dokku-bower-gulp-build
=================

This plugin will install Bower and pull in dependencies. It will then
install Gulp and run the 'build' task. Any Gulp specific node
modules other than Gulp should be specified in gulpfile.js.

## Install

On your dokku server run:
```sh
cd /var/lib/dokku/plugins
git clone https://github.com/ezynda3/dokku-bower-gulp-build bower-gulp-build
```
