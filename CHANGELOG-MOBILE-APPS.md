# Mobile apps Changelog

# 24.2.1 (2024-04-18)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-24.2.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-24.2.1)

## Changes

### Common

- Add ability to insert custom buttons in the overflow menu.
- Translation updates.
- Fixed visitors promote all option.
- Enable media on promotion for visitors.
- lib-jitsi-meet update.

### Android

- Dropped support for UVC cameras.
- Fix parsing server URL.
- Disable local storage for whiteboard.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-23.6.0...android-24.2.1)

### iOS

- react-native-webrtc@118.0.6 update which fixes duplicated audio.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-23.6.0...ios-24.2.1)

# 23.6.0 (2023-11-17)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-23.6.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-23.6.0)

## Changes

### Common

- Move breakout rooms to a dedicated screen
- Fix display name input on prejoin screen
- Fix keyboard overlapping chat input bar
- Fix displaying poll creator name
- Fix not keeping user settings after authentication
- Clear raised hands when conference changes
- Miscellaneous UI tweaks
- Update native dependencies
- Translation updates

### Android

- Fix crash on Android 14
- Fix scroll inside conference settings screen

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-23.5.0...android-23.6.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-23.5.0...ios-23.6.0)

# 23.5.0 (2023-09-25)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-23.5.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-23.5.0)

## Changes

### Common

- Authentication fixes

### Android

- Fix crash in Android <= S due to an outdated GMS dependency

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-23.4.0...android-23.5.0)

### iOS

- Fixed CallKit video button ending the call

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-23.4.0...ios-23.5.0)

# 23.4.0 (2023-09-15)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-23.4.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-23.4.0)

## Changes

### Common

- Authentication fixes
- Fix moderator logout when using token auth
- Fix not leaving conference if it was never properly joined
- Avoid starting to knock twice
- Add support for custom icons through dynamic branding
- Use rtcstats from lib-jitsi-meet
- Allow spaces when renaming breakout rooms
- Hide Grant Moderator button inside breakout rooms
- Small UI tweaks
- Update native dependencies
- Translation updates

### Android

- Bump target API level to 33
- Disable full-screen while screen-sharing

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-23.3.1...android-23.4.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-23.3.1...ios-23.4.0)

# 23.3.1 (2023-08-24)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-23.3.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-23.3.1)

## Changes

### Common

- Fix for non-token authentication.

# 23.3.0 (2023-08-23)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-23.3.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-23.3.0)

## Changes

### Common

- New Settings screen
- Support for Firebase authentication
- Hide Grant Moderator inside breakout rooms
- Authentication through Profile screen
- Count badge for Participants button

# 23.2.0 (2023-07-11)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-23.2.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-23.2.0)

## Changes

### Common

- Use more efficient codecs by default
- Add unsafe room name warning
- Add ability to control remote track volume
- Settings: add field with SDK version
- Fix not showing a screen-share until reload
- Fix and zoom in remote screen-share
- Fixes for visitor mode
- Update native dependencies
- Updated translations

### Android

- Set MainActivity launch mode to singleInstance

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-23.1.2...android-23.2.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-23.1.2...ios-23.2.0)

# 23.1.2 (2023-05-03)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-23.1.2)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-23.1.2)

## Changes

### Common

- N/A

### Android

- Add support for hearing aid audio devices

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-23.1.1...android-23.1.2)

### iOS

- Fix video rendering crash

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-23.1.1...ios-23.1.2)

# 23.1.1 (2023-05-01)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-23.1.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-23.1.1)

## Changes

### Common

- N/A

### Android

- Raise minimum API level to 24

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-23.1.0...android-23.1.1)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-23.1.0...ios-23.1.1)

# 23.1.0 (2023-04-27)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-23.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-23.1.0)

## Changes

### Common

- Fix authentication

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-23.0.0...android-23.1.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-23.0.0...ios-23.1.0)

# 23.0.0 (2023-04-25)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-23.0.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-23.0.0)

## Changes

### Common

- UI tweaks to all screens
- Overhaul notifications UI
- Add language selection support to subtitles
- Replace ongoing meeting indicator with a notification
- Add support for visitor mode
- Reloading a meeting after a failure bypasses the pre-join screen
- Skip disabling low bandwidth mode when screen-sharing
- Open settings links in the system browser
- Fix UI conflict between raised hand indicator and filmstrip
- Fix joining breakout rooms
- Fix opening multiple share-meeting sheets
- Reinitialize rtcstats when the config changes
- Updated translations

### Android

- Fix not leaving the room when swiping the app from recent apps
- Added Monochrome icon

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-22.7.1...android-23.0.0)

### iOS

- Disable CallKit when running in the simulator

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-22.7.1...ios-23.0.0)

# 22.7.1 (2022-12-08)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-22.7.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-22.7.1)

## Changes

### Common

- Fixed not saving settings

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-22.7.0...android-22.7.1)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-22.7.0...ios-22.7.1)

# 22.7.0 (2022-11-25)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-22.7.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-22.7.0)

## Changes

### Common

- Dropped support for very old Jitsi Meet instances
- UI tweaks to all screens
- Update icons
- Fix hangup all action
- Fix displaying connection information and make it more accurate
- Updated translations

### Android

- Temporarily disable P2P

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-22.6.0...android-22.7.0)

### iOS

- Status bar is now visible at all times

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-22.6.0...ios-22.7.0)

# 22.6.0 (2022-10-21)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-22.6.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-22.6.0)

## Changes

### Common

- Fixed incompatibilities with recent Jitsi Meet deployments
- Add ability to start car mode when setting low bandwidth mode
- Force portrait when in car mode
- Prevent duplicated participant tiles
- Clear notifications when joining a conference
- Change default bridged calls codec to VP8
- Show participants pane button in the top bar
- Fixed screen headers not being translatable
- Fixed welcome page tabs not being translatable
- Fixed showing stale recording labels in car mode
- Numerous UI tweaks and improvements
- Updated translations

### Android

- Add support for the H.264 hardware accelerated codec
- Fix back button behavior in the welcome page

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-22.5.1...android-22.6.0)

### iOS

- Fix layout issues in iOS 16

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-22.5.1...ios-22.6.0)

# 22.5.1 (2022-09-09)

(The 22.5.0 release was aborted)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-22.5.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-22.5.1)

## Changes

### Common

- Rework the settings screen, now also accessible from the in-meeting menu
- Numerous UI tweaks and improvements
- Updated translations

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-22.4.0...android-22.5.1)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-22.4.0...ios-22.5.1)

# 22.4.0 (2022-07-11)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-22.4.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-22.4.0)

## Changes

### Common

- Numerous UI fixes and improvements
- Show more tiles in landscape mode
- Make sure PiP is only available while in a meeting

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-22.3.1...android-22.4.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-22.3.1...ios-22.4.0)

# 22.3.1 (2022-06-30)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-22.3.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-22.3.1)

## Changes

### Common

- Fix broken recording dialog

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-22.3.0...android-22.3.1)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-22.3.0...ios-22.3.1)

# 22.3.0 (2022-06-25)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-22.3.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-22.3.0)

## Changes

### Common

- Add a pre-join screen
- Add ability to move participants across rooms without being in them
- Add show self-view button in overflow menu
- Make sure Picture-in-Picture is only enabled in the conference screen
- Car Mode improvements: force portrait mode, add connection indicator
- Update the lobby UI
- Use native navigation components
- Update WebRTC to version 100
- Fix landscape mode tile view
- Fix janky scrolling in bottom sheets 
- Fix incorrect handling of private chat replies
- Fix video context sheet not displaying
- Navigation improvements
- Numerous UI tweaks and improvements
- Updated translations

### Android

- Fix incorrect colors on MIUI 12 devices
- Fix initial muted state in the ongoing notification
- Fix crash starting foreground service

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-22.2.0...android-22.3.0)

### iOS

- Fix not using the loudspeaker by default

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-22.2.1...ios-22.3.0)

# 22.2.0 (2022-05-16)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-22.2.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-22.2.0)

## Changes

### Common

- Add Car Mode
- Added GIPHY integration
- Revamp lobby UI
- Stop reordering tiles in small meetings
- Don't show raise hand button in menu if disabled
- Don't disable screen-sharing button when in audio-only mode
- Hide display name label in one to one meeting
- Updated UI for thumbnail indicators
- Fix private chat messages getting stuck
- Fix lobby not showing up on subsequent tries
- Fix joining breakout rooms
- Fix participant list not taking enough space
- Fix recording start button not being enabled
- UI tweaks and fixes
- Updated translations

### Android

- Fix crash when starting foreground service on some devices
- Fix back button behavior

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-22.1.0...android-22.2.0)

### iOS

- Fix not marking speaker as a selected device
- Fix not showing the CarPlay audio interface

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-22.1.0...ios-22.2.0)

# 22.1.0 (2022-03-22)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-22.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-22.1.0)

## Changes

### Common

- Recording UI updates
- Navigation improvements
- Updated translations
- Bug fixes and improvements

### Android

- Fix crash when showing dialogs on certain devices

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-22.0.0...android-22.1.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-22.0.0...ios-22.1.0)

# 22.0.0 (2022-03-02)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-22.0.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-22.0.0)

## Changes

### Common

- Consistent coloring across the UI
- Reworked all dialogs
- Navigation improvements
- Layout improvements in tile view
- Fix echo issue in some scenarios
- Fix losing screen-share under certain circumstances
- Updated translations
- Bug fixes and improvements

### Android

- Fix crash due to EGL context leaks
- Fix white "flash" when loading

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-21.6.0...android-22.0.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-21.6.0...ios-22.0.0)


# 21.6.0 (2021-12-21)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-21.6.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-21.6.0)

## Changes

### Common

- Re-enables PIP after stopping screen-share
- Updated translations
- Bug fixes and improvements

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-21.5.0...android-21.6.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-21.5.0...ios-21.6.0)

# 21.5.0 (2021-12-03)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-21.5.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-21.5.0)

## Changes

### Common

- Added breakout rooms
- Added speaker stats
- Added search in participants list
- Revamped UI of the top conference bar
- Revamp all screens to use smooth transitions
- Coalesce participant left and raised hand notifications
- Update WebRTC engine to M94
- Show raised hand indicators in the participants pane
- Advanced moderation improvements
- Stop displaying local video on the welcome page
- Updated translations

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-21.4.1...android-21.5.0)

### iOS

- Don't show "disable call integration" on the settings page, it's not implemented on iOS

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-21.4.2...ios-21.5.0)

# 21.4.2 (2021-10-01)

- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-21.4.2)

## Changes

### iOS

- More fixes for iOS 15 compatibility

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-21.4.1...ios-21.4.2)

# 21.4.1 (2021-09-29)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-21.4.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-21.4.1)

## Changes

### Common

- N/A

### Android

- Disable uncompressed native libs usage
- Fix crash in WebRTC view handling

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-21.4.0...android-21.4.1)

### iOS

- Fixed crash on WebSocket connection errors

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-21.4.0...ios-21.4.1)

# 21.4.0 (2021-09-23)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-21.4.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-21.4.0)

## Changes

### Common

- Added advanced moderation capabilities
- Added ability to make polls
- Added support for reactions
- Added invite button to top navbar
- Added support for XMPP WebSocket connections (behind a flag)
- Performance improvements for large meetings
- Fixed shared-video placeholder not being translated
- Fixed crash on invalid shared-video URLs
- Fixed sidebar not appearing on RTL languages
- Fixed not counting "fake" participants when joining a conference
- Updated translations

### Android

- Disable PiP when login into Dropbox

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-21.3.0...android-21.4.0)

### iOS

- Fixes for iOS 15 compatibility

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-21.3.0...ios-21.4.0)

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
