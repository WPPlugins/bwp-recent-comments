=== Better WordPress Recent Comments ===
Contributors: OddOneOut
Donate link: http://betterwp.net/wordpress-plugins/bwp-recent-comments/#contributions
Tags: comments, recent comments, recent comments widgets
Requires at least: 2.8
Tested up to: 3.1.2
Stable tag: 1.1.0

This plugin displays recent comment lists at assigned locations, with comprehensive support for widgets.

== Description ==

This plugin displays recent comment lists at assigned locations. It does not add any significant load to your website. The comment list is updated on the fly when a visitor adds a comment or when you moderate one. No additional queries are needed for end-users.

A recent comment list, in my opinion, can help stimulate discussion and exploration of your blog tremendously. Now for the past few months I have been using a plugin called Get Recent Comments; though this plugin is configurable and indeed popular, the code is somehow messy and no support for custom post type is found. The worst thing is Get Recent Comment doesn't seem to be updated anymore, so I decide to write another recent comment plugin which is more lightweight and makes use of some nice features provided by WordPress 3.0.

**New Features in 1.1.0**

* You can now show comments on a separate page, with pagination and custom template!
* Get comments from a specific post, using either ID or post name (slug).
* Trim post title to a certain number of words.

**Other Features**

* Has the options to show comment only, trackback only, or show both (separately or all together)
* Possibility to add different comment lists with different settings on one page
* You can sort comment lists descendingly or ascendingly
* Supports custom post type
* Supports Gravatar
* Supports smiley
* Widget-ready
* Template functions ready
* Generate Zero SQL query for end-users
* Possibility to trim comment to a specific number of words
* Possibility to split long words into smaller chunks
* WordPress Multi-site compatible (not tested with WPMU)
* And more...

**Get in touch**

* I'm available at [BetterWP.net](http://betterwp.net) and you can also follow me on [Twitter](http://twitter.com/0dd0ne0ut).
* Check out [latest WordPress Tips and Ideas](http://feeds.feedburner.com/BetterWPnet) from BetterWP.net.

**Languages**

* This plugin is currently available only in English. Please [help translate](http://betterwp.net/wordpress-tips/create-pot-file-using-poedit/) it!

Visit [Plugin's Official Page](http://betterwp.net/wordpress-plugins/bwp-recent-comments/) for more information!

== Installation ==

1. Upload the `bwp-recent-comments` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the Plugins menu in WordPress. After activation, you should see a menu of this plugin on your left. If you can not locate it, click on Settings under the plugin's name.
1. Configure the plugin
1. Enjoy!

[View instructions with images](http://betterwp.net/wordpress-plugins/bwp-recent-comments/installation/).

== Frequently Asked Questions ==

[Check plugin news and ask questions](http://betterwp.net/topic/bwp-recent-comments/).

== Screenshots ==

1. Showing recent comments using customizable widget
2. Paginated comment list on a separate page with custom template
3. The configuration page

== Changelog ==

= 1.1.0 =
* You can now show comments on a separate page, with pagination and custom template!
* You can also get comments from a specific post, using either ID or post name (slug)!
* It's now possible to trim post title to a certain number of words.
* Implemented a new way to exclude certain comment authors, using a user's id.
* Added a translation tag to `%post_title%` to make this plugin compatible with multi-lingual websites/blogs.
* Fixed the non-functional `%post_link%` template tag.
* Other unspecified enhancements and bug fixes ;).

To see the awesomeness of this major release, take a look at the [release announcement] (http://betterwp.net/237-bwp-recent-comments-1-1-0/)! Thanks for using this plugin!

= 1.0.1 =
* Fixed the bug that strips legit HTML tags in comment templates. Thanks to [Mike McKoy](http://www.hairwegoproducts.com/)!
* Fixed the bug that prevents empty comment templates.
* Fixed the widget class so that it functions more expectedly.
* Fixed some minor bugs that might cause notice or warning messages. Thanks to **Konstantin**!
* Added a reset instances button that will reset all malformed instances caused by 1.0.0's bugs.
* It is now possible to have HTML in 'no comment' and 'stripped comment' message.
* Comments that belong to trashed posts are no longer included in comment lists.

= 1.0.0 =
* Initial Release.

== Upgrade Notice ==

= 1.0.1 =
* A critical bug fix release, all users are advised to update immediately!

= 1.0.0 =
* Enjoy the plugin!