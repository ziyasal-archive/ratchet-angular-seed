# ratchet-angular-seed — the seed for Ratchet & AngularJS apps

This project is an application skeleton for a typical **Ratchet-AngularJS** web app.
You can use it to quickly bootstrap your ratchet-angular webapp projects and dev environment for these
projects.

The seed contains a sample Ratchet-AngularJS application and is preconfigured to install the Ratchet and Angular
framework and a bunch of development and testing tools for instant web development gratification.

The seed app doesn't do much, just shows how to wire two controllers and views together.


## Getting Started

To get you started you can simply clone the ratchet-angular-seed repository and install the dependencies:

### Clone angular-seed

Clone the angular-seed repository using [git][git]:

```
git clone https://github.com/ziyasal/ratchet-angular-seed.git
cd ratchet-angular-seed
```

### Install Dependencies

We have two kinds of dependencies in this project: tools and angular framework code.  The tools help
us manage and test the application.

* We get the tools we depend upon via `npm`, the [node package manager][npm].
* We get the angular code via `bower`, a [client-side code package manager][bower].

We have preconfigured `npm` to automatically run `bower` so we can simply do:

```
npm install
```

Behind the scenes this will also call `bower install`.  You should find that you have two new
folders in your project.

* `node_modules` - contains the npm packages for the tools we need
* `bower_components` - contains the angular framework files

### Run the Application

We have preconfigured the project with a simple development web server.  The simplest way to start
this server is:

```
npm start
```

Now browse to the app at `http://localhost:8000/app/index.html`.