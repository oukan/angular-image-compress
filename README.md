angular-image-compress
=================

######This Angular directive compresses jpeg or png files using angularjs on client side. It uses using HTML5 Canvas &amp; File API. The compression algorithm is based off of the ng-image-compress and J-I-C project on github. 

-----------

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
<input id="inputImage" type="file" accept="image/*" image="image1" resize-max-height="800" resize-max-width="800" resize-quality="0.7" resize-type="image/jpg" ng-image-compress/>
```

**Adjustable: resize-max-height, resize-max-width, resize-quality, resize-type 


For demo, u can just clone this repo and then run index.html. thanks!!