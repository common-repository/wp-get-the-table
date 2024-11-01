=== Plugin Name ===
Contributors: jonsisk
Donate link: http://www.chalkbeat.org/donate
Tags: html, table
Requires at least: 1.0
Tested up to: 5.0.3
Stable tag: 1.5
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

A plugin that lets you grab an HTML table from a URL by ID or Class, and echo it out onto a page via shortcode.

== Description ==

A plugin that lets you grab an HTML table from a URL by ID or Class, and echo it out onto a page via shortcode. Use your own stylesheets and responsiveness with on-page table elements rather than ugly iframe embeds of offsite data.

== Installation ==

Upload and activate the plugin to enable the shortcode.

Shortcode usage:
----------------

	-- Parameters --
	
	url="" 		URL to scrape table from
	id=""		ID of table to scrape
	class=""	Class of table to scrape (will scrape first table on the page with matching class)
	mobile=""	Mobile version breakpoint
	tablesorter	Enable the tablesorter javascript

	-- Examples --

	[getthetable url="" id=""] - Basic Format
	[getthetable url="http://www.itjon.com/getthetable" id="getthetable" mobile="600"] - This will grab the sample table off the plugin page, with mobile version <600px width>
	[getthetable url="http://www.itjon.com/getthetable" id="getthetable" mobile="600" tablesorter] - The tablesorter argument adds the tablesorter js and css from cdn.ucb.org.br and applies it to your table


== Frequently Asked Questions ==

== Screenshots ==

== Changelog ==

= 1.5 =
* Added option to grab table by Class or just the first table at the URL if neither ID nor Class is specified. If both ID and Class are specified, only ID will be used. Also if neither is specified and the tablesorter option is used, it will apply to all tables on the output page.

= 1.4 =
* Added tablesorter images, moved css to function and js to own directoriy, added stacktable js for mobile and mobile breakpoint option

= 1.3.1 =
* Styled debug output

= 1.3 =
* Added debug mode

= 1.2 =
* Added tablesorter js and css to plugin codebase

= 1.1 =
* Added verification and error handling for bad URL/ID and tablesorter option

= 1.0 =
* Initial Release

== Upgrade Notice ==

== Arbitrary section ==