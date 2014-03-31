# YO

## Installing yo and some generators

First, you'll need to install yo and other required tools:

$ npm install -g yo

If you are using npm 1.2.10 or above, this will also automatically install grunt and bower for you. If you're on an older version of npm, you will need to install them manually:
// For npm versions < 1.2.10. 

$ npm install -g grunt-cli bower

If you have installed Grunt globally in the past, you will need to remove it first: npm uninstall -g grunt

## Example: Scaffolding an AngularJS app

As always, before using a new generator, you must install it from npm first:

$ npm install -g generator-angular

After that, create a new directory for your application, then run:

$ yo angular

## Scaffolding out your Angular app’s pieces

Some generators can also be used to scaffold further pieces of your application - we call these sub-generators.
In the AngularJS framework, for example, your application is made up of a number of pieces including controllers, directives and filters. You can actually scaffold out any of these pieces (and more) during your development workflow as shown below:

$ yo angular:controller myController
$ yo angular:directive myDirective
$ yo angular:filter myFilter
$ yo angular:service myService

Each framework generator has further documentation available noting what sub-generators it supports.


# Bower

Bower is a package manager for the web which allows you to easily manage dependencies for your projects. This includes assets such as JavaScript, images and CSS. It is maintained by Twitter and the open-source community.
Managing packages using Bower can be done using the following commands:

//# Search for a dependency in the Bower registry.
$ bower search <dep>

//# Install one or more dependencies.
$ bower install <dep>..<depN>

//# List out the dependencies you have installed for a project.
$ bower list

//# Update a dependency to the latest version available.
$ bower update <dep>


# GRUNT

Grunt is a task-based command-line tool for JavaScript projects. It can be used to build projects, but also exposes several commands which you will want to use in your workflow. Many of these commands utilize Grunt tasks under the hood which are maintained by the Yeoman team.
Grunt commands

//# Preview an app you have generated (with Livereload).

$ grunt serve

//# Run the unit tests for an app.

$ grunt test

//# Build an optimized, production-ready version of your app.

$ grunt



TODO:
	passport.js -- passportjs.org

