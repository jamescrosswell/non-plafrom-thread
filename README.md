# demo

Demo applicatin for [record](https://github.com/llfbandit/record), to illustrate the `channel sent a message from native to Flutter on a non-platform thread` error.

This error occurs when deploying/running the application on physical iOS devices.

In order to publish the app to a physical device, you'll need to set the `DEVELOPMENT_TEAM` attribute under `Signing & Capabilities` in the Runner targets section of the `ios/Runner.xcodeproj/project.pbxproj` file. 
