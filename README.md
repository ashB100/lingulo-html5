lingulo-html5
=============

A responsive HTML5 website from tutorial (http://www.lingulo.com/) 

1. Use the viewport meta tag defines how the website should be displayed on a device. 
Setting width to device-width sets the width of the viewport to the width of the device
and initial-scale to 1.0  and sets the inital zoom level to 1.0.  There is debate on whether to use width=device-width only, as this width doesn't workout for landscape orientation which should use height instead. 
or initial-scale=1.0 only as it might have zoom problems in iOS.

2. Use Eric Meyer's Reset CSS.

3. Use Lightbox2 to overlay images on top of current page when a smaller image is clicked.

4. Use Google Web Fonts to use Open Sans and Baumans

5. Use Modernizr.js to detect the browsers support of HTML5 and CSS3 features

6. Use html5shiv to enable HTML5 elements in Internet Explorer. 

7. Use Respond.js to allow Media Queries support in IE and other browsers that might not support Media Queries.

8. Use Prefix Free which automatically creates the required prefixes and lets us write unprefixed CSS3 properties. 

9. Use HTML5 semantic elements which help us create more sturctured and searchable web pages by telling screen readers
and search engine bots what is on a page which helps them to read only the parts they want. The semantic elemnts used:
** section
** nav
** article
** header - hide the headings that we don't want to display using CSS clip property
** footer

10. Use the responsive slideshow plug-in SlideJs for slideshow. 


Todo: 
1. Use sass
2. Minify files
3. Use icons instead of images
4. Change fonts to rems instead of px
