=== Steply ===
Contributors: vivex
Donate link: http://vivex.me/
Tags: steps, howoto, tutorial
Requires at least: 4.6
Tested up to: 4.7
Stable tag: 4.3
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Adds wikihow style step by step UI, good for tutorial websites.

== Description ==

This is a shortcode plugin, with help of that you can create step sections in your post/page.
This helps if you are writing any tutorial and want to separate content each step.
We will be adding few more features soon

[Steply Demo](http://w3.cafe/blogs/tutorials/tutorial-hosting-your-js-html-project-on-firebase "Steply Demo")


== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload the plugin files to the `/wp-content/plugins/steply` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Use the Settings->Setply Settings Option to change color of steps heading background
1. Use following short code:

```
[steply_wrapper]
            [steply_step step-number='1' title='Step Title']
                  Step Content
            [/steply_step]
[/steply_wrapper]
```

== Frequently Asked Questions ==

= Any live demo =

Please check this post:  [Steply Demo](http://w3.cafe/blogs/tutorials/tutorial-hosting-your-js-html-project-on-firebase "Steply Demo")

== Screenshots ==

1. Example.
2. Admin settings

== Changelog ==

= 1.0 =
* Initial release

== Upgrade Notice ==
= 0.1 =
Initial release
