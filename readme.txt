Instructions:
Place the function call in wherever you want the recent posts to appear.
<?php mdv_recent_posts(); ?>

Configuration:
You may pass parameters when calling the function to configure some of the options.
Example: mdv_recent_posts(10, '', '<br />', true, 5, false)

The parameters:
$no_posts - sets the number of recent posts to display

$before - text to be displayed before the link to the recent post

$after - text to be displayed after the link to the recent post

$hide_pass_post - whether or not to display password protected posts

$skip_posts - allows skipping of a number of posts before showing the number of posts specified with the $no_posts parameter

$show_excerpts - allows the post excerpt to be output after the post title