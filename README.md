An easy way to display forms with Zend Framework + Bootstrap 3
============================================================

This is designed as an easy drop-in replacement for the normal Zend Forms to
work together with Twitter Bootstrap (http://twitter.github.com/bootstrap).

Getting started
---------------

This library has decorators for basic and horizontal twitter forms (http://getbootstrap.com/css/#forms). For properly render Zend_Form_Element_MultiChocie and Zend_Form_Element_Radio plase add following styles:

    .form-group-multi .checkbox,
    .form-group-multi .radio {
        padding-left: 20px;
    }

Instaliation
------------

* Add this to your composer.json:

    {
        "minimum-stability": "dev",
        "require": {
            "lciolecki/zf-debug" : "dev-master"
        }
    }

Usage
-----

* Instead of extending from Zend\_Form extend from Twitter\_Form

We included a small example application that shows you what you can do with
this.
The interesting parts for our "library" are in /library/Twitter.

Have fun!

If you encounter any errors, please report them here on Github. Thanks!

License
-------

Copyright (c) 2012-2013 Sebastian Hoitz, komola GmbH <hoitz@komola.de>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.