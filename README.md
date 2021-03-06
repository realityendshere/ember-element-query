ember-element-query
===================

[![Travis](https://api.travis-ci.org/lolmaus/ember-element-query.svg?branch=gen-1)](https://travis-ci.org/lolmaus/ember-element-query)
[![npm](https://img.shields.io/npm/v/ember-element-query.svg?maxAge=2592000)](https://www.npmjs.com/package/ember-element-query)
[![Ember Observer Score](https://emberobserver.com/badges/ember-element-query.svg)](https://emberobserver.com/addons/ember-element-query)
![1.13+](https://embadge.io/v1/badge.svg?start=1.13.0)

This is an Ember addon that allows you to apply styles to elements
conditionally based on element's own width rather than viewport width.

This lets you implement your HTML elements as independent components capable
of responsive web design (RWD) transformations while staying decoupled from their parent context.


Documentation and Demo
----------------------

http://lolmaus.github.io/yuidork/#/lolmaus/ember-element-query/gen-1/modules/ember-element-query

Yuidork, the documentation website, heavily relies on `ember-element-query` for its advanced RWD.


PhantomJS Not Supported
-----------------------

`ember-element-query` is not compatible with PhantomJS. Use Chrome for testing.


IE11 Not Supported (Yet)
------------------------

IE11 support is currently missing, it is planned to be implemented, see [#2](https://github.com/lolmaus/ember-element-query/issues/2).



License
-------

This software is free to use under the MIT license. See the [LICENSE](https://github.com/lolmaus/ember-element-query/blob/gen-1/LICENSE.md) file for license text and copyright information.

Includes fragments of code borrowed from [runspired/flexi](https://github.com/runspired/flexi).
