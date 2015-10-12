# Bootstrap 3 with on-demand RTL support 

---

This is a fork of [morteza's bootstrap-rtl](https://github.com/morteza/bootstrap-rtl/fork) theme. Contrary to the original, it doesn't override the default LTR direction and enforce RTL direction by default. It relies on `<html dir="ltr|rtl">` attribute and enables RTL direction only when `dir="rtl"` is set.


Bootstrap RTL provides simple yet robust right-to-left capability for Bootstrap 3, by employing new theming feature of it. Simply put its CSS after bootstrap's original CSS, to the pages designed by Bootstrap 3. It works just like an extension on top of the original Bootstrap:

```html
<!-- Original Bootstrap 3.x -->
<link rel="stylesheet" href="bootstrap.css">

<!-- Bootstrap RTL Theme -->
<link rel="stylesheet" href="bootstrap-rtl.css">
```

## Quick start

It's just like Bootstrap 3, nothing special. You can install it via bower:

* Run `bower install bootstrap-rtl-ondemand` and latest version will be installed under *bower_components/bootstrap-rtl/* directory.

In addition to bootstrap distribution, LESS codes for RTL theme and compiled CSS (`bootstrap-rtl.css`) are provided, as well as minified CSS (`bootstrap-rtl.min.css`). Check `dist/` directory for all the codes you need.

#### Auto Flip (`.flip`)
To automatically flip placements from right to left and vice versa (in bilingual pages), use `.flip` alongside `.pull-right` and `.pull-left`. This is a custom class and is not available in the original Bootstrap 3.

## Building CSS and JavaScript

Bootstrap RTL uses [Grunt](http://gruntjs.com/) for working with the framework. Follow these simple steps to prepare and compile:

1. Run `npm install` to download and prepare dependencies.
2. Run `grunt`, and check `dist/` directory for outputs.

## Author

**Morteza Ansarinia**

+ [https://github.com/morteza](https://github.com/morteza)

**Michał Jastrzębowski**
 
+ [https://github.com/mjastrzebowski](https://github.com/mjastrzebowski)




