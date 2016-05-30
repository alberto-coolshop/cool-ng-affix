Angular version of Bootstrap Affix.js
=====================================

Pure AngularJS component replicating [Twitter Bootstrap's Affix](http://twitter.github.io/bootstrap/javascript.html#affix) component behavior.
The affix behavior enables dynamic pinning of a DOM element during page scrolling when specific conditions are met.

## Getting Started

+ Install with bower, `bower install cool-ng-affix --save`

In your web page:

```html
<script src="bower_components/angular/angular.js"></script>
<script src="bower_components/cool-ng-affix/dist/cool-ng-affix.min.js"></script>
<script src="scripts/app.js"></script>
```

In your app.js:

```js
angular.module('myApp', ['cool.bootstrap.affix'])
```

## Documentation

+ To easily add affix behavior to any element, just add `cool-affix` to the element you want to spy on. Then use offsets to define when to toggle the pinning of an element on and off.

+ Check [Twitter Bootstrap's Affix](http://twitter.github.io/bootstrap/javascript.html#affix) docs.

## Examples

```html
<div class="iphone" cool-affix data-offset-top="200" data-offset-bottom="300">
  <div class="iphone-content">
  </div>
</div>