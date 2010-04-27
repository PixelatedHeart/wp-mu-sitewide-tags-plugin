=== WordPress MU Sitewide Tags Pages ===
Contributors: donncha, imwebgefunden, wpmuguru
Tags: wordpressmu
Tested up to: 2.7.1
Stable tag: 0.4.0.1
Requires at least: 1.5.1
Donate link: http://ocaoimh.ie/wordpress-plugins/gifts-and-donations/

A central area where all the posts on a WordPress MU site can be collected.

== Description ==
This plugin creates a new blog on your WordPress MU system for all the posts on your site, much like http://wordpress.com/tags/

For performance reasons the number of posts is limited to a user configurable amount, and the blog itself can be made indexable by search engines or not.

== Install ==
1. Copy sitewide-tags.php into wp-content/mu-plugins/
2. Login as a site administrator and go to Site Admin, Options. A number of extra options are created:
	1. "Tags blog" defaults to "tags" but can be anything. This is the blog where your sitewide posts will live. It will be created if it doesn't exist.
	2. Check "Post to main blog" to use your main blog as the tags blog.
	3. "Max posts" defaults to 5000. Older posts will be deleted if this threshold is broken.
	4. Check "Include Pages" to include both posts and pages, handy for making a sitewide search.
	5. "Privacy" defaults to public, pages can be indexed by search engines.
	6. When "Privacy" is not public, check "Non-Public Blogs" to include blogs not indexed by search engines.
	7. Add "Post Meta" custom fields to be copied with posts/pages.

== Changelog ==

= 0.4.0.1 =
* Bug fix - only push published content to the tags blog

= 0.4 =
* Added option to include pages in tags blog.
* Added option to include non search engine indexed blogs if tags blog not indexed.
* Added option for post meta to be copied with post.
