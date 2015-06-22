# STRV-Project
This application was proposed as test project.


Features
========
* Get Today's weather details depending on your location.
* Get the weather forecast for the upcoming week with the possibility to see the details.
* Animated background depending the weather state and the location using Flickr api.

Installation
============
For Genymotion:
* Drag and drop the apk file into Genymotion emulator.

For other emulators:
* Copy the apk file to platform-tools in android-sdk linux folder.
* Open Terminal and navigate to platform-tools folder in android-sdk.
* Then Execute this command ./adb install FileName.apk
* If the operation is successful (the result is displayed on the screen), then you will find your file in the launcher of your emulator.

Usage
=====
* Usage is pretty simple using the navigation drawer on the left side of the screen to switch between the different features.

WeatherConfig.java
------------------
This is the main configuration file and there are some important constants: addresses to API endpoints, API keys to 3rd party services etc. Make sure that all constants are set up properly.

build.gradle
------------

This is the main build script and there are 4 important constants for defining version code and version name.

* VERSION\_MAJOR
* VERSION\_MINOR
* VERSION\_PATCH
* VERSION\_BUILD

See [Versioning Your Applications](http://developer.android.com/tools/publishing/versioning.html#appversioning) in Android documentation for more info.

There are also a build config fields in this script. Check "buildTypes" configuration and make sure that all fields are set up properly for debug and release. It is very important to correctly set these true/false switches before building the APK.

Dependencies
============
* [AppCompat](https://developer.android.com/reference/android/support/v7/appcompat/package-summary.html)

Developed by
============
Marouen Hammami

