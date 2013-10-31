MobileApps
==========

Android app development using Cordova

Set up instructions:<br>
1. Download node.exe --http://nodejs.org/dist/latest/node.exe <br>
   --Lets suppose its downloaded to C:\NODE_HOME  <br>
2. Download npm and extract its contents to npm --http://nodejs.org/dist/npm/ <br>
   --Lets suppose its extrcated to C:\NPM_HOME (would contain npm.cmd and node_modules) <br>
3. Download Android  SDK and extrct its contents--http://developer.android.com/sdk/index.html <br>
   --Lets suppose its extracted to c:\ANROID_HOME <br>
4. Download Ant and extract its contents <br>
   --Lets suppose its extracted to C:\ANT_HOME 

PATH setup:<br>
Path should include below locations<br>
C:\NODE_HOME<br>
C:\NPM_HOME<br>
C:\ANDROID_HOME\sdk\tools;C:\ANDROID_HOME\sdk\platform-tools<br>
C:\ANT_HOME\bin

From Windows command prompt:<br>
npm install -g cordova<br>
cordova create my-app<br>
cd my-app<br>
cordova platform add android<br>
cordova build android<br>
cordova emulate android<br>




