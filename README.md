# cordova-plugin-push

This is a copy of https://github.com/mapsplugin/cordova-plugin-googlemaps? We modified it to provide iOS 14 support with cordova.

### Installation
    cordova plugin add cordova-plugin-googlemaps --save
    
Cordova Plugin Push
Node CI Codacy Badge

Register and receive push notifications

What is this?
This plugin offers support to receive and handle native push notifications with a single unified API.

This does not mean you will be able to send a single push message and have it arrive on devices running different operating systems. By default Android uses FCM and iOS uses APNS and their payloads are significantly different. Even if you are using FCM for both Android and iOS there are differences in the payload required for the plugin to work correctly. For Android always put your push payload in the data section of the push notification. For more information on why that is the case read Notification vs Data Payload. For iOS follow the regular FCM documentation.

This plugin does not provide a way to determine which platform you are running on. The best way to do that is use the device.platform property provided by cordova-plugin-device.

Reporting Issues
Installation
API reference
Typescript support
Examples
Platform support
Cloud build support (PG Build, IntelXDK)
Push notification payload details
Contributing
License (MIT)
Do you like tutorial? You get tutorial!
PhoneGap Day US Push Workshop 2016 (using node-gcm)
Thanks to all our contributors
