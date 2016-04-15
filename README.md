This is a repo contains webrtc h264 support on experimental Crosswalk build.
The build result is xwalk_core_library.aar file

How to to use it in Cordova project:
1: You can follow the wiki to set up cordova based on Crosswalk Webview: https://crosswalk-project.org/documentation/cordova.html
2: After command "cordova plugin add cordova-plugin-crosswalk-webview"
   Do these 2 steps
   A: copy xwalk_core_library.aar to platforms/android/libs/ under your cordova project
   B: update the gradle file under platforms/android/cordova-plugin-crosswalk-webview/yourproject-xwalk.gradle
      Should be similar with the sample hellocordova-xwalk.gradle in this repo (You can use diff and update the change)

3: cordova build android

