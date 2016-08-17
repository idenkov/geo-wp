=== Plugin Name ===
Contributors: Ivan Denkov
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=R9SL7M6CUU6BE
Tags: geo-redirect, geographical-redirect, geoip, multilanguage, multidomain
Requires at least: 4.3
Tested up to: 4.3
Stable tag: 1.0

Redirect visitors on your site, according to their geographical location.

== Description ==

You have multiple languages on your site and you want the visitors to be automatically redirected to the language for their country.
You have different versions of your site and you want to the right domain/subdomain based on their geographical location.

Go to Settings -> GeoIP Redirect, choose the country from the dropdown, and where do you want to redirect.
It is best first to test the redirection you want to use with your country to see how they work for you.

This plugin uses MaxMind GeoLite geolocation database for country detection.

== Installation ==

1. Unzip `geoip-redirect.zip`
2. Upload `geoip-redirect` folder to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= My browser says that the page is redirect loop. =

Add to the end of the url "?no_redirect" example - "http://example.com/page/?no_redirect"

== Changelog ==

= 1.0 =
* Initial release.
