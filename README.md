tiltEffect
==========
[![The MIT License](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](#license)&nbsp;
[![Live Demo](http://img.shields.io/badge/live-DEMO-ff9900.svg?style=flat)](https://salgnt.github.io/tiltEffect/demo)

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
_tiltEffect_ was created by [_Salvatore Gentile_](https://twitter.com/_sgentile) and is released under **The MIT License (MIT)**.

    The MIT License (MIT)

    Copyright (c) 2013 Salvatore Gentile

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
