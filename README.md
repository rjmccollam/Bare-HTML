##HTML Development Files

A starting point for HTML and CSS projects. Typically I use this as a starting point for my WordPress builds so the CSS has some WordPress styles and bloginfo already in it.

###CodeKit
I use CodeKit to handle all of my tasks as I work. It compiles my Sass, concatonates and minifies my javascript, and a whole bunch of other stuff. I have included my codekit.config in this repo so it can be as easy as dragging the project folder into CodeKit and then you are up and running. If you don't have CodeKit you can purchase it here https://incident57.com/codekit/

###Sass
This starter bundle uses Sass as a CSS preprocessor. I like my Sass handled a specific way and that is setup in the codekit.config file, but obviously you can set it up however you want.

###Retina Images
retina.js is prepended to scripts.js and will handle all of your inline retina image needs. You can learn more about it and how it works at http://retinajs.com/. There is also a mixin called retina-sprite that you can use to handle all of your retina images in CSS. Take a look at the mixin as you may have to change the path to the file as well as the background size to get it working.

####Credits
- Meyers Web CSS Reset used under public domain http://meyerweb.com/eric/tools/css/reset/
- HTML5 Shiv dual licensed under the MIT or GPL Version 2 licenses https://code.google.com/p/html5shiv/