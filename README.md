# `ember-cli-eyeglass` [![Build Status](https://travis-ci.org/sass-eyeglass/ember-cli-eyeglass.svg?branch=master)](https://travis-ci.org/sass-eyeglass/ember-cli-eyeglass)<Paste>

This Ember CLI Addon makes it trivial to compile your sass files with
eyeglass support via node-sass.

## Installation

`npm install --save-dev ember-cli-eyeglass`

Then rename all your `.css` files so they have the `.scss` extension.

## Configuration

In your application's config/environment.js the key `"eyeglass"` can be
set to an options object that will be passed to broccoli-eyeglass. For
details on the options available, please read the [broccoli-eyeglass
options documentation](https://github.com/sass-eyeglass/broccoli-eyeglass#options).

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).
