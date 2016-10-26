angular-image-compress
=================

######This Angular directive compresses jpeg or png files using angularjs on client side. It uses using HTML5 Canvas &amp; File API. The compression algorithm is based off of the ng-image-compress and J-I-C project on github. 

-----------

Demo
-------------
[http://oukan.github.io/angular-image-compress/](http://oukan.github.io/angular-image-compress/)

Installation
-------------
 - Bower -  `bower install angular-image-compress`


Usage
-------

Include `angular.js` and `angular-image-compress.js` in your application and add `ngImageCompress` as dependency to your main module.

```
angular.module('myApp', ['ngImageCompress']);
```

```html
<input id="inputImage" type="file" accept="image/*" image="image1" resize-max-height="800" resize-max-width="800" resize-quality="0.7" resize-type="image/jpg" ng-image-compress />
```

```html
<img ng-src="{{image1.compressed.dataURL}}" />
```

**Adjustable: resize-max-height, resize-max-width, resize-quality, resize-type

Angular support
-------
support 1.x version, no test in Angular 2.


Browser support
-------
IE9+, Google Chrome, Firefox, Edge, Safari... 

[List](http://caniuse.com/#search=canvas)

License
-------

This code is released under the [MIT License
license](http://opensource.org/licenses/MIT)

Copyright (c) 2012 Bruno Barbieri

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

Enjoy!
