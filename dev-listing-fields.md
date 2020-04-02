## Adding Custom Listing Field

```php
function your_listing_field( $fields ){
    $fields[] = [
		'id' => 'your_field_id',
		'_type' => 'preset', // preset or custom.
		'title' => __( 'Your Field Type', 'list-plus' ),
		'type' => 'text', // Input type.
		'name' => 'your_field_name',
	],
    return $fields;
}
add_filter( 'listplus_listing_fields', 'your_listing_field' );
```