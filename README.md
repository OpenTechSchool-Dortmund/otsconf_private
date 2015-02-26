# [otsconf](http://otsconf.com)

[![Build Status](https://travis-ci.org/OpenTechSchool-Dortmund/otsconf_private.svg?branch=master)](https://travis-ci.org/OpenTechSchool-Dortmund/otsconf_private)

> otsconf is a static single page website. It is generated with grunt, written in jade, less and js and uses jQuery and Bootstrap.

## Dependencies

Run `npm i` to install necessary devDependencies (mostly grunt-plugins) and required libraries.

## Build

Run `npm start` to generate a production version of the site and to view it on a local server.

## Development

Note: For development it is necessary to globally install the grunt-cli `npm i -g grunt-cli`

Run `grunt serve` for a development server with livereload. Be aware that optimisations like uncss, or minifiers won't be applied in this mode.

## Deployment

Pushing changes to master automatically deploys them within a few moments.
