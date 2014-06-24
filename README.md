sketch-slicy
============

Sketch app plugin inspired by [Slicy](http://macrabbit.com/slicy/) app.

Requires [Sketch Beta](http://bohemiancoding.com/sketch/beta/)

![screenshot](https://raw.githubusercontent.com/timuric/sketch-slicy/master/README/screenshot.png)

###Features:
* Web friendly assets names
* Exports layers with similar names
* Assets clean up (Deleted layers/sizes from document automatically being removed from assets folder)
* it is free

###Usage:
* Add extension to the layer or group name to generate an asset, like so `icon.png`
* `icon.png+@2` - Would generate original asset plus retina version that would be named `icon@2.png`
* `icon.png@2` - Would generate only one asset (which would be double the size)