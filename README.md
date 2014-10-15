# [Bootstrap](http://getbootstrap.com)


##Setup Details


1. bootstrap.less imports features of other .less file example carousel.less
   _/components/less/bootstrap.less compiles & outputs to  _/css_bootstrap.css

2. custom.less will be used to implement overiding styles
   _/components/less/custom.less compiles & outputs to  _/css_custom.css

3. bootstrap.js combines other jquery along with other javascript plugins for bootstrap example(carousel.js)
   _/components/js/bootstrap.js compiles & outputs to  _/js/bootstrap.js

4. custom.js will be used to implement custom scripts
   le_/components/js/custom.js compiles & outputs to  _/js/custom.js



Folder Structure


```

bootstrap3/
├── images/
├── _/
│   ├── /components
│   │    ├── js/
│   │    │     ├── affix.js
│   │    │     ├── alert.js
│   │    │     ├── bootstrap.js
│   │    │     ├── button.js
│   │    │     ├── carousel.js
│   │    │     ├── collapse.js
│   │    │     ├── custom.js
│   │    │     ├── dropdown.js
│   │    │     ├── jquery.js
│   │    │     ├── modal.js
│   │    │     ├── popover.js
│   │    │     ├── scrollspy.js
│   │    │     ├── tab.js
│   │    │     ├── tooltip.js
│   │    │     ├── transition.js
│   │    ├── less/
│   │    │     ├── alerts.less
│   │    │     ├── badges.less
│   │    │     ├── bootstrap.less
│   │    │     ├── breadcrumbs.less
│   │    │     ├── button-groups.less
│   │    │     ├── button.less
│   │    │     ├── carousel.less
│   │    │     ├── close.less
│   │    │     ├── code.less
│   │    │     ├── component-animations.less
│   │    │     ├── custom.less
│   │    │     ├── dropdowns.less
│   │    │     ├── grid.less
│   │    │     ├── input-groups.less
│   │    │     ├── jumbotron.less
│   │    │     ├── labels.less
│   │    │     ├── list-group.less
│   │    │     ├── media.less
│   │    │     ├── mixins.less
│   │    │     ├── modals.less
│   │    │     ├── navbar.less
│   │    │     ├── navs.less
│   │    │     ├── normalize.less
│   │    │     ├── pager.less
│   │    │     ├── pagination.less
│   │    │     ├── panels.less
│   │    │     ├── popovers.less
│   │    │     ├── print.less
│   │    │     ├── progress-bars.less
│   │    │     ├── responsive-utilities.less
│   │    │     ├── scaffolding.less
│   │    │     ├── tables.less
│   │    │     ├── theme.less
│   │    │     ├── thumbnail.less
│   │    │     ├── tooltip.less
│   │    │     ├── type.less
│   │    │     ├── type.less
│   │    │     ├── utilities.less
│   │    │     ├── variables.less
│   │    │     ├── wells.less
│   ├── css/
│   │    ├── bootstrap.css
│   │    ├── custom.css
│   ├── js/
│   │    ├── bootstrap.js
│   │    ├── custom.js
│   ├── fonts/
│   │    ├── glyphicons-halflings-regular.eot
│   │    ├── glyphicons-halflings-regular.svg
│   │    ├── glyphicons-halflings-regular.ttf
│   │    ├── glyphicons-halflings-regular.woff

```

