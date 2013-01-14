skeleton-Sass
=============

Sass port of the great Skeleton (www.getskeleton.com)

## Lay of the Land
This port is heavily modulated. All of the Sass is located within

    stylesheets/sass

## Variables
All color variables are in one location for editing and can be found in

    stylesheets/sass/general/_variables.sass

## Working with Sass
I recommend using [CodeKit](http://incident57.com/codekit/) with Sass, CoffeeScript, JS, and really even any type of front-end dev.
However, If you prefer compiling the Sass from the command line, you can do this:

    $ sass --watch stylesheets/sass/:stylesheets/css --style compressed

## To-Do
Abstract and refactor those bloody button classes.
