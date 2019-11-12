Example implementation of `sentry-cocoa` (https://github.com/getsentry/sentry-cocoa) in a iOS project (obj-c, xCode 11).

# Getting Started

Install cocoapods and pod "Sentry". i.e.:

`bundle install`
`bundle exec pod install` 

Open the file `sentry-ios-obj-c-cocoapods.xcworkspace` with xCode 11 and change the Bundle Identifier and select a Team for automatic code siging (or switch to manual and set a profile).

Project runs without issues in iOS Simulator.

See `AppDelegate.m` and `ViewController.m` for how to acutally implement sentry features in your iOS Project.

Please check the docs for more detailed information: https://docs.sentry.io/clients/cocoa