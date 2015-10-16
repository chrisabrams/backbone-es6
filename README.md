![Backbone-ES6](http://i.imgur.com/vyFIbER.png)

Backbone supplies structure to JavaScript-heavy applications by providing models with key-value binding and custom events, collections with a rich API of enumerable functions, views with declarative event handling, and connects it all to your existing application over a RESTful JSON interface.

Backbone-ES6 is a fork of Backbone 1.2.3 (https://github.com/jashkenas/backbone) converting and modularizing it into idiomatic ES6. The impetus for this fork is to experiment with modernizing and making Backbone easier to modify in a granular fashion. In particular the Parse JS SDK (http://www.parse.com) previously also was a fork of Backbone, but with the 1.6+ SDK release the Backbone API was unceremoniously removed. Backbone-ES6 provides the base for Backbone-Parse-ES6 (https://github.com/typhonjs/backbone-parse-es6) which provides a solution for Backbone dependent Parse users. 

This repository contains several pre-packed downloads in the `dist/` directory. There are AMD, CJS, and Global distributions. The "global-inclusive" bundle includes the latest jQuery and Underscore libraries.

API documentation can be found in the `docs/` directory and online here:

For original Backbone Docs, License, Tests, pre-packed downloads, and everything else, really, see:
http://backbonejs.org

To suggest a feature or report a bug:
https://github.com/typhonjs/backbone-es6/issues

Many thanks to DocumentCloud & all Backbone contributors:
https://github.com/jashkenas/backbone/graphs/contributors

Backbone (c) 2010-2015 Jeremy Ashkenas, DocumentCloud and Investigative Reporters & Editors

Backbone-ES6 (c) 2015 Michael Leahy, TyphonRT, Inc. 

Backbone / Backbone-ES6 may be freely distributed under the MIT license.