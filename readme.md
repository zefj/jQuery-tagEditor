jQuery-tagEditor
================

A powerful and lightweight tag editor plugin for jQuery.

Compatible with jQuery 1.7.0+ in Firefox, Safari, Chrome, Opera, Internet Explorer 8+. IE7 technically works, but no care has gone into CSS/layout bugs. No dependencies except the jQuery library.
Released under the MIT License: http://www.opensource.org/licenses/mit-license.php

This plugin was developed by and for Pixabay.com - an international repository for sharing free public domain images.
We have implemented this plugin in production and we share this piece of software - in the spirit of Pixabay - freely with others.

## Demo and Documentation

http://goodies.pixabay.com/jquery/tag-editor/demo.html

## Features

* Lightweight: 9.3 kB of JavaScript - less than 3.4 kB gzipped
* Edit in place tags
* Intuitive navigation between tags with cursor keys, Tab, Shift+Tab, Enter, Pos1, End, Backspace, Del, and ESC
* Optional jQuery UI sortable
* Optional jQuery UI autocomplete
* Copy-paste or delete multiple selected tags
* Duplicate tags check
* Custom delimiter/s
* Placeholder
* Custom style for faulty tags
* Public methods for reading, adding and removing tags + destroy function
* Callbacks
* Graceful degradation if JavaScript is disabled

## Changelog

### Version 1.0.2 - 2014/07/16

* Fixed removal of placeholder after calling addTags.

### Version 1.0.1 - 2014/07/16

* Fixed tagEditor for IE8 and IE7. IE7 still has some obvious layout alignment bugs, that can be fixed by conditional CSS rules.

### Version 1.0.0-beta - 2014/07/15

* First release
