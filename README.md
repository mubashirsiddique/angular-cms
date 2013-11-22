# Angular CMS
This is a lightweight CMS built with Angular.js, Twitter Bootstrap and Node.js.

The purpose of this CMS is for many reasons, the most important reason is this is the CMS that the Learning Yeoman book is going to revolve around.
The book is going to be published during the 2nd quarter of the new year by Packt Publishing. Each piece has to do with a corresponding chapter in the book that I am writing.



## Features

_(Coming soon)_


### Must Have
* user management & user roles
* action and view permissions
* content versioning and audit
* some form of workflow and notifications
* i18n support on literals and object versions
* normalized database schema design
* some form of content import-export
* assets management and thumbnail generation for uploads
* Valid XHTML (compressed with GZIP)
* Rich text editing (e.g FCKeditor) which generates accessible markup
* Valid and minified CSS and javascript (e.g using YUI)
* automatically generated sitemaps.org document
* integration with Google Analytics
* automatic RSS feeds
* open search support
* print css and/or print versions of content
* SEO consideration for duplicate content (e.g use of canonical tag)




## Getting Started

Download the [production version][min] or the [development version][max].

_(Coming soon)_

## Documentation
_(Coming soon)_



## Examples
_(Coming soon)_



# Contributing

## Important notes
Please don't edit files in the `dist` subdirectory as they are generated via Grunt. You'll find source code in the `src` subdirectory!

### Code style
Regarding code style like indentation and whitespace, **follow the conventions you see used in the source already.**

### PhantomJS
While Grunt can run the included unit tests via [PhantomJS](http://phantomjs.org/), this shouldn't be considered a substitute for the real thing. Please be sure to test the `test/*.html` unit test file(s) in _actual_ browsers.

## Modifying the code
First, ensure that you have the latest [Node.js](http://nodejs.org/) and [npm](http://npmjs.org/) installed.

Test that Grunt's CLI and Bower are installed by running `grunt --version` and `bower --version`.  If the commands aren't found, run `npm install -g grunt-cli bower`.  For more information about installing the tools, see the [getting started with Grunt guide](http://gruntjs.com/getting-started) or [bower.io](http://bower.io/) respectively.

1. Fork and clone the repo.
1. Run `npm install` to install all build dependencies (including Grunt).
1. Run `bower install` to install the front-end dependencies.
1. Run `grunt` to grunt this project.

Assuming that you don't see any red, you're ready to go. Just be sure to run `grunt` after making any changes, to ensure that nothing is broken.

## Submitting pull requests

1. Create a new branch, please don't work in your `master` branch directly.
1. Add failing tests for the change you want to make. Run `grunt` to see the tests fail.
1. Fix stuff.
1. Run `grunt` to see if the tests pass. Repeat steps 2-4 until done.
1. Open `test/*.html` unit test file(s) in actual browser to ensure tests pass everywhere.
1. Update the documentation to reflect any changes.
1. Push to your fork and submit a pull request.
 