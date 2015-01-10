# edx-theme

[![Build Status](https://travis-ci.org/IONISx/edx-theme.svg?branch=master)](https://travis-ci.org/IONISx/edx-theme)

> Open edX responsive theme using [Bootstrap](http://getbootstrap.com/).

![Screenshot](https://raw.githubusercontent.com/IONISx/edx-theme/docs/images/responsive.png)

## Getting started

First, install `grunt-cli` and `bower` globally (or not) in order to have the required build tools.

    npm install -g grunt-cli bower

Then fetch the local depedencies.

    npm install
    bower install

Finally, run `grunt` to build the theme’s source files.
`grunt` will watch for changes and re-build the output automatically.

Run `grunt build` for a one time build.  
Run `grunt test` to lint your source files as well.

## Installation

Create /edx/app/edx_ansible/server-vars.yml

Update file permissions
```
sudo chown edx-ansible:edx-ansible /edx/app/edx_ansible/server-vars.yml
```
Re-provision:
```
sudo /edx/bin/update edx-platform release
```
## License

[AGPL](http://en.wikipedia.org/wiki/Affero_General_Public_License)
