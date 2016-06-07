app: This is where folders and files for models, components, routes, templates and styles are stored. The vast majority of our coding happens in this folder.

bower-components / bower.json: bower is a dependency management tool. It is used to manage front-end plugins and component dependencies (HTML, CSS, JavaScript, etc). All bower components are installed in the bower-components directory. If we open bower.json, we see the list of dependencies that are installed by Ember automatically. These include Ember, jQuery, Ember Data and QUnit (for testing). If we add additional front-end dependencies, like bootstrap, they will also be listed here and their files added to the bower-components directory.

config: Contains the environment.js file which lists environmental settings and configurations for our app. We'll look at this more closely later.

dist: When an app is built for deployment, the output files will reside here.

node_modules / package.json: This directory and file are from npm. npm is the package manager for Node.js. Ember is built with Node and uses a variety of Node.js modules for operation. The package.json file comes pre-loaded with a list of current packages Ember requires. Any Ember-CLI add-ons you install will also show up here. Packages listed in package.json are installed in the node_modules directory.

public: This directory contains assets such as images and fonts.

vendor: This directory is where any front-end dependencies NOT managed by bower reside.

tests / testem.json: Contains automated tests for our app. Ember CLI's test runner testem is also configured in testem.json.

tmp: Temporary files live here.

ember-cli-build.js: Behind the scenes, Ember CLI uses a tool called Broccoli to compile our code. This file contains settings for how Broccoli should build our app.

DS - Data store for Firebase data structure
