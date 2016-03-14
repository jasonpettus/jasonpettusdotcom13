# jasonpettusdotcom13
These are the source files for the recent overhaul of my personal website, [jasonpettus.com](http://www.jasonpettus.com), home of my archived creative work from the 1980s and '90s, as well as the home of my weekly personal long-form journal. I've included them here at Github for the sake of any fellow front-end developers who wish to see how I went about doing a particular thing, and in case any potential employers were interested in seeing them. Please feel free to use as little or as much of this as you want at your own website, as long as you continue to credit the third-party sources I used during my own development. For a lengthier and more digressive essay on the considerations that went into making this design scheme, [click here](http://jasonpettus.com/archives/001622.html).

I've posted two versions of the code; one is formatted as a standalone "static" site, which might be better for looking at just to check out the code itself, while the other includes all the markup needed to run the pages on the [Movable Type](http://www.movabletype.org/) content management system I use for my site.

This was created using HTML5, CSS3 and JavaScript, including CSS animation features. It was designed responsively to present different layouts on cellphone, tablet, laptop/desktop, media center on a television, and printed onto paper; see the CSS specs for more. It relies on the following third-party services and tutorials...

* [Google Web Fonts](https://www.google.com/fonts) for providing the typefaces
* [jQuery](https://jquery.com/) to simplify and automate part of the JavaScript
* [scrollMonitor](https://github.com/stutrek/scrollMonitor), a JS library that simplifies the tracking of DOM elements as they scroll; and [this tutorial](http://creative-punch.net/2014/03/making-scroll-dependent-menu-bar-css3-javascript/) by Creative Punch on how to implement it
* [This tutorial](http://www.webdesignerdepot.com/2013/07/how-to-create-a-simple-parallax-effect/) by Sara Vieiera of Web Designer Depot on how to properly code a parallax scroll function in JavaScript and CSS
* Ethan Marcotte's book [Responsive Web Design](https://abookapart.com/products/responsive-web-design) for much-needed advice on using media queries
* With thanks to [John Paul Davis](http://www.johnpauldavis.org/) for helping me fine-tune my JavaScript

## Still Coming Throughout 2016

* Fancy jQueryUI interface for interacting with the archives
* Better search result page
* Remove tic from main menu when it transitions from scrolling to fixed
* Script for inserting a random backbground image with each new refresh

#### By the way, I'm a recent DevBootcamp graduate and front-end developer, currently seeking a great new place to call home. For more, see my [resume website](http://jasonpettus.github.io) and [LinkedIn profile](http://www.linkedin.com/in/jasonpettus), or drop me a line at ilikejason@gmail.com.