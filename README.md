# Readme to Slideshow
Just upload this on a server or local to have a clock with background images.
It's perfect to put on an old laptop or other device.

You can adjust the settings and change the images easily in slideshow.html on line 60

Factory settings:

var urls = ["1.jpg", "2.jpg", "3.jpg", "4.jpg", "5.jpg"];
var percentageWatch = false; // change this if you like your minutes as percentage of an hour
var timeUntilImageChanges = 4000; // in miliseconds
var timeToFade = 1000; // miliseconds. 1000ms = 1s

It's suggested to use downsized images. Big images use lots of RAM.

Thanks to jQuery Backstretch which does most of the work!