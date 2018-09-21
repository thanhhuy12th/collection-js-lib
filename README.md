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
<script src="lib/easing/easing.js"></script>
<script>
    $('.scroll-top, #logo a').click(function(){
        $("html, body").animate({
          scrollTop: 0
        }, 1000, 'easeInOutExpo');
        return false;
    });
</script>
```
## SuperFish menu custom
Using to create smart menu (navigator). Add mobile style
```
<!-- HTML code -->
<!-- Nav  -->
<nav id="nav-menu-container">
    <div class="logo pull-left">
        <a href="#">LOGO</a>
    </div>
    <ul class="nav-menu pull-right">
        <li><a href="#aboutUs">home</a></li>
        <li><a href="#features">features</a></li>
        <li><a href="#portfolio">portfolio</a></li>
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
        <li><a href="#contact">contact</a></li>
    </ul>
    <div class="clearfix"></div>
</nav>
<!-- Include script -->
<script src="lib/fish-menu/js/hoverIntent.js"></script>
<script src="lib/fish-menu/js/superfish.js"></script>
<script src="lib/fish-menu/js/main.js"></script>
```
## Parallax
Using to create amazing background. Must include by step: 1. stellar.js -> 2. paralax.js
```
<!-- HTML code -->
<div class="parallax text-center" id="parallax" data-bg-img="img/parallax-bg.jpg" data-settings='{"stellar-background-ratio": 0.2}' data-toggle="parallax-bg"> </div>
<!-- Include lib -->
<script src="lib/parallax/stellar.min.js"></script>
<script src="lib/parallax/parallax.js"></script>
```
## Sticky
Using to stick an element as fixed
```
<!-- Sticky something -->
<script src="lib/stickyjs/sticky.js"></script>
<script>
    $("#header").sticky({topSpacing:0, zIndex: '50'});
</script>
```
