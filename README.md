tiltEffect
==========
A simple jQuery plugin to add a tilt effect to an HTML element, just like tiles in Windows 8 and Windows Phone.


How to
------
Include `tiltEffect.css` in `<head>`:
```html
<link rel="stylesheet" href="path/to/tiltEffect/tiltEffect.css">
```

Include *jQuery* and `tiltEffect.js` somewhere in the page and target your elements with `tiltEffect()`:
```html
<script src="path/to/jquery.min.js"></script>
<script src="path/to/tiltEffect/tiltEffect.js"></script>
<script>
    $(document).ready(function(){
        $('.tile').tiltEffect();
    });
</script>
```


Supported browser
-----------------
Works only on modern browser that support *CSS3 Transforms*.


License
-------
_tiltEffect_ was created by [_Salvatore Gentile_](https://twitter.com/SalvoGentile) and is released under **The MIT License (MIT)**.
