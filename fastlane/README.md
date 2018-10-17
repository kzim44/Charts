fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## iOS
### ios test
```
fastlane ios test
```
Runs all the tests
### ios certs
```
fastlane ios certs
```
Sync certs and provisioning
### ios release
```
fastlane ios release
```
Deploy a new version to the App Store.
### ios beta
```
fastlane ios beta
```
Deploy a new version to the App Store for TestFlight.
### ios dev
```
fastlane ios dev
```
Deploy a new ad-hoc version to the S3.

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
