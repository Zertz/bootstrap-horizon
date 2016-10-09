bootstrap-horizon [![bower package](https://badge.fury.io/bo/bootstrap-horizon.svg)](http://badge.fury.io/bo/bootstrap-horizon) [![npm version](https://badge.fury.io/js/bootstrap-horizon.svg)](http://badge.fury.io/js/bootstrap-horizon)
=================
Boostrap 3 rows with inline, horizontally scrolling columns. Inspired by [Ravimallya @ StackOverflow](http://stackoverflow.com/questions/20332830/bootstrap-3-horizontal-scrollable-row-website-design/20335239#20335239)

[Live example](https://jsfiddle.net/azu9mf8d/3/)

Installation
------------

### Bower

```
bower install bootstrap-horizon
```

### npm

```
npm install bootstrap-horizon
```

Usage
-----

Include bootstrap-horizon.css *after* bootstrap.css

```
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="/bootstrap-horizon/dist/bootstrap-horizon.min.css">
```

Add the `.row-horizon` class to rows that require horizontal scrolling. In order to improve the UX, bootstrap-horizon overrides bootstrap's `.col-*-*` classes to make the baseline width 90% instead of 100% which allows for a small portion of the last column to be displayed.

```html
<div class="row row-horizon">
  <div class="col-xs-6">
    <p>This content is very, very, very, very, very, very, very wide!</p>
  </div>
  <div class="col-xs-6">
    <p>This content is very, very, very, very, very, very, very wide!</p>
  </div>
  <div class="col-xs-6">
    <p>This content is very, very, very, very, very, very, very wide!</p>
  </div>
</div>
```

License
-------

**MIT**
