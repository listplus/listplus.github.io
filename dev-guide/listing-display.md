## Adding Display Listing Item

```php
function your_display_fields( $fields ){
    $fields[] = [
		'id' => 'your_id',
		'_type' => 'preset',
		'title' => __( 'Your field title', 'list-plus' ),
	],
    return $fields;
}
add_filter( 'listplus_listing_display_fields', 'your_display_fields' );
```

## Display Listing Field

```php

function your_display_function( $item ){
    $listing = \ListPlus\get_listing();
    var_dump( $listing->to_array() );
}

function your_display_field_callback( $callback, $item ){
    if ( 'your_id' == $item['id'] ) {
        $callback = 'your_display_function';
    }
    return $callback ;
}

add_filter( 'listplus_listing_display_field', 'your_display_field_callback', 15, 2 );
```