Sticky Footer
=============

Basic CSS that makes your Bootstrap footer stick to the bottom of the screen.

This is a stylesheet you can include that will make sure your ```<footer>``` element or any element with a class of footer will stick to the bottom of the screen, even if there is only a bit of content.

It comes from [this article](http://ryanfait.com/resources/footer-stick-to-bottom-of-page/). I just made a quick stylesheet that works with [Bootstrap](http://getbootstrap.com/).

The CSS looks like this:
```
* {
    margin: 0;
}

html,
body {
     height: 100%;
}

.container,
.container-fluid {
    min-height: 100%;
    height: auto !important;
    height: 100%;
    margin: 0 auto -4em;
}

footer,
.footer {
    height: 4em;
}
```