# Draggabilly-ps

A little fork from Draggabilly and [Sirgallifrey](https://github.com/sirgallifrey/draggabilly-ps/) that implements scale, mouse wheel scroll and auto-scrolling
Don't forget to check David DeSandro's awesome original Draggabilly

[draggabilly.desandro.com](http://draggabilly.desandro.com)

For draggabily documentation refer to:
[draggabilly.desandro.com](http://draggabilly.desandro.com)


## New available options:

``` js
var $draggable = $('.draggable').draggabilly({
  parentScroll: 'selector', // element, string or bool. Parent scrolling element, true is for parentNode.
  autoScroll: false, // bool, enable autoScroll. Only verticall autoscrolling ATM, open an issue if you need horizontal too.
  autoScrollThreshold: 30, // int. threshold from parentScroll borders to start autoscrolling
  scrollSpeed: 10 // int, autoScrolling speed
})
```

## New Methods

### Set and Get scale.

useful when inside and scaled element

``` js
// jQuery
$draggable.draggabilly('setScale', SCALE)
$draggable.draggabilly('getScale')
// vanilla JS
draggie.setScale(SCALE)
draggie.getScale()
```


Draggabilly-ps is released under the [MIT License](http://desandro.mit-license.org/). Have at it.