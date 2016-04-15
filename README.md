Found this gradle build of paho to make incorporating JavaComponents easier. Haven't made much of a contribution here yet as I've run into issues utilizing the BKS keystores. This was an easy to use and configre proof of concept for connecting to a non encrypted local MQTT broker via an Android Studio virtual device. This [site](https://eclipse.org/paho/clients/android/sample/) shows exactly how to utilize the app to make a connection to an MQTT broker.





# Getting started

## Download Android Studio
* https://developer.android.com/sdk/index.html
* Android SDK Manager
    * Install Android SDK Build-tools 23.0.0 or later
    * Install Android 6 (API 23)
        * SDK Platform 23
        * Extras
        * Android Support Repository

## Import Project
* Open Android Studio
* File -> Import Project
* Run -> Run 'app'

# Project Origin
This Android project is a clone from http://git.eclipse.org/c/paho/org.eclipse.paho.mqtt.java.git/ and just contains the changes to build it with gradle
