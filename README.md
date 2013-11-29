GDK Playground
=======

`GDK Demo` is a collection of Glass Development Kit sample apps and example code.
You can quickly test new GDK API features using the sample Glassware.

Refer to [the official GDK doc](https://developers.google.com/glass/develop/gdk/index)
for more information on the Glass Development Kit.
This repository contains (will contain) a variety of example programs and sample code,
and other apps and libraries, which are built with GDK,
or which are otherwise relevant to Glassware development.


You can build the demo Glassware using Gradle:

    gradle clean build

You can install it on your Glass (if you have one) using `adb`.

    adb install -r build/apk/[app name]-release.apk


You can also import any of the Glassware projects
into an IDE such as Android Studio.


# API Demo

## GDK Live Card Sample Code

The [apidemo](https://github.com/harrywye/gdkdemo/tree/master/apidemo) directory contains two Glass apps
which demonstrate a simple implementation of the 
[LiveCard](https://developers.google.com/glass/develop/gdk/ui/live-cards) API.
The second app, Live Card Demo 2, includes a sample code
for updating the LiveCard content via "low frequency rendering".


## GDK Touch Gesture Sample Code

This Glassware shows to how to implement
the [Touch Gesture](https://developers.google.com/glass/develop/gdk/input/touch) input modes.
The app can be started using the following voice input:

_OK, Glass._ _Start Gesture Demo_


## GDK Voice Input Sample Code

This demo Glassware uses the GDK Voice Input API.
You can start the app via Voice Trigger, _Start Voice Demo..._, followed by the phrase _dictate_.
This voice command opens a new activity, 
which includes the "dictation" function.
Tap to start dictation.


## GDK Location Sample Code

This example app uses the Android `LocationManager` API
to display the user's dynamic location on the LiveCard.




