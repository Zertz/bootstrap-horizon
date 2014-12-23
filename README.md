bootstrap-horizon
=================
Boostrap 3 rows with horizontal overflow

Example
-------

This `.well` fills the viewport and has a `.row.row-horizon` inside with a bunch of `.col-*-6`.

![Overflowing well](https://raw.githubusercontent.com/FluidApps/bootstrap-horizon/master/screenshots/1.png)

Installation
------------

### Bower

```
To do
```

### Download

[Github](https://raw.githubusercontent.com/FluidApps/bootstrap-horizon/master/bootstrap-horizon.css)

Usage
-----

Include bootstrap-horizon.css *after* bootstrap.css

```
<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.1/css/bootstrap.min.css">
<link rel="stylesheet" href="/css/bootstrap-horizon.css">
```

Add the `.row-horizon` class to rows that require horizontal scrolling. In order to improve the UX, bootstrap-horizon overrides bootstrap's `.col-*-*` classes to make the baseline width 90% instead of 100% which allows a small portion of the last column to be displayed.

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
