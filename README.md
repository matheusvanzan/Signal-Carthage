# Readme Crthage

By: Matheus Vanzan

Xcode 10 (swift 5) workoaround

Download new repositories
carthage update --platform iOS
This will give PromiseKit compile error

Open PromiseKit.xcodeproj, change swift build settings to Swift 5
Build project on Xcode

Now, only build
carthage build --platform iOS
