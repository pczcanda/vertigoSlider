vertigoSlider
=============

This is a responsive vertical slider that can be easily adapted and customised.

Plugin is available as of 14 Sept 2013 with the following features

This plugin allows you to have a list of content that the slider can go through:

 - For each slider images are not included in the markup but these are loaded dynamically, 
   decreasing the page download speed;
 - Each slider requires a title element and a content element that will be picked up upon creation
   of the slides. At the moment these require the same class names as shown on the example markup;
 - Certain elements can be made disabled, like dots, navigation buttons, content container and others


AVAILABLE OPTIONS
slide_speed: (int) this is the speed, in milliseconds, of a slide change
easing: (string)
autoLoop: (boolean) determine whether the slides will loop automatically. This will go down by definition
autoLoopTime: (int) this is the time, in milliseconds, for a slide to stay when autoloop is true
showDots: (boolean) determines whether to show the slider dots
showNav: (boolean) determins whether to show the slide navigation buttons
startIndex: (int) the start index of the slider
animateChange: (boolean) determines whether to animate the slide change
contentContainer: (boolean) determines whether to show and update the content box
showDotsNav: (boolean) determines whether to show the up and down arrows for the dots box
onBeforeSlide: (function) this is triggered before the slide animation - this can be called from the slider or externally
onAfterSlide: (function) this is triggered after the slide animation - this can be called from the slider or externally

DEFAULTS

Some of the options already have defaults for ease of use.

slide_speed: 500,
easing: 'swing',
autoLoop: false,
autoLoopTime: 5000,
showDots: false,
showNav: false,
startIndex: 0,
animateChange: true,
contentContainer: true,
showDotsNav: true
