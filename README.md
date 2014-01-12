dokku-bower-grunt-build
=================

This plugin will install Bower and pull in dependencies. It will then
install grunt-cli and run the 'build' task. Any Grunt specific node
modules other than grunt-cli should be specified in Gruntfile.js.

Install
=================

On your dokku server run:
```sh
cd /var/lib/dokku/plugins
git clone https://github.com/ezynda3/dokku-bower-grunt-build bower-grunt-build
```
