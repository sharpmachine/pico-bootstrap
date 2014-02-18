Pico // Bootstrap 3
===================

Everything you need to start a project using the Pico CMS and Bootstrap 3

[*Pico*](http://pico.dev7studios.com) is a studipidly simple &amp; blazing fast, flat file CMS.  [*Bootstrap*](http://getbootstrap.com) is he most popular front-end framework for developing responsive, mobile first projects on the web.  Together they do great things, quickly.  Just clone or download the zip and your off!

We've also included Modernizr and Selectivizr for production sites, and Holder and #grid.js for development.

[*Modernizr*](http://modernizr.com/) is a JavaScript library that detects HTML5 and CSS3 features in the user’s browser.

[*Selectivizr*](http://selectivizr.com/) was written to make using CSS3 selectors in Internet Explorer completely seamless.

[*Holder*](http://imsky.github.io/holder/) renders image placeholders entirely on the client side.  It works both online and offline, and offers a chainable API to style and create placeholders with ease.

[*#Grid*](https://github.com/dotjay/hashgrid) is a little tool that inserts a layout grid in web pages, allows you to hold it in place, and toggle between displaying it in the foreground or background.
======================================================

# The perfect workflow

This magical combination of Pico and Bootstrap has been put together for developers that enjoy working with Bootstrap, but like to keep it as lean as possible.  The problem with the default Bootstrap download is that the bootstrap.css and bootstrap.js will include the components and plugins that your project may not end up using, leaving unnecessary bloat.

## Javascripts

That's why we've chose to not include the compiled bootrap.js file.  Instead you will notice that in the footer we have linked to all the BS3 plugins.  The idea is that when your project is ready for production, you can remove the plugins you didn't use, and then import and minify the needed plugins into a single JS file.  We like to use Codekit for things like this.  That's why we also included.

###plugins.js

###scripts.js

during development your footer will look like this:

When ready for production, you'll want your footer to look like this:

## CSS/LESS

Just like with the javascript, the precompiled bootstrap.css that comes with the default download of BS3 will undoubtly end up with loads of code that your production site will not use.  

For this, we have added an import to the bootstrap.less for theme.less and style.less on lines 48 and 49.  We have bootstrap.less compile into bootstrap.css in the CSS directory.  We use theme.less for all the bootrap component overrides, and style.less for the project custom styling.  When a project is ready for production, we simply comment out all the components we didn't use and recompile bootrap.less (also minify).

## Holder &amp; #Grid

Holder and #grid and only there to help with development.  Once your site is ready for product, you can remove the footer links to these files.

# This README.md is currently a work in progress


