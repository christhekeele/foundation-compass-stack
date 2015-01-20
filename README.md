# Foundation Sandbox

This is a sandbox for your next web project using Foundation. It also comes with Grunt, Compass, and Assemble.

## Usage

This project contains every single Foundation component on a single page, to make it easy to tweak everything in one go until you have the customized Foundation installation perfect for your next endeavor.

Once you like what you have, you can place your customizations into your app, or use the Grunt, Compass, and Assemble stack provided as the seed of your project.

## Requirements

You'll need to have the following items installed before continuing.

* [Ruby](http://ruby-lang.org/): If you are on OSX or Linux, you should already have Ruby installed. If not, check their website for installation options.
* [Node.js](http://nodejs.org): Use the installer provided on the NodeJS website.
* [Grunt](http://gruntjs.com/): Run `sudo npm install -g grunt-cli`
* [Bower](http://bower.io): Run `sudo npm install -g bower`
* [Sass](http://sass-lang.com) & [Compass](http://compass-style.org): Run `gem update --system && gem install compass`


## Quickstart

Fork or clone this repository:

`git clone git@github.com:christhekeele/foundation-sandbox.git`

Navigate into the directory:

`cd foundation-sandbox`

Install all the dependincies:

`npm install && bower install`

While you're working on your project, run:

`grunt`

This will assemble all the pages and compile the Sass. You're set!

## Directory Structure

* `src`: This is the directory you'll work in.
* `src/assets`: All assets (scss, images, fonts, js, etc) go here.
* `src/assets/scss/_settings.scss`: Foundation configuration settings go in here.
* `src/assets/scss/sandbox.scss`: Styles that make the sandbox look good go here.
* `src/assets/scss/app.scss`: Application styles go here. These are the ones you'll want to take home with you.
* `dist`: Static pages are assembled here. This is where you should view the site in your browser. **Don't edit these files directly. They will be overwritten!**
* `pages`: This is where your Assemble HTML templates go.
* `pages/index.html`: This is the landing page for your site, already kitted out with every Foundation component.
* `partials`: This is where reusable templates that will be embedded in others go.
* `partials/components`: This is where each Foundation component lives. Remove component partials from your `index.html` if you don't intend on using them to reduce clutter.

