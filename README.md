# Joke Telling App

In this project, we create an app with multiple flavors that uses
multiple libraries and Google Cloud Endpoints. The finished app will consist
of four modules. A Java library that provides jokes, a Google Cloud Endpoints
(GCE) project that serves those jokes, an Android Library containing an
activity for displaying jokes, and an Android app that fetches jokes from the
GCE module and passes them to the Android Library for display.

### App Components

* Project contains a Java library for supplying jokes
* Project contains an Android library with an activity that displays jokes passed to it as intent extras.
* Project contains a Google Cloud Endpoints module that supplies jokes from the Java library. Project loads jokes from GCE module via an async task.
* Project contains connected tests to verify that the async task is indeed loading jokes.
* Project contains paid/free flavors. The paid flavor has no ads, and no unnecessary dependencies.

### App Behavior

* App retrieves jokes from Google Cloud Endpoints module and displays them via an Activity from the Android Library.

### Used Libraries and Concepts

* Gradle
* Multi-Module Application
* Java Libraries
* Android Libraries
* Fragments
* Google app engine
* Android Flavors

### Screens
![Alt text](/Screenshots/s1.png?raw=true)
![Alt text](/Screenshots/s2.png?raw=true)
![Alt text](/Screenshots/s3.png?raw=true)
![Alt text](/Screenshots/s4.png?raw=true)




