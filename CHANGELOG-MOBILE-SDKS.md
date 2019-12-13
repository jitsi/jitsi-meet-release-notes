# Mobile SDKs Changelog

# 2.5.0 (2019-12-13)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.5.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.5.0)

## Changes

### Common

- Allow for userInfo and token to be set at the same time
- Refactored bottom sheet menu
- Chat UX improvements

### Android

- Fix crash on old devices using the Camera1 API
- Fix selecting the Bluetooth route on some devices
- Improve audio device management

Relevant native dependencies:

- react-native 0.61.3
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.4.2...android-sdk-2.5.0)

### iOS

- Drop support for iOS 10

NOTE: due to a build issue this version was released as 2.5.1 on CocoaPods.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.4.2...ios-sdk-2.5.0)

# 2.4.2 (2019-11-08)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.4.2)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.4.2)

## Changes

### Common

- N/A

### Android

- Fix crash with room names containing some Unicode characters
- Fix share document showing "unsupported browser"
- Fix audio device handling regressions

Relevant native dependencies:

- react-native 0.61.3
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.4.1...android-sdk-2.4.2)

### iOS

- Switch to the "new" Xcode build system
- Enabled Swift modules stability
- SDK compiled with Xcode 11.2.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.4.1...ios-sdk-2.4.2)

# 2.4.1 (2019-10-31)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.4.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.4.1)

## Changes

### Common

- Add advanced settings section
- Update React Native to version 0.61.3

### Android

- Refactor audio device handling

Relevant native dependencies:

- react-native 0.61.3
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.4.0...android-sdk-2.4.1)

### iOS

- Disable H.264 on iOS 10 devices due to crashes

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.4.0...ios-sdk-2.4.1)

# 2.4.0 (2019-10-21)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.4.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.4.0)

## Changes

### Common

- Private messages support
- Shared document editing support
- Update React Native to version 0.61
- Indicate recording initiator in notification
- Harden loading the configuration

### Android

- Throw exception if room is set in default conference options
- Fix several crashes in specific devices

Relevant native dependencies:

- react-native 0.61.1
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.3.2...android-sdk-2.4.0)

### iOS

- Build SDK with Xcode 11
- Disable H.264 for P2P on iOS 10 devices due to crashes
- Fix bottom sheet "shaking"
- Fix crash on call end

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.3.1...ios-sdk-2.4.0)

# 2.3.2 (2019-09-26)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.3.2)

## Changes

### Android

- Stability improvements

Relevant native dependencies:

- react-native 0.60.5
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.3.1...android-sdk-2.3.2)

# 2.3.1 (2019-09-20)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.3.1)

## Changes

### Android

- Fix missing thumbnails and broken conference state

Relevant native dependencies:

- react-native 0.60.5
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.3.0...android-sdk-2.3.1)

### iOS

- Disable H.264 on iOS 10 devices (avoids a crash)
- Fix crashes when WebRTC restarts the AudioUnit

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.3.0...ios-sdk-2.3.1)

# 2.3.0 (2019-09-17)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.3.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.3.0)

## Changes

### Common

- Add low bandwidth mode
- Add logging APIs
- Updated WebRTC to M75
- Hide invite button if the functionality is not available
- Update default color scheme
- Show prompt when device permissions are denied
- Enable the proximity sensor only when the audio device is set to earpiece
- Update UI for the invite dialog
- Fix loading welcome page if no config could be fetched

### Android

- Migrated to AndroidX
- Fix crash on certain devices when starting a foreground service
- Audio quality improvements
- Fix crashes on bogus calendar entries on certain devices

Relevant native dependencies:

- react-native 0.60.5
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.2.2...android-sdk-2.3.0)

### iOS

- Fix crash when processing certain calendar events
- Fix CallKit muted state in latest iOS version

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.2.0...ios-sdk-2.3.0)

# 2.2.2 (2019-07-16)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.2.2)

## Changes

### Android

- Fix crash if UserInfo is not passed

Relevant native dependencies:

- react-native 0.59.8
- okhttp: 3.12.1
- android-support: 28.0.0

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.2.1...android-sdk-2.2.2)

# 2.2.1 (2019-07-03)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.2.1)

## Changes

### Android

- Fix threading issue on hangup
- Fix deadlock

Relevant native dependencies:

- react-native 0.59.8
- okhttp: 3.12.1
- android-support: 28.0.0

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.2.0...android-sdk-2.2.1)

# 2.2.0 (2019-06-28)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.2.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.2.0)

## Changes

### Common

- Add SDK API to set user information
- Add SDK API for setting feature flags (calendar integration, chat integration and recording on iOS can be toggled)
- Exit audio-mode when video-unmuting
- Add ability to set the conference subject
- Fix losing audio if call is hangup too quickly
- Don’t render moderator icon if everyone is moderator
- Update react-native@0.59.8
- Chat improvements (rewrite)
- Ensure the conference terminated event is always sent
- Add connection quality indicator
- Add display name label to tile view

### Android

- Add notification while there is an ongoing meeting
- Add ability to keep track of the current ongoing conference
- Make sure we left the current meeting when the activity is destroyed
- Do not enter PiP mode when the permissions alert is shown
- Add the ability to make a "libre" build
- Make JitsiMeetActivity.leave() public
- Make JitsiMeetActivity.join() public
- Enter PiP mode when pressing back button

Relevant native dependencies:

- react-native 0.59.8
- okhttp: 3.12.1
- android-support: 28.0.0

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.1.0...android-sdk-2.2.0)

### iOS

- Add property for setting PiP initial position
- Fix CallKit crash in development mode

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.1.0...ios-sdk-2.2.0)

# 2.1.0 (2019-04-10)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.1.0)

## Changes

### Common

- Improve call setup delay
- Update react-native@0.59.4

### Android

Relevant native dependencies:

- react-native 0.59.4
- okhttp: 3.12.1
- glide: 4.7.1
- android-support: 28.0.0

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.0.0...android-sdk-2.1.0)

### iOS

- Update to Xcode 5 and Swift 5

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.0.0...ios-sdk-2.1.0)
