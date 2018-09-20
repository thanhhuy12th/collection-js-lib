# collection-js-lib
All collection javascript library that i collected and used in my project
## Counter up
Using to count number up.
Must use by step: counterup.js -> waypoints.js (To handle scroll event)
```
<script src="lib/counterup/counterup.min.js"></script>
<script src="lib/counterup/waypoints.min.js"></script>
<script>
    $('.cirtle-count').counterUp({
        delay: 10,
        time: 1000
    });      
</script>
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
## SuperFish menu custom
Using to create smart menu (navigator). Add mobile style
```
<!-- Include script -->
<script src="lib/fish-menu/js/hoverIntent.js"></script>
<script src="lib/fish-menu/js/superfish.js"></script>
<script src="lib/fish-menu/js/main.js"></script>
<!-- HTML code -->
<nav id="nav-menu-container" class="pull-left">
    <ul class="nav-menu">
        <li><a href="#aboutUs">about us</a></li>
        <li><a href="#features">features</a></li>
        <li><a href="#portfolio">portfolio</a></li>
        <li><a href="#team">team</a></li>
        <li class="menu-has-children">
            <a href="#">dropdown</a>
            <ul>
                <li><a href="#">dropdown 1</a></li>
                <li class="menu-has-children">
                    <a href="#">dropdown 2</a>
                    <ul>
                        <li><a href="#">Deep dropdown 1</a></li>
                        <li><a href="#">Deep dropdown 2</a></li>
                        <li><a href="#">Deep dropdown 3</a></li>
                        <li><a href="#">Deep dropdown 4</a></li>
                    </ul>
                </li>
                <li><a href="#">dropdown 3</a></li>
                <li><a href="#">dropdown 4</a></li>
                <li><a href="#">dropdown 5</a></li>
                <li><a href="#">dropdown 6</a></li>
            </ul>
        </li>
        <li><a href="#contact">contact us</a></li>
    </ul>
</nav>
```
## Parallax
Using to create amazing background. Must include by step: 1. stellar.js -> 2. paralax.js
```
<!-- Include lib -->
<script src="lib/parallax/stellar.min.js"></script>
<script src="lib/parallax/parallax.js"></script>
<!-- HTML code -->
<div class="parallax text-center" id="parallax" data-bg-img="img/parallax-bg.jpg" data-settings='{"stellar-background-ratio": 0.2}' data-toggle="parallax-bg"> </div>
```
