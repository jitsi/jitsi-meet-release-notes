# Mobile apps Changelog

# 21.3.1 (2021-08-19)

- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-21.3.1)

## Changes

### iOS

- Fix deadlock when selecting audio device
- Fix conference failing when proximity sensor is near

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-21.3.0...ios-21.3.1)

# 21.3.0 (2021-08-17)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-21.3.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-21.3.0)

## Changes

### Common

- Add a participants panel
- Add "1on1" mode, which hides the remote thumbnail while in a 1-1 call
- Add the ability to share direct video links (mp4, etc.)
- Improve in-meeting options panel
- Update WebRTC to M92
- UI improvements
- Update the translations

### Android

- Fix install error on application compiled against Android S while targeting S+
- Fix crash in certain devices when the configuration is saved while in the background

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-21.2.0...android-21.3.0)

### iOS

- Skip sending newlines in the invite email

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-21.2.0...ios-21.3.0)

# 21.2.0 (2021-06-23)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-21.2.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-21.2.0)

## Changes

### Common

- Disable screen share when audioOnly mode
- Add capability for sharing any direct link video
- Fix displaying mute everyone buttons for non-moderators
- Show full participant thumbnails in tile view
- Place picture-in-picture button on the left
- Fix video-layout when a screen-sharing participant leaves
- New and updated translations

### Android

- Fix screen rotation when screen-sharing

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-21.1.0...android-21.2.0)

### iOS

- Detect orientation when screen sharing
- Fix leaving the meeting when screen-sharing

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-21.1.0...ios-21.2.0)

# 21.1.0 (2021-04-23)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-21.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-21.1.0)

## Changes

### Common

- Add security dialog
- Make sure immersive mode respect the fullscreen flag
- Redesign labels
- Fix button overflow in landscape orientation
- Always pin screenshare to large-video if it exists
- New and updated translations

### Android

- Adjust resolution to screen rotation when screen sharing

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-21.0.0...android-21.1.0)

### iOS

- Keyboard no longer covers message board and input
- Detect orientation when screen sharing

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-21.0.0...ios-21.1.0)

# 21.0.0 (2021-03-31)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-21.0.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-21.0.0)

## Changes

### Common

- Adaptive toolbar
- Brand new in-meeting UI
- Fix not focusing on single input dialogs
- Allow to toggle tile view even while alone
- Fix not showing alert when permission is not granted
- Implement aggressive layer suspension
- Fix incorrect bitrate calculation on mobile
- Stop room name generator when the room field is focused
- Other UI fixes
- Updated translations

### Android

- Set compile/target SDK versions to 30

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.6.2...android-21.0.0)

### iOS

- Screen sharing support

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.6.2...ios-21.0.0)

# 20.6.2 (2021-01-14)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.6.2)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.6.2)

## Changes

### Common

- Fix incorrect bitrate calculations

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.6.0...android-20.6.2)

### iOS

- Add support for screen sharing (iOS >= 14)

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.6.0...ios-20.6.2)

# 20.6.0 (2020-12-23)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.6.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.6.0)

## Changes

### Common

- Add connection information to participants contextual menu
- Fixed not always receiving screen shares when in low bandwidth mode
- Updated WebRTC engine to version 87
- Stability fixes and improvements
- Update translations

### Android

- Fix volume buttons not controlling meeting volume on some devices

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.5.0...android-20.6.0)

### iOS

- Fix (not) joining a meeting when the app was closed

NOTE: A 20.6.1 released quickly followed fixing a crash on startup on iOS 11 devices.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.5.0...ios-20.6.0)

# 20.5.0 (2020-11-17)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.5.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.5.0)

## Changes

### Common

- Add mute everyone / (else) capabilities
- Replace swipe options with long-press sheet in recents list
- Increase config load timeout to 10 seconds
- Fix error when reloading a failed conference
- UI/UX improvements
- Update translations

### Android

- Add screen-sharing support
- Fix crash when requesting permissions in certain cases
- Fix crash when fetching calendar entries
- Reduce app size
- Reduce app startup time

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.4.2...android-20.5.0)

### iOS

- Fix not rendering images on iOS 14

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.4.0...ios-20.5.0)

# 20.4.0 (2020-09-15)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.4.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.4.0)

## Changes

### Common

- Add screen-sharing indicator to thumbnails
- Fix chat issues
- Show lonely experience only after joining
- Tile view UI/UX improvements
- Updated translations

### Android

- Bump minimum API level to 23 and target API level to 29
- Make app movable to SD card
- Bring back activity to the foreground when exiting PiP

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.3.2...android-20.4.0)

### iOS

- Specify the correct keyboard type and content

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.3.2...ios-20.4.0)

# 20.3.2 (2020-07-22)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.3.2)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.3.2)

## Changes

### Common

- Fix overriding custom server URL

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.3.1...android-20.3.2)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.3.1...ios-20.3.2)

# 20.3.1 (2020-07-20)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.3.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.3.1)

## Changes

### Common

- Fix ghost participant when kicking

### Android

- Fix crash when refreshing calendar entries on some devices

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.3.0...android-20.3.1)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.3.0...ios-20.3.1)

# 20.3.0 (2020-07-14)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.3.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.3.0)

## Changes

### Common

- Improved performance by adjusting the send / receive video quality
- Added lobby mode
- Added YouTube video sharing feature
- Added unsafe room name warning
- Added ability to disable crash reporting
- Internationalization improvements
- Fixed incorrect text when locking a room with a password
- Fixed Picture-in-Picture window showing conference controls
- Fixed language detection to take region into account
- Fixed opening private chat messages
- Fixed on-screen keyboard overlapping certain dialogs

### Android

- Allow use of user trust store
- Disables PiP on Android < 26

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.2.3...android-20.3.0)

### iOS

- Try to leave the meeting when the app is terminating

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.2.3...ios-20.3.0)

# 20.2.3 (2020-04-30)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.2.3)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.2.3)

## Changes

### Common

- Fix not being able to send private chat messages.

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.2.2...android-20.2.3)

### iOS

- N/A

NOTE: There was no 20.2.2 release on iOS.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.2.1...ios-20.2.3)

# 20.2.2 (2020-04-16)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.2.2)

## Changes

### Common

- N/A

### Android

- Fix keyboard misbehavior in settingss view

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.2.1...android-20.2.2)

# 20.2.1 (2020-04-09)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.2.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.2.1)

## Changes

### Common

- Add new URL parameters: config.disableInviteFunctions, config.doNotStoreRoom and userInfo.displayName

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.2.0...android-20.2.1)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.2.0...ios-20.2.1)

# 20.2.0 (2020-04-07)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.2.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.2.0)

## Changes

### Common

- Added share button to "add people" dialog
- Fixed displaying room names with unicode characters
- Improved room lock prompt
- Improved translations

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.1.0...android-20.2.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.1.0...ios-20.2.0)

# 20.1.0 (2020-03-27)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.1.0)

## Changes

### Common

- Add ability to eassily invite others when alone
- Refactor in-conference menu
- Fix usability problems in the settings view
- Updated translations

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.0.3...android-20.1.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.0.3...ios-20.1.0)

# 20.0.3 (2020-02-14)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.0.3)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.0.3)

## Changes

### Common

- Add a "more options" button to the bottom sheet menu

### Android

- Revert to sotware decoding
- Fix not re-entering full-screen after dialog is shown

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.0.2...android-20.0.3)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-20.0.0...ios-20.0.3)

# 20.0.2 (2020-02-11)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.0.2)

## Changes

### Common

- N/A

### Android

- Fix AudioManager crashes

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.0.1...android-20.0.2)

# 20.0.1 (2020-02-10)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.0.1)

## Changes

### Common

- N/A

### Android

- Disable HW accelerated decoding on Samsung
- Disable ConnectionService integration

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-20.0.0...android-20.0.1)

# 20.0.0 (2020-02-20)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-20.0.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-20.0.0)

## Changes

### Common

- Add conference timer
- Fix connecting on custom deployments on a non-sstandard HTTPS port
- Fix not displaying Dropbox storage text

### Android

- Turn on HW video decoder

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-19.5.1...android-20.0.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-19.5.1...ios-20.0.0)

# 19.5.1 (2020-01-10)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-19.5.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-19.5.1)

## Changes

### Common

- N/A

### Android

- Improve stability when using ConnectionService

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-19.5.0...android-19.5.1)

### iOS

- Fix data channels not opening

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-19.5.0...ios-19.5.1)

# 19.5.0 (2019-12-13)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-19.5.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-19.5.0)

## Changes

### Common

- Refactored bottom sheet menu
- Chat UX improvements

### Android

- Improve audio device management

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-19.4.1...android-19.5.0)

### iOS

- Drop support for iOS 10

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-19.4.1...ios-19.5.0)

# 19.4.1 (2019-11-13)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-19.4.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-19.4.1)

## Changes

### Common

- N/A

### Android

- Stability improvements

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-19.4.0...android-19.4.1)

### iOS

- Fix not showing text color in settings when Dark Mode is used

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-19.4.0...ios-19.4.1)

# 19.4.0 (2019-11-08)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-19.4.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-19.4.0)

## Changes

### Common

- Private messages support
- Shared document editing support
- Indicate recording initiator in notification
- Harden loading the configuration
- Add advanced settings section
- Update React Native to version 0.61.3

### Android

- Stability improvements

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-19.3.1...android-19.4.0)

### iOS

- Disable H.264 on iOS 10 devices due to crashes
- Fix bottom sheet "shaking"
- Stability improvements

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-19.3.1...ios-19.4.0)

# 19.3.1 (2019-09-26)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-19.3.1)

## Changes

### Android

- Stability fixes

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-19.3.0...android-19.3.1)

### iOS

- Stability fixes

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-19.3.0...ios-19.3.1)

# 19.3.0 (2019-09-20)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-19.3.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-19.3.0)

## Changes

### Common

- Add low bandwidth mode
- Hide invite button if the functionality is not available
- Update default color scheme
- Show prompt when device permissions are denied
- Enable the proximity sensor only when the audio device is set to earpiece
- Update UI for the invite dialog
- Fix initial load if no config could be fetched

### Android

- Audio quality improvements
- Fix crash on certain devices when starting a foreground service
- Fix crashes on bogus calendar entries on certain devices

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-19.2.1...android-19.3.0)

### iOS

- Fix crash when processing certain calendar events
- Fix CallKit muted state in latest iOS version

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-19.2.0...ios-19.3.0)

# 19.2.1 (2019-07-03)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-19.2.1)

## Changes

### Android

- Fix critical stability issues

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-19.2.0...android-19.2.1)

# 19.2.0 (2019-07-02)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-19.2.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-19.2.0)

## Changes

### Common

- Add dial-in information on the welcome page
- Add participant connection indicator
- Add display name label to tile view
- Add "conference connecting" screen
- Add option to show on stage participant from tile view
- Fix inviting more than one participant
- Fix toggling toolbox from tile view
- Fix losing audio if call is hangup too quickly
- Make app more resilient to signaling errors
- Display conference subject if set
- Faster hangup time
- Improved chat

### Android

- Add notification while there is an ongoing meeting
- Set system navbar color to match the header
- Enter PiP mode when pressing the back button
- Fix entering PiP mode when the permissions alert is shown

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-19.1.0...android-19.2.0)

### iOS

- Add watchOS app
- Add a CallKit icon
- Fix memory leak
- Fix crashes in Metal renderer

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-19.1.0...ios-19.2.0)

# 19.1.0 (2019-04-02)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-19.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-19.1.0)

## Changes

- [Android](https://github.com/jitsi/jitsi-meet/compare/android-19.0.0...android-19.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/compare/ios-19.0.0...ios-19.1.0)
