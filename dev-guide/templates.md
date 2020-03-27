## Template Structure
**ListPlus** template files contain the markup and template structure for frontend of your listings.

When you open these files, you will notice they all contain hooks that allow you to add/move content without needing to edit template files themselves. This method protects against upgrade issues, as the template files can be left completely untouched.

Template files can be found within the` /listplus/templates/` directory.

## Overriding Templates via a Theme

Edit files in an upgrade-safe way using overrides. Copy the template into a directory within your theme named `/listing/` keeping the same file structure but removing the `/templates/` subdirectory.

Example: To override the admin order notification, copy: `/wp-content/plugins/listplus/templates/archives.php` to `wp-content/themes/yourtheme/listing/archives.php`

The copied file will now override the ListPlus default template file.

**Warning**: Do not edit these files within the core plugin itself as they are overwritten during the upgrade process and any customizations will be lost.


## Overriding Templates via Hoook.
```php
function your_template( $file, $template ){
    $new_file = YOUR_PLUGIN_DIR.'/path/to/your/'.$template;
    return $new_file;
}
add_filter( 'listplus_locate_template', 'your_template', 15, 2 );
```