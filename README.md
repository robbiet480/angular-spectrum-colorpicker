Angular Spectrum Colorpicker
============================

[![Build Status](https://magnum.travis-ci.com/Jimdo/angular-spectrum-colorpicker.png?token=ZtVcRNmVRxsSKaA711h9)](https://magnum.travis-ci.com/Jimdo/angular-spectrum-colorpicker)

Angularified [spectrum colorpicker](http://bgrins.github.io/spectrum/)

This module bases on the [spectrum colorpicker](http://bgrins.github.io/spectrum/)
and can be embedded in any angular project via dependency injection:

	var myApp = angular.module('myApp', ['angularSpectrumColorpicker']);

To us it, put the Angular Spectrum Colorpicker directive in your html code and bind it to your project scope:

	<spectrum-colorpicker ng-model="someModel"></spectrum-colorpicker>


Initialize
----------

	bower install
	npm install


Start demo & test environment
-----------------------------

	./node_modules/protractor/bin/webdriver-manager update --standalone
	./node_modules/protractor/bin/webdriver-manager start
	node-dev scripts/web-server.js
	grunt


Play around in demo
-------------------

[http://localhost:8000/demo/index.html](http://localhost:8000/demo/index.html)



Grunt Tasks
-----------

(need running system:
  ./node_modules/protractor/bin/webdriver-manager start
  node-dev scripts/web-server.js
)

 * `grunt`: Execute tests and build dist
 * `grunt test`: Just test
 * `grunt watch:start`: Watch source and test files and run karma on change
 * `grunt build`: Just build
 * `grunt test:e2e`: Just test end to end
 * `grunt dist`: Test, build, bump patch version, commit, add version tag and push


LICENSE
-------

> The MIT License
>
> Copyright (c) 2014 Jimdo GmbH http://jimdo.com
>
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in
> all copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
> THE SOFTWARE.
