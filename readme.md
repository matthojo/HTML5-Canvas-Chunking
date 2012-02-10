# [HTML5 Canvas Chunking](http://labs.matthojo.co.uk/canvasChunking/)

Automatically chunks out specified area and allows for markers to be placed into chunks (maybe for mapping, etc.). It also only renders chunks within the Canvas frame itself, which keeps performance high.

*Example*

* 800 x 600 w/ 20 markers :: 60+ FPS
* 8000 x 6000 w/ 1000 markers :: 60+ FPS (Possible slight drop at maybe 1FPS in some browsers).


## Features

* Specify chunk size
* Specify content size (width and height of chunked area)
* Add markers relative to chunk (e.g a marker at x:10, y:10 will be at those co-ordinates inside the chunk, not the canvas.)
* Only renders chunks within canvas frame (with 1 chunk outside for smooth panning of chunks).
* You can pan the content to reveal more chunks and their markers.


## Special Thanks

* [Sophie Meredith](http://sophie-meredith.co.uk)


## License

### Major components:

* [jQuery](http://jquery.com/): MIT/GPL license
* [Modernizr](http://www.modernizr.com/): MIT/BSD license
* [FPS stats](https://github.com/mrdoob/stats.js): MIT
* [HTML5 Boilerplate](http://html5boilerplate.com/): Public Domain
* [Bootstrap](http://twitter.github.com/bootstrap/): Apache 2.0

### Everything else:
[GPL 2.0 license](http://www.opensource.org/licenses/gpl-2.0.php)

Copyright 2012 Matthew Harrison-Jones
