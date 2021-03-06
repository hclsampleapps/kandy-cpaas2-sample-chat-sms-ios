# kandy-cpaas2-sample-chat-sms-ios (Swift)
Sample app of CPaaS2 modules (SMS,Chat)

## Introduction
It is a sample app where CPaaS2 APIs are used to make the following modules

- [x] SMS
- [x] Chat

## Installation
Instructions to install the .ipa on iPhone using Xcode

1. Connect your device to your PC.
2. Open Xcode, go to Window → Devices .
3. Then, the Devices screen will appear. Choose the device you want to install the app on.
4. Drag and drop your .ipa file into the Installed Apps section.

## Usage
Instructions to use this app

1. Open this iOS application on iPhone
2. Enter the user details created at [AT&T API Marketplace](https://apimarket.att.com/)
3. Proceed further as required

## Development
Instructions to setup development environment

### Pre-requistie
If you don't have [CocoaPods](https://cocoapods.org/) installed on your system already, then install it.

For troubleshooting, please refer this link [How to install cocoapods?](https://stackoverflow.com/questions/20755044/how-to-install-cocoapods).

### Setup repository
To setup the project repository, run these commands

```
git clone https://github.com/hclsampleapps/kandy-cpaas2-sample-chat-sms-ios.git
cd kandy-cpaas2-sample-ios
```

### Build application
Instructions to build the app

1. Open the project folder in terminal.
2. Run 'pod install' it will add all the pods required.
3. Run 'pod update KandyCPaaSMobileSDK' to update to latest CpaaS pod.
4. Open RibbonSample.xcworkspace
5. Build and deploy the app

### Branching strategy
To learn about the branching strategy, contribution & coding conventions followed in the project, please refer [GitFlow based branching strategy](https://gist.github.com/ribbon-abku/10d3fc1cff5c35a2df401196678e258a) for your project repository.

### Coding conventions
Contributors should strictly follow the conventions mentioned at [Swift Style Guide](https://google.github.io/swift/).

