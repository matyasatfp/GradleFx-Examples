This sample project shows you how to make a mobile application for iOS.
Also it shows how to include a native extension in your project and how to write ActionScript only tests.

How to use:
-----------

To build and launch on a connected device:

    gradlew launchMobile

To build an run the tests:

    gradlew build

To generate IntelliJ IDEA project files:

    gradlew idea


Notes:
------
The sample will not build on your device out of the box since it does not include an Apple developer key (.p12 file) and a .mobileProvision file. You need to get these by signing up to the Apple iOS developer program and generating your own.

Furthermore you need to add your own repository details in the build.gradle file, since I could not find any public repository that host the dependencies.
