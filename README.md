minifront
=========

A simple, server agnostic, minimal HTML5/CSS3/jQuery/PHP skeleton with some features and ideas from [HTML5Boilerplate](http://html5boilerplate.com/), [HTML5Reset](http://html5reset.org/), [Modernizr](http://modernizr.com/) and the [LESS 4 Framework](http://lessframework.com/).

Useful to develop static pages or small websites focusing on the UI before going into back-end development.


## How it works

Just start coding the HTML5 in header.php, index.php and footer.php. Then add some CSS3 awesomeness to css/style.css, throw some jQuery plugins in js/plugins.js, fight with your semicolons in js/start.js and you'll be ready to go writing some Ruby.


## Filesystem Structure

### header.php
- Conditional IE comments to avoid loading different external stylesheets.
- Minimal custom modernizr.js HTML5 Shim.
- Simple title variable specified in the index.php file.

### index.php
- Title variable passed to header.php

...