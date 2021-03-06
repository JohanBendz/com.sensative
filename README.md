This app adds support for the Sensative Strips family of products in Homey.

## Supported devices with most common parameters:
* Strips Guard (door/window sensor)
* Strips Drip
* Strips Comfort

## Supported Languages:
* English
* Dutch

Release notes
-------------
**2.1.0:**
* Fixed an issue with Strips Comfort heat alarm (thanks Vegard!)
* Added maintenance actions to reset alarms manually (requires Homey 3.1+)
* Added battery information for all supported devices
* Updated to latest homey-meshdriver (1.3.3)

**2.0.1:**
* Fixed a number of issues with Strips Drip and Strips Comfort

**2.0.0:**
* Support for notification command class for Strips Guard.
  Using this instead of the binary sensor command class should fix an issue with devices with firmware 0.7 or older.
* Add tamper alarm capability for Strips Guard
* Preliminary support for Strips Drip and Strips Comfort
* Upgraded to Homey SDK 2.0 
  
**1.0.3:**
* Z-Wave configuration parameters should be properly initialized upon inclusion now.
* Requires Homey 1.0.3 firmware due to an issue in combination with 1.0.1 and 1.0.2 firmwares.

**1.0.1:**
* In this initial version, Strips will be set to a simple binary sensor. I'd like to switch to using its default operating mode in the future, which may require the device to be re-added.
* The US version of Strips is not yet recognized. It may be added in a future version (testers needed).

Disclaimer
----------
This application is not affiliated with Sensative AB. Sensative AB is not responsible for the operation or content of this application.
