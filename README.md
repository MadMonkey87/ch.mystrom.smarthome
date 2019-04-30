# myStrom - Smart Home app for Homey

Adds support for [myStrom devices](https://mystrom.ch/smart-home/).

**Note:**

* Finding new devices can take up to 4 minutes.
* To add myStrom devices, you have to use the myStrom-App at the moment.
* If you have problems after the upgrade, register all devices new.

**Important note for Buttons**

Keep in mind that in order for the Button or Button+ to respond to any of these requests they have to be in the configuration mode:

* Button: (Re-)Connect the button to a power source with the provided USB cable. Press the button and after some time it should become visible in the network.
* Button+: Open the back of the button by rotating it clockwise. Remove the batteries and reinsert them. The Button+ should now be visible.

---

## Devices

* myStrom WiFi Switch       [supported]
* myStrom WiFi Bulb         [supported]
* myStrom WiFi Button       [supported]
* myStrom WiFi Button Plus  [supported]

---

## Changelog

v0.2.0

* Rewrite myStrom WiFi Button & Button+ (Due to Homey v2 & myStrom api changes)
* [Homey-App Logger](https://community.athom.com/t/how-to-integrate-a-homey-app-logger-to-your-app-for-a-simple-global-logger-in-homey) added
* Packages updated
* Homey-Dev added

v0.1.0

* Now uses [semantic versioning](https://semver.org/)

v0.0.5

* Release problem fixed

v0.0.4

* Support for myStrom WiFi Button Plus added
* Code refactored

v0.0.3

* Support for myStrom WiFi Button added
* New pictures added (Thanks to Tom)
* Device response error fixed

v0.0.2

* Support for myStrom WiFi Bulb added
* Device discovery refactored

v0.0.1

* Support for myStrom WiFi Switch added
* initial commit

---

## ToDo

* Test WPS-Mode
* Adding devices (pair) to WLAN without myStrom-app
* Button add battery level warning

---

## Copyright and license

Copyright 2017, 2017 cgHome under [ISC License](LICENSE)