# Changelog

All notable changes to the Gainsight PX Android SDK are documented in this file.

## Version 1.13.6

* Fix YouTube Error 153 in mobile engagements

## Version 1.13.5

* Minor bug fixes

## Version 1.13.4

* Engagement support when switching user

## Version 1.13.3

* Engagement displaying is more stable and will only be dismissed if the main resource is unavailable and not for CSS

## Version 1.13.2

* Enabling the engagements by default
* Reducing engagement sync time from every 5 min to 2 min (align with iOS)

## Version 1.13.1

* Making sure that network operations will not prevent event caching

## Version 1.12.4

* Added HMAC support for Identify User

## Version 1.12.3

* Fixing Encryption/Decryption issues
* Aligning all User and Account fields with Web API

## Version 1.12.2

* Fixing feature mapper crash

## Version 1.12.1

* Add support for using Application Context

## Version 1.12.0

* Stop collecting device and advertising ids on Android
* Fixing configuration issue with Hybrid SDK on Android

## Version 1.11.0

* Upgrading project Gradle and AGP versions
* Fixing bugs

## Version 1.10.1

* If view has no id, but has string as tag - we'll use it as id
* Adding the exception thrown to ExceptionHandler values

## Version 1.10.0

* Adding reset API call for recreating instance with new configuration
* Adding API to enable/disable engagements at runtime
* Fixing bugs

## Version 1.9.0

* Adding support for Interval engagement scope

## Version 1.8.0

* Adding support for Every time (Paywall) engagement scope

## Version 1.7.5

* Fixing Reset functionality

## Version 1.7.4

* Renaming Builder maxQueueSize
* Web JS Platforms initialization: supporting also maxQueueSize and host

## Version 1.7.3

* Support tracking web view content (inside native app)
* Adding configuration for limiting persistent cache queue size
* Fixing bugs

## Version 1.7.0

* Supporting Web JS platforms e.g. Ionic, Sencha, Cordova
* Filtering out non-SDK deep links
* Adding new datacenter

---

Release notes for versions prior to 1.7.0 are not documented here.
