MobileApps
==========

Android app development using Cordova

Set up instructions:
1. Download node.exe --http://nodejs.org/dist/latest/node.exe
   --Lets suppose its downloaded to C:\NODE_HOME  
2. Download npm and extract its contents to npm --http://nodejs.org/dist/npm/
   --Lets suppose its extrcated to C:\NPM_HOME (would contain npm.cmd and node_modules)
3. Download Android  SDK and extrct its contents--http://developer.android.com/sdk/index.html
   --Lets suppose its extracted to c:\ANROID_HOME
4. Download Ant and extract its contents
   --Lets suppose its extracted to C:\ANT_HOME

PATH setup:
Path should include below locations
C:\NODE_HOME
C:\NPM_HOME
C:\ANDROID_HOME\sdk\tools;C:\ANDROID_HOME\sdk\platform-tools
C:\ANT_HOME\bin

From Windows command prompt:
npm install -g cordova
cordova create my-app
cd my-app
cordova platform add android
cordova build android
cordova emulate android




