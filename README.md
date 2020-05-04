# SonyLiveView #

An Android app for Sony cameras to stream a live view of the camera image over wifi.

Based on the [Demo-App by ma1co](https://github.com/ma1co/PMCADemo).

## Build instructions
To build the program you need to install the Android SDK and gradle and set the environment
variable `ANDROID_HOME` to something like the following (adapt the path to where you installed it):  
` export ANDROID_HOME=$HOME/Android/Sdk`

To compile it run:
`gradle build`

After a successful build The finished apk is located under `app/build/outputs/apk/`.
