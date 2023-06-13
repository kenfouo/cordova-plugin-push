# Cordova Plugin Push

This is a copy of https://github.com/havesource/cordova-plugin-push? We modified it to provide iOS 14 support with cordova. It also fixes the problem of the Obsolete googlemaps SDK for 03 years.

# Contribution

My Email: borientm@gmail.com.
Our development conditions are not always better here in Africa.
also, Your sponsorship will be of great use to us. PayPal Link: https://paypal.me/Borientmk?country.x=LS&locale.x=fr_XC

[![Node CI](https://github.com/havesource/cordova-plugin-push/actions/workflows/ci.yml/badge.svg)](https://github.com/havesource/cordova-plugin-push/actions/workflows/ci.yml) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/422c67b5e70c4a0eadae7b9fc794d3c1)](https://app.codacy.com/gh/havesource/cordova-plugin-push?utm_source=github.com&utm_medium=referral&utm_content=havesource/cordova-plugin-push&utm_campaign=Badge_Grade_Settings)

> Register and receive push notifications

# What is this?

This plugin offers support to receive and handle native push notifications with a **single unified API**.

This does not mean you will be able to send a single push message and have it arrive on devices running different operating systems. By default Android uses FCM and iOS uses APNS and their payloads are significantly different. Even if you are using FCM for both Android and iOS there are differences in the payload required for the plugin to work correctly. For Android **always** put your push payload in the `data` section of the push notification. For more information on why that is the case read [Notification vs Data Payload](https://github.com/havesource/cordova-plugin-push/blob/master/docs/PAYLOAD.md#notification-vs-data-payloads). For iOS follow the regular [FCM documentation](https://firebase.google.com/docs/cloud-messaging/http-server-ref).

This plugin does not provide a way to determine which platform you are running on. The best way to do that is use the `device.platform` property provided by [cordova-plugin-device](https://github.com/apache/cordova-plugin-device).

* [Reporting Issues](docs/ISSUES.md)
* [API reference](docs/API.md)
* [Typescript support](docs/TYPESCRIPT.md)
* [Examples](docs/EXAMPLES.md)
* [Platform support](docs/PLATFORM_SUPPORT.md)
* [Cloud build support (PG Build, IntelXDK)](docs/PHONEGAP_BUILD.md)
* [Push notification payload details](docs/PAYLOAD.md)
* [Contributing](.github/CONTRIBUTING.md)
* [License (MIT)](MIT-LICENSE)

# Do you like tutorial? You get tutorial!

## Quick install
    cordova plugin add github:kenfouo/cordova-plugin-push --save 

* [PhoneGap Day US Push Workshop 2016 (using node-gcm)](http://macdonst.github.io/push-workshop/)

