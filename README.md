angularjs-jasmine-karma
=======================

TDD and BDD with AngularJS

1. Start ionic project
ionic start angularjs-jasmine-karam tabs


2. Prerequisites:

As with most things lately, you’ll want to make sure you have node.js and npm installed.  If you don’t already have node.js installed, you can download it at http://nodejs.org.

From a command-line, you want to install Karma and PhantomJS using npm:

$ npm install -g karma-cli
$ npm install -g phantomjs
$ npm install karma-jasmine –save-dev
$ npm install karma-phantomjs-launcher –save-dev




* Install Bower

$ npm install -g bower bower requires Node and npm and Git.

Configure Karma for the project:

Now that the project is setup, lets configure Karma to work with it. Karma requires a configuration file in order to run, but fortunately includes an automatic initialization process that will create one for you:

$ karma init karma.conf.js

Running the tests and doing some TDD:

Assuming everything has gone according to plan so far, we should be able to run Karma and see the results of the first tests:

$ karma start karma.conf.js

 
2. Start using ionic:
 * cd into your project: $ cd angularjs-jasmine-karma
 * Setup this project to use Sass: ionic setup sass

 * Develop in the browser with live reload: ionic serve

 * Add a platform (ios or Android): ionic platform add ios [android]
   Note: iOS development requires OS X currently
   See the Android Platform Guide for full Android installation instructions:
   https://cordova.apache.org/docs/en/edge/guide_platforms_android_index.md.html

 * Build your app: ionic build <PLATFORM>

 * Simulate your app: ionic emulate <PLATFORM>

 * Run your app on a device: ionic run <PLATFORM>

 * Package an app using Ionic package service: ionic package <MODE> <PLATFORM>

For more help use ionic --help or visit the Ionic docs: http://ionicframework.com/docs
3. Init karam configuration
Karma configuration
To run new tests with Karma, you need to have a Karma configuration file (learn more about it).

To generate new configuration file, for example, karma.conf.js in the project directory run in built-in Terminal:

karma init karma.conf.js
Follow the suggested steps in the configuration dialog.



