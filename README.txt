=== Easy Clickheat Wordpress Intergration Plugin ===
Contributors: Adam Sayler from Impression Engineers
Plugin homepage: http://www.impressionengineers.com/wordpress/clickheat-wordpress-intergration-plugin/
Tags: stable, clickheat, labs media, plugin
Requires at least: 2.0
Tested up to: 2.8.2
Stable tag: 1.0

A plugin to easily and quickly integrate the Labs Media Clickheat tracking system in your Wordpress site.

== Description ==

A plugin to easily and quickly integrate the Labs Media Clickheat tracking system in your Wordpress site.

== Installation ==

Clickheat Install

1.) Download and install the Clickheat system from Labs Media.  Download and install the Clickheat system into a folder called "clickheat" in your root web folder. i.e. http://www.mydomain.com/clickheat

Download
http://sourceforge.net/project/showfiles.php?group_id=181196

Instructions
http://www.labsmedia.com/clickheat/installation.html

Plugin Install

1. Unzip and upload the clickheat.php file into your `/wp-content/plugins/` directory
2. Please verify that your current theme has the code wp_footer() installed at the bottom of the template
3. Activate the plugin through the ‘Plugins’ menu in WordPress
4. Verify the tracking code was installed correctly by verifying the comment in the footer of your source code starting with <!-- Clickheat code by http://www.impressionengineers.com.
5. Test the system by adding the "?debugclickheat" debug code to the end of any page link on your site. i.e. http://www.site.com/page-or-post-slug/?debugclickheat

Please note: the system will not track clicks from admin users that are logged in.

== Frequently Asked Questions ==

1. The system will not track clicks from admin users that are logged in.  You must be logged out of the Wordpress admin section to get the tracking code to register a click.

2. How to install Clickheat  http://www.labsmedia.com/clickheat/installation.html

http://www.impressionengineers.com/wordpress/clickheat-wordpress-intergration-plugin/

== Screenshots ==

== Changelog ==

= 1.0 =
* Initial public release 