# MeanExamPrep06

####Explain the concept of Hybrid Mobile App Development

The concept about hybrid app development, is that you use web programming language to code an app for any platform.


####Explain the Pros & Cons of using Hybrid Mobile App Development compared to Native App Development.

**Pros about hybrid mobiles apps developments:**
- Easy to create and you only have to know about web techs. 
- You can converte the code to platforms like iOS or andriod.

**The disadvantage about hybrid apps:**
- You dont have specific native app development tools and libraries.
- Hybrid apps are slower than the native.

####Explain about the "building blocks" involved in an ionic Hybrid Application

**The building blocks of a hybrid app has three key blocks**
-	The codebase – made with webtechnologies
-	Compiler – PhoneGap/ionic
-	Runtime – Native platform

####Explain and demonstrate ways to debug Hybrid Mobile Applications Running on a real device
- [Enable USB debugging on your device] (https://developer.chrome.com/devtools/docs/remote-debugging)
- Open Chrome on your desktop (development) machine and navigate to: chrome://inspect
- Select Discover USB Devices.
- Select your device.
- To use your device to debug a web application that’s running on your development machine:
  * Click Port forwarding….
  * Set the device port and the localhost port.
  * Select Enable port forwarding. [See for details.](https://developer.chrome.com/devtools/docs/remote-debugging#port-forwarding)

####Explain when and why CORS is a problem for Hybrid Mobile Applications

the hybrid app has some issues when you are trying to request data, because its coming from another location and therefore doesnt have access. 
This can be prevented by making the "Access-Control-Allow-Origin: *".

If you use firebase you don’t have these kinds of issues.

####Explain how and why it is possible for a Hybrid Application to access native phone devices like location, calendar etc.

By using the native wrapper cordova, you can get plugins, which communicate, to native phone functions. 
Cordova is used for compiling ionic.

####Explain using an example the "fundamentals" of an ionic application.

Ionics fundamentals is a HTML5 language which is builded on AngularJS

[See example.](https://github.com/Asnorrason/MeanExamPrep06/tree/master/IonicAppExamPrep)


####Explain using an example how your Hybrid Application communicates with a backend and how CORS problems were solved (if any).

I didn’t have any problem with CORS, because the app uses firebase as backend.

To see how I communicate with the backend, see – [link](https://github.com/Asnorrason/MeanExamPrep06/blob/master/IonicAppExamPrep/www/js/services.js)
