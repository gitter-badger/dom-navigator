DOM Navigator
=============

> Library that allow keyboard navigation through DOM elements (←↑→↓).

Installation
------------

Using bower:

```
bower install domnavigator --save
```

Using NPM:

```
npm install domnavigator --save
```

Usage
=====

Vanilla JavaScript:

```js
var el = document.querySelector('#grid');
var nav = new DomNavigator(el);
```

If jQuery is included you can use the library as a jQuery plugin:

```js
var el = $('#grid');
el.domNavigator();
```

