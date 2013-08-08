Hide Default WordPress Taxonomies
=================================
Removes and/or hides most post category and tag functionality from the WordPress admin.

+ 'QuickPress' dashboard widget tags input
+ 'Right Now' dashboard widget categories and tags display
+ Categories and tags submenu items
+ Post edit screen category and tag meta boxes
+ Category and tag columns and category filter on edit.php
+ 'Quick edit' form category and tag inputs
+ Nav menu category and tag meta boxes

## Intended Usage

The plugin is intended as a quick fix for hiding most interface elements related to default post taxonomies via actions, filters and \*yikes\* css. It does not try to unregister the default taxonomies nor provides a complete removal of all taxonomy related functionality.

Settings area remains untouched. Users with the correct capability will still be able to navigate to wp-admin/edit-tags.php?taxonomy=category and wp-admin/edit-tags.php?taxonomy=post_tag.