=== Latest Post ===
Contributors: Dasinfomedia	
Tags: mootools, fontpage slider,carousel slider,sliding content,showcase latest post,latest post,pramote latest post on front page.
Requires at least: 2.6
Tested up to: 2.8
Stable tag: 1.0

A plugin for wordpress which shows the latest 10 post slider. 

== Description ==

Latest Post plugin will show the latest 10 post. User can set the height, width, and the time duration of the slide show. Post will be shown with the link by clicking on it user can view particular post.

[plugin home page](http://blog.dasinfomedia.com/?p=3)

= Features =
* Templating, one can edit the al_template.php and caruosel_css.php file to change the design and css.
* Configuration under Options/Latest post settings in the dashboard.


== Installation ==

1. Unzip and copy the "latest-post-carousel" folder inside your "wp-content/plugins" folder. 
1. Go to your administration interface for plugins and activate "Latest Post Carousel Slider".
1. If you are using the dynamic sidebar (widgets) you can now drag and drop AJAX Login in the widgets administration. If not you can add the template tag "get_ajaxlogin()" in your templates, for example in sidebar.php

== Frequently Asked Questions ==

= Fake loading screen? What are you, stupid? =
Good question. My test users (as well as I) became confused when the switch was instant. The different screens do not differ enough. A loading screen for a second or so seem to make our brains re-interpret the content and avoid confusion.

= Fair enough, but I still don't want it, how do I turn it off? =
Just go to the options in your dashboard and set Fake loading screen timeout to 0.

= Can I customize the widget? =
Yes. Both the widget and the template tag "get_ajaxlogin()" by default use the al_template.php in the plugin directory.
To have your own just make a copy of al_template.php and put in your theme directory along with the other templates.
