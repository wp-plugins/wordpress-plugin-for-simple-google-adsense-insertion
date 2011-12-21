=== WP Simple Adsense Insertion ===

Contributors: Ruhul Amin
Donate link: http://www.tipsandtricks-hq.com/
Tags: Google Adsense, WordPress Plugin,
Requires at least: 3.0
Tested up to: 3.3
Stable tag: 1.4

Easy to use Wordpress plugin to insert Google Adsense to your WordPress posts, pages and sidebar.

== Description ==

Use this plugin to quickly and easily insert Google Adsense to your posts, pages and sidebar by using a trigger text or calling the php function.

There are many plugins and services which can add Google Adsense to your WordPress site. However I found that even though something like Adsense Manager or Adsense Deluxe provides a lot of customizable options, it can be overwhelming and isn't really simple enough for people who are new to WordPress.

I found that most of the time I only use two or three types of Google Adsense units in various places and posts throughout my sites.That's why I wrote my own Simple Adsense Insertion Plugin for WordPress, to focus on having 1-4 Google Adsense codes saved and use them where ever I want on my site by inserting a simple trigger text to my posts,pages and sidebar.

For information and updates, please visit:
http://www.tipsandtricks-hq.com/?page_id=170

= Usage: =

There are two ways you can use this plugin:

Use the shortcodes: 

* [wp_ad_camp_1]
* [wp_ad_camp_2]
* [wp_ad_camp_3]
* [wp_ad_camp_4]

Call the function from template files:

* <?php echo show_ad_camp_1(); ?>
* <?php echo show_ad_camp_2(); ?>
* <?php echo show_ad_camp_3(); ?>
* <?php echo show_ad_camp_4(); ?>

== Installation ==

1. Unzip and Upload the folder 'WP-Simple-Adsense-Insertion' to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to Settings and configure the options eg. Copy and paste the Google Adsense code that you want to use.
4. Add the trigger text [wp_ad_camp_1] to a post or page where you want it to appear.

== Frequently Asked Questions ==

= Does this plugin allow complex adsense management? =

No.

= I am updating an older version of the plugin.  Will it still work? =

The method for displaying ads changed in version 1.2.  The old style will continue to work in this version, but it highly suggested that you update all the adcode in your content to the new method.

An easy way to do this would be to install the find/replace plugin (http://wordpress.org/extend/plugins/search-and-replace/) and update all your old tags.  E.g. Find <!-- wp_ad_camp_1 --> and replace it with [wp_ad_camp_1].

== Screenshots ==  

1. Check out this Plugin in action at http://www.tipsandtricks-hq.com

== Changelog ==

Please see this page for changelog:
http://www.tipsandtricks-hq.com/wordpress-plugin-for-simple-google-adsense-insertion-170
