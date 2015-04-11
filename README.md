#Web Page with Hover State Button

This is a web page built using *HTML5* . The styling has been done using *CSS3 Scripts (Bootstrap)*.
The color scheme of the web page is according to the project that was undertaken.
The web page contains a button in Hover State , a Hover Card will appear when the mouse pointer is brought over the button . The Hover card has ben built using *Javascript* .
The codes used for the Hover card is :

```Javascript
$('.hovercard').hover(function() {
$(this).stop(true, false).show();
}, function() {
$('.hovercard').hide();
});
$('#images li').hover(function() {
$(this).find('.hovercard').delay(100).fadeIn(); // show() doesn't seem to work with delay
}, function() {
$(this).find('.hovercard').delay(100).fadeOut('fast');
});    
```