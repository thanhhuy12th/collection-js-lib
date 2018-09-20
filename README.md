# collection-js-lib
All collection javascript library that i collected and used in my project
## Counter up
Using to count number up.
Must use by step: counterup.js -> waypoints.js (To handle scroll event)
```
$('.cirtle-count').counterUp({
    delay: 10,
    time: 1000
});
```
## Easing
Using to make smooth scrolling
```
$('.scroll-top, #logo a').click(function(){
    $("html, body").animate({
      scrollTop: 0
    }, 1000, 'easeInOutExpo');
    return false;
  });
```
