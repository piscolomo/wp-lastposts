wp-lastposts
============

A web component made with Polymer to display recent posts from Wordpress

First you need a url to expose the API posts from Wordpress, I use the [JSON API Plugin](https://wordpress.org/plugins/json-api/)

That's it, now import wp-lastposts.html in your theme, don't forget the script referenced to platform.js

And add the web component wp-lastposts

> <wp-lastposts nposts="5"></wp-lastposts>

Use the attribute nposts to indicate how many recent posts do you need to display (default is one)
