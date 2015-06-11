bootstrap-horizon [![bower package](https://badge.fury.io/bo/bootstrap-horizon.svg)](http://badge.fury.io/bo/bootstrap-horizon) [![npm version](https://badge.fury.io/js/bootstrap-horizon.svg)](http://badge.fury.io/js/bootstrap-horizon)
=================
Boostrap 3 rows with inline, horizontally scrolling columns. Inspired by [Ravimallya @ StackOverflow](http://stackoverflow.com/questions/20332830/bootstrap-3-horizontal-scrollable-row-website-design/20335239#20335239)

Example
-------

This `.well` fills the viewport and has a `.row.row-horizon` inside with a bunch of `.col-*-6`.

![Overflowing well](https://raw.githubusercontent.com/FluidApps/bootstrap-horizon/master/screenshots/bootstrap-horizon.gif)

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
<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.1/css/bootstrap.min.css">
<link rel="stylesheet" href="/bower_components/bootstrap-horizon/bootstrap-horizon.css">
```

Add the `.row-horizon` class to `.rows` that require horizontal scrolling. In order to improve the UX, bootstrap-horizon overrides bootstrap's `.col-*-*` classes to make the baseline width 90% instead of 100% which allows for a small portion of the last column to be displayed.

```
<div class="row row-horizon">
  <div class="col-xs-6 col-sm-4 col-md-3 col-lg-2">
    ...
  </div>
</div>
```

License
-------

**MIT**
