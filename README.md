# NativeScript.GettingStarted


## Overview

How to get started building iOS app with NativeScript.

### Installation
This document describe the different installation steps to be able to
- Develop NativeScript/Vue.js iOS application on Windows
- Build and install on Apple device the application using NativeScript Cloud Building

## Installation

### NativeScript + Vue

```bash
# sudo on macos
npm install -g nativescript
```

### Sikekick

Download and install [sidekick windows app](https://www.nativescript.org/nativescript-sidekick).

### MacOs Configuration
- Install XCode
- See instructions [ns-setup-os-x](https://docs.nativescript.org/start/ns-setup-os-x)

### Cloud Builds

[Cloud Builds](https://docs.nativescript.org/sidekick/user-guide/build-app/cloud-build)
allow to build the iOS app in the cloud.

#### Apple Developer Account
[Create Apple Developer Account](https://appleid.apple.com/account#!&page=create)
[Web Portal](https://iforgot.apple.com/appleid#!&section=appleid)

[Code Signing Assistance](https://docs.nativescript.org/sidekick/user-guide/code-signing/code-signing-for-ios/code-signing-assistance)

[Setting certificate and provisionning video](https://www.youtube.com/watch?v=5gKuR2UCOnM)

## Development Documentation

[XML Markup Language](https://docs.nativescript.org/ui/ns-ui-widgets/action-bar)


# Firebase

The firebase plugin does not work running your native script app in `Preview` mode.

- Error Message: `Plugin nativescript-plugin-firebase is not included in preview app on device 63453FFF-F433-4DBF-ACDC-23A3B8905966 and will not work.`

- Solutions
  * Compile the application locally with XCode and run it in the emulator
  * compile the application locally with XCode run it on a real device
  
