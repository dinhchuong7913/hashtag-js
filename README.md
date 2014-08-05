Hashtag.js
=====

Hastag.js is a js library for finding and replacing hashtags in strings. Useful when working with your own backends that use social media feeds.
  
Installation
------------

Hashtag.js does not require jQuery or any other libraries, it's written in plain Vanilla JS. To install, just include the script in your document:

```
<script type="text/javascript" src="hashtag.min.js"></script>

```

Basic usage
-----------

```
Hashtag.replaceTags('#myDiv');
```

As simple as that! Let's say that #myDiv looks like this:

```
<div id="myDiv">
  #hashtags are #cool
</div>
```

After running the replaceTags() function, the tags will be replaced:

```
<div id="myDiv">
  <span class="tag">#hashtags</span> are <span class="tag">#cool</span>
</div>
```

Setting options
---------------

You can set options for the library by using the setOptions() function and passing an object to it.

Templates
---------

Hashtags.js supports a simple templating system for replacing tags. 
