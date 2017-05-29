## What's new?

The Android part of the plugin was updated:

VERSION 1.0.1:
    - Ranging OK,
    - SecureRanging OK using a BeaconRegion (and not a SecureBeaconRegion),
    - Monitoring NOT TESTED,
    - Discovery NOT WORKING,
    - Connection NOT WORKING (because of no connectivity packets).

VERSION 1.0.2 & 1.0.3:
    - Ranging NOT WORKING,
    - Monitoring NOT TESTED,
    - Discovery OK,
    - Connection OK.

See https://github.com/Estimote/Android-SDK/issues/211.

## About the Estimote Cordova/PhoneGap plugin

This plugin makes it easy to develop Cordova apps for Estimote Beacons and Estimote Stickers. Use JavaScript and HTML to develop stunning apps that take advantage of the capabilities of Estimote Beacons and Stickers.

![Estimote Beacons](http://estimote.com/assets/gfx/press/branding/Estimote-Logo-BW-Horizontal.c457034e.png)

## Updated API

The JavaScript API has been updated. Please note that the new API is not backwards compatible. The original API is available in the branch "0.1.0".

As of version 0.6.0 the API consists of two modules, "estimote.beacons" and "estimote.nearables", with support for Estimote Beacons and Estimote Stickers. "EstimoteBeacons" is kept for backwards compatibility, and points to "estimote.beacons".

A change log is found in file [changelog.md](changelog.md).

## Beacon Finder example app

Try out the Beacon Finder example app, which is available in the examples folder in this repository. Find out more in the [README file](examples/beacon-finder/README.md) and look into the details of the [example source code](examples/beacon-finder/www/).

## How to create an app using the plugin

See the instructions in the Beacon Finder [README file](examples/beacon-finder/README.md).

## Documentation

The file [documentation.md](documentation.md) contains an overview of the plugin API.

Documentation of all functions is available in the JavaScript API implementation file [EstimoteBeacons.js](plugin/src/js/EstimoteBeacons.js).

## Credits

Many thanks goes to [Konrad Dzwinel](https://github.com/kdzwinel) who developed the original version of this plugin and provided valuable support and advice for the redesign of the plugin.

Many thanks also to all contributors! https://github.com/evothings/phonegap-estimotebeacons/pulls?q=is%3Apr+is%3Aclosed
