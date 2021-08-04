Cordova Apk Updater Demo App  &middot; [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kolbasa/cordova-plugin-apkupdater/blob/master/LICENSE) [![npm](https://img.shields.io/npm/v/cordova-plugin-apkupdater.svg)](https://www.npmjs.com/package/cordova-plugin-apkupdater) [![npm](https://img.shields.io/npm/dm/cordova-plugin-apkupdater.svg)](https://www.npmjs.com/package/cordova-plugin-apkupdater)
---------------------------------------------------------------------------

![Installation dialog](https://raw.githubusercontent.com/wiki/kolbasa/cordova-plugin-apkupdater-demo/Images/Installation.png)

### Overview

This demo app demonstrates the functions of the **[Apk Updater Plugin](https://github.com/kolbasa/cordova-plugin-apkupdater)** for Cordova. 

:point_right: **[DOWNLOAD](https://github.com/kolbasa/cordova-plugin-apkupdater-demo/raw/master/Demo.apk)** :point_left:

* This is how the demo looks like: **[short video showcase](https://raw.githubusercontent.com/wiki/kolbasa/cordova-plugin-apkupdater-demo/Videos/Download.gif)**.
* **[In this folder](https://github.com/kolbasa/cordova-plugin-apkupdater-demo/tree/master/update)** you will find the update file. As you can see I update the app directly from this github repository.
* All function calls of the demo app can be found **[here](https://github.com/kolbasa/cordova-plugin-apkupdater-demo.src/blob/main/www/js/demo.js)**.
* In this example I use an encrypted zip file update with the password: `aDzEsCceP3BPO5jy`.

### Instructions

* Install the app `Demo.apk`.
* The installed app starts with the Version `1.0.0`. The goal is to then update the app to version `1.0.1`.
* The fastest way to install the apk update is to press the following buttons in succession: `download()` &rarr; `install()`.

### Notes

* Some functions have been color-coded to indicate that they belong together.
* The method `http.get()` is the only one that is not from the plugin. This is offered only as an example of how to do versioning ([explanation](https://github.com/kolbasa/cordova-plugin-apkupdater#update-versioning)).

### Build the demo yourself

* You can find everything you need **[here](https://github.com/kolbasa/cordova-plugin-apkupdater-demo.src)**.