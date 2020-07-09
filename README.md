# How-can-you-check-if-you-are-in-a-particular-page-in-the-WP-Admin-section

When developing some custom plugin in WordPress, you need to figure which current page is loaded. 

There could be more ways but here I am showing 2 ways.

1) Using $pagenow Global variable.

Using this you can get the current loaded page e.g admin.php as in the screenshot and then the $_GET request to figure out the actual page loaded in the WordPress.

2) Using get_current_screen() function

Using get_current_screen() function you can access the get current screen object. You can read its documentation at https://developer.wordpress.org/reference/functions/get_current_screen/.

The output of this function is displayed in the screenshot.
