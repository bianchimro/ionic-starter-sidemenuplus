# ionic-starter-sidemenuplus

This is an addon starter template for the [Ionic Framework](http://ionicframework.com/).

This is a revamped [ionic-starter-sidemenu](https://github.com/driftyco/ionic-starter-sidemenu) with the following:

* Different files layout (controllers and services in separated folders)
* Config splitted in modules, saving you from huges `app.js` file:
    * network config
    * states-config
    * permissions-config 
    * constants config
* [angular-permission](https://github.com/Narzerus/angular-permission)
* [restangular](https://github.com/mgonto/restangular)
* [angular-http-auth](https://github.com/witoldsz/angular-http-auth)
* Example templates with more views
* Example login/logout workflow with protected account page and example redirect
* Example rest consumer service based on restangular

We use this template at [INMAGIK](http://www.inmagik.com) for ionic projects, in particular
for integration with [django](https://github.com/django/django) and [djangorestframework](https://github.com/tomchristie/django-rest-framework)

## How to use this template

*This template does not work on its own*. It is missing the Ionic library, and AngularJS.

To use this, either create a new ionic project using the ionic node.js utility, or copy and paste this into an existing Cordova project and download a release of Ionic separately.

### With the Ionic tool:

Take the repo url, and that is the name of the template to be used when using the `ionic start` command below:

```bash
$ sudo npm install -g ionic cordova
$ ionic start myApp https://github.com/inmagik/ionic-starter-sidemenuplus.git
```

Then, to run it, cd into `myApp` and run:

```bash
$ ionic platform add ios
$ ionic build ios
$ ionic emulate ios
```

Substitute ios for android if not on a Mac, but if you can, the ios development toolchain is a lot easier to work with until you need to do anything custom to Android.

## Demo
TBW

## Credits

Made with love @ [INMAGIK](http://www.inmagik.com)



