skeleton-Sass
=============

Modulated Sass port of [Skeleton](www.getskeleton.com)

## Getting Started
Assuming you already have Ruby and Rubygems installed...

    $ git clone git@github.com:rpearce/skeleton-Sass.git
    $ cd skeleton-Sass

## Lay of the Land
All of the Sass is located within

    stylesheets/sass

### Variables
All color variables are in one location for editing and can be found in

    stylesheets/sass/general/_variables.sass

## Working with Sass
I recommend using [CodeKit](http://incident57.com/codekit/) with Sass, CoffeeScript, JS, and really even any type of front-end dev.
However, If you prefer compiling the Sass from the command line, you can do this:

    $ gem install sass
    $ sass --watch stylesheets/sass/:stylesheets/css --style compressed

## To-Do
Abstract and refactor those bloody button classes.
