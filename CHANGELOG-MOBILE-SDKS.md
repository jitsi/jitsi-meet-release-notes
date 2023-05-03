# Mobile SDKs Changelog

# 8.1.2 (2023-05-03)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-8.1.2)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-8.1.2)

## Changes

### Common

- N/A

### Android

- Add support for hearing aid audio devices

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-8.1.1...android-sdk-8.1.2)

### iOS

- Fix video rendering crash

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-8.1.1...ios-sdk-8.1.2)

# 8.1.1 (2023-05-01)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-8.1.1)

## Changes

### Android

- Raise minimum API level to 24

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-8.1.0...android-sdk-8.1.1)

# 8.1.0 (2023-04-27)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-8.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-8.1.0)

## Changes

### Common

- Fix authentication

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-8.0.0...android-sdk-8.1.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-8.0.0...ios-sdk-8.1.0)

# 8.0.0 (2023-04-25)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-8.0.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-8.0.0)

## Changes

- Updated WebRTC to version 111 and migrated to Unified Plan
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
- Updated React Native to version 0.68.6
- Updated translations

### Android

- Fix not leaving the room when swiping the activity recent apps
- Added default notification icon
- Allow to override integer config

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-7.0.1...android-sdk-8.0.0)

### iOS

- Avoid getting duplicated SDK events

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-7.0.1...ios-sdk-8.0.0)

# 7.0.1 (2022-12-08)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-7.0.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-7.0.1)

## Changes

- Fixed not saving settings

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-7.0.0...android-sdk-7.0.1)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-7.0.0...ios-sdk-7.0.1)

# 7.0.0 (2022-11-25)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-7.0.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-7.0.0)

## Changes

- BREAKING: legacy signalling support has been removed, thus the SDK will stop working with
  very old Jitsi Meet instances
- UI tweaks to all screens
- Update icons
- Fix hangup all action
- Add ability to hide settings button in overflow menu
- Add ability to go PiP while screen sharing (flag)
- Fix rendering connection information and make it more accurate
- Update React Native to version 0.68.5
- Updated translations

### Android

- Temporarily disable P2P
- Sort codecs in the same order as iOS
- Set compile and target SDKs to 32

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-6.2.2...android-sdk-7.0.0)

### iOS

- Status bar is now visible at all times
- Make initialPositionInSuperView a variable

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-6.2.2...ios-sdk-7.0.0)

# 6.2.2 (2022-10-24)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-6.2.2)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-6.2.2)

## Changes

- Fixes missing participant tiles when joining a meeting
- Set the default P2P codec to H.264
- Fixed not forcing VP8 for bridge calls

### Android

- Add support for the H.264 hardware accelerated codec

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-6.2.1...android-sdk-6.2.2)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-6.2.1...ios-sdk-6.2.2)

# 6.2.1 (2022-10-21)

(The 6.2.0 was aborted)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-6.2.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-6.2.1)

## Changes

- Fixed incompatibilities with recent Jitsi Meet deployments
- Add ability to start car mode when setting low bandwidth mode
- Force portrait when in car mode
- Prevent duplicated participant tiles
- Clear notifications when joining a conference
- Change default codec to VP8
- Show participants pane button in the top bar
- Fixed screen headers not being translatable
- Fixed welcome page tabs not being translatable
- Fixed showing stale recording labels in car mode
- Updated WebRTC to version 106
- Update React Native to version 0.68.4
- Numerous UI tweaks and improvements
- Updated translations

### Android

- Fix back button behavior in the welcome page
- Fix crash in devices with Android < 10
- Disable volume logger thread

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-6.1.0...android-sdk-6.2.1)

### iOS

- Fix layout issues in iOS 16
- Xcode 14 compatibility

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-6.1.0...ios-sdk-6.2.1)

# 6.1.0 (2022-09-09)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-6.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-6.1.0)

## Changes

- Add settings button and screen to the overflow menu
- Skip participant joined and left events for virtual screen shares
- Numerous UI tweaks and improvements
- Updated translations

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-6.0.0...android-sdk-6.1.0)

### iOS

- Add a "lite" SDK target

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-6.0.0...ios-sdk-6.1.0)

# 6.0.0 (2022-07-08)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-6.0.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-6.0.0)

## Changes

- BREAKING: External API scope has been removed
- Add a pre-join screen
- Add ability to move participants across rooms without being in them
- Add show self-view button in overflow menu
- Make sure Picture-in-Picture is only enabled in the conference screen
- Car Mode UI improvements
- Update the lobby UI
- Update WebRTC to version 100
- Fix landscape mode tile view
- Fix janky scrolling in bottom sheets 
- Fix incorrect handling of private chat replies
- Fix video context sheet not displaying
- Navigation improvements
- Numerous UI tweaks and improvements
- Updated translations

### Android

- BREAKING: JitsiMeetFragment has been removed
- BREAKING: Removed delegate methods, BroadcastReceiver is the only supported event mechanism now
- Fix incorrect colors on MIUI 12 devices
- Fix initial muted state in the ongoing notification
- Fix crash starting foreground service
- Set proper theme for JitsiMeetActivity

Relevant native dependencies:

- react-native: 0.68.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-5.1.0...android-sdk-6.0.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-5.1.0...ios-sdk-6.0.0)

# 5.1.0 (2022-05-16)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-5.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-5.1.0)

## Changes

- Add Car Mode
- Added GIPHY integration
- Revamp lobby UI
- Update React Native to version 0.68.1
- Update WebRTC to version M100
- Stop reordering tiles in small meetings
- Don't show raise hand button in menu if disabled
- Don't disable screen-sharing button when in audio-only mode
- Hide display name label in one to one meeting
- Updated UI for thumbnail indicators
- Fix last N getting stuck on 1
- Fix private chat messages getting stuck
- Fix navigation getting stuck in the connecting state
- Fix lobby not showing up on subsequent tries
- Fix joining breakout rooms
- Fix participant list not taking enough space
- Fix recording start button not being enabled
- UI tweaks and fixes
- Updated translations

### Android

- Fix crash when starting foreground service
- JitsiMeetActivity now uses JitsiMeetView instead of JitsiMeetFragment
- Fix back button behavior

Relevant native dependencies:

- react-native: 0.68.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-5.0.2...android-sdk-5.1.0)

### iOS

- Build SDK releases with bitcode
- Fix not marking speaker as a selected device
- Fix not showing the CarPlay audio interface
- Fix cycle in dependencies with Xcode 13.3

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-5.0.2...ios-sdk-5.1.0)

# 5.0.2 (2022-03-29)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-5.0.2)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-5.0.2)

## Changes

- Fix back button handling on Android
- Fix joining breakout rooms
- Fix lobby not showing up on subsequent tries

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-5.0.1...android-sdk-5.0.2)

# 5.0.1 (2022-03-28)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-5.0.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-5.0.1)

## Changes

- Fix broken recording dialog
- Fix not showing meeting participants by default in the pane
- Fix bottom color glitch when navigating from the connecting screen

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-5.0.0...android-sdk-5.0.1)

# 5.0.0 (2022-03-02)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-5.0.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-5.0.0)

## BREAKING Changes

- Removed unused code for incoming call view on Android
- Update React Native to version 0.66

## Changes

- Fix echo issue in some scenarios
- Fix losing screen-share under certain circumstances
- Tile view layout improvements
- Use native dialogs
- Navigation improvements
- Move all moderation functionality to the participants pane
- New in-conference header
- Update base UI colors
- Redesigned Thumbnails
- Revamped speaker stats UI
- Revamped security dialog
- Revamped recording screen
- Updated translations

### Android

- Fix EGL context leak
- Fix white "flash" when loading
- Drop jcenter

Relevant native dependencies:

- react-native: 0.66.4
- android-jsc: 250230.2.1
- okhttp: 4.9.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-4.1.0...android-sdk-5.0.0)

### iOS

- Add support for the simulator on Apple Silicon processors

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-4.1.0...ios-sdk-5.0.0)

# 4.1.0 (2021-12-14)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-4.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-4.1.0)

## Changes

- Created SecurityOptions React Navigation screen
- Fixed issue where last participant is shown as inactive when the self view is hidden
- Fixed not rendering display names in breakout-rooms
- Adjust the timeout for unmute blocked notifications
- Fixed the issue where the user muted by focus is able to unmute themselves even when the sender limit has been reached
- Fixed chat and polls title
- Re-enables PIP after stopping screen-share
- Updated translations

### Android

- Fixed keyboard covering input on chat
- Fixed NoClassDefFoundError for Android L/graphics/ColorSpace

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-4.0.0...android-sdk-4.1.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-4.0.0...ios-sdk-4.1.0)

# 4.0.0 (2021-12-03)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-4.0.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-4.0.0)

## BREAKING changes

This SDK update introduces breakout rooms and with it a very significant change: a new
"ready to close" event which signals the SDK is done and it's safe to hide the view.

Users should rely on this event / delegate method to destroy the Jitsi Meet SDK view
instead of the conference terminated event.

Some deprecated options in JitsiMeetConferenceOptions were removed.

Support for iOS 11 has been dropped.

## Changes

- Added breakout rooms
- Added speaker stats
- Added search in participants list
- Revamped UI of the top conference bar
- Revamp all screens to use smooth transitions
- Coalesce participant left and raised hand notifications
- Send AUDIO_MUTED_CHANGED event only when value changed
- Update WebRTC engine to M94
- Introduce a "ready to close" event
- Show raised hand indicators in the participants pane
- Drop deprecated option enableWelcomePage
- Drop deprecated color scheme option
- Fix not displaying a reload dialog when the conference fails
- Advanced moderation improvements
- Updated translations

### Android

- Remove unnecessary parcel processing
- Fix initializing SoLoader with the proper context

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.10.2...android-sdk-4.0.0)

### iOS

- Fixed RCTBridge not being released under certain circumstances
- Expose activating/deactivating audio session events
- Avoid creating CXProvider objects when CallKit is disabled
- Disable QuickType bar on iOS15 when not using autocorrect
- Drop support for iOS 11

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.10.4...ios-sdk-4.0.0)

# 3.10.4 (2021-10-08)

- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.10.4)

## Changes

### iOS

- iOS 15 fixes

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.10.3...ios-sdk-3.10.4)

# 3.10.3 (2021-10-01)

- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.10.3)

## Changes

### iOS

- Fix fist audio unmute not working on iOS 15.when "everyone starts muted" is set.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.10.2...ios-sdk-3.10.3)

# 3.10.2 (2021-09-24)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.10.2)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.10.2)

## Changes

### Android

- Targets Android 12

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.10.1...android-sdk-3.10.2)

### iOS

- Fix fist audio unmute not working on iOS 15.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.10.1...ios-sdk-3.10.2)

# 3.10.1 (2021-09-23)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.10.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.10.1)

## Changes

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.10.0...android-sdk-3.10.1)

### iOS

- Fix black screen when using Bluetooth devices

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.10.0...ios-sdk-3.10.1)

# 3.10.0 (2021-09-22)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.10.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.10.0)

## Changes

### Common

- Add advanced moderation capabilities
- Add an invite button on the top navbar
- Fix filmstrip rendering when thumbnail reordering is disabled
- Enable XMPP WebSocket on mobile (behind a flag)
- Fix counting fake participants when checking if lonely meeting
- Fix crash in share-video when using a bogus URL
- Disable PiP while authorizing Dropbox
- Small UI tweaks
- Updated translations

### Android

- Fix initializing soloader from Activity context
- Expose notification channel ids

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.9.0...android-sdk-3.10.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.9.0...ios-sdk-3.10.0)

# 3.9.1 (2021-09-06)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.9.1)

## Changes

### Android

- Fixed build due to new Amplitude SDK package name

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.9.0...android-sdk-3.9.1)

# 3.9.0 (2021-09-02)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.9.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.9.0)

## Changes

### Common

- Add ability to create polls
- Add reactions
- Significant performance improvements for large meetings
- Fix crash on shared video URLs with spaces
- Skip join notifications when meetings grow large
- Skip participant notifications when not in a meeting
- Skip participant joined notifications before we join
- Update Dropbox logic to retrieve refresh token
- Update Amplitude SDK
- UI fixes to bottom sheets
- Updated translations

### Android

- Avoid exception in onHostPause
- Added android screen share flag

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.8.0...android-sdk-3.9.0)

### iOS

- Fix conference failing when proximity sensor is near
- Fix deadlock when selecting audio device

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.8.0...ios-sdk-3.9.0)

# 3.8.1 (2021-08-19)

- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.8.1)

## Changes

### iOS

- Fix deadlock when selecting audio device
- Fix conference failing when proximity sensor is near

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.8.0...ios-sdk-3.8.1)

# 3.8.0 (2021-08-13)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.8.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.8.0)

## Changes

### Common

- Add a participants panel
- Add "1on1" mode, which hides the remote thumbnail while in a 1-1 call
- Add the ability to share direct video links (mp4, etc.)
- Add the ability to override any configuration option
- Refactored bottom sheets for UI consistency
- Improve in-meeting options panel
- Update WebRTC to M92
- UI improvements
- Update the translations

### Android

- Fix install error on application compiled against Android S while targeting S+
- Fix crash in certain devices when the configuration is saved while in the background

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.7.0...android-sdk-3.8.0)

### iOS

- Skip sending newlines in the invite email
- Add the ability to destroy & reinitialize the React Native bridge
- Skip exitPictureInPicture() call from resetBounds in PiPViewCoordinator

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.7.0...ios-sdk-3.8.0)

# 3.7.0 (2021-07-15)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.7.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.7.0)

## Changes

### Common

- Optimizes speaker stats to skip occupants with 0 talk time
- Add replaceParticipant feature-flag
- Place filmstrip videos over toolbar
- Enable deeplinking
- LocaleDetector should consider the language tag
- Include support for translated string resources at device permission dialog because it contains hardcoded english strings
- Update the translations

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.6.0...android-sdk-3.7.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.6.0...ios-sdk-3.7.0)

# 3.6.0 (2021-05-31)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.6.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.6.0)

## Changes

### Common

- Allow both regex and normal check for the room name
- Remove listener for native events when app unmounts
- Hide screen share button when audioOnly mode
- Add capability for sharing any direct link video
- Knocking participant name in participants list
- Add flag for controlling security options button visibility
- Fix displaying mute everyone buttons for non-moderators
- Fix notifications for phone invites
- Introduce react-native-paper
- Place picture-in-picture button on the left
- Show full participant thumbnails in tile view

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.5.0...android-sdk-3.6.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.5.0...ios-sdk-3.6.0)

# 3.5.0 (2021-04-29)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.5.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.5.0)

## Changes

### Common

- Remove old LoginDialog.js file, fixed redirection to the external auth and created actions.any.js

### Android

- Catch exception thrown when media projection is stopped
- Fix screen rotation when screen-sharing

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.4.0...android-sdk-3.5.0)

### iOS

- Fix building with Xcode 12.5
- Add ability to set CallKit options for incoming calls
- Fix leaving the meeting when screen-sharing

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.4.0...ios-sdk-3.5.0)

# 3.4.0 (2021-04-20)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.4.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.4.0)

## Changes

### Common

- Add security dialog
- Make sure immersive mode respects the fullscreen flag
- Redesign labels
- Button overflow in landscape orientation
- Implement sip invite
- Always pin screenshare to large-video if it exists
- Update the translations

### Android

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.3.0...android-sdk-3.4.0)

### iOS

- Detect orientation when screen sharing
- Fixes typo on JitsiMeetViewDelegate method
- Adds ios screensharing enabled flag
- Keyboard no longer covers message board and input

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.3.0...ios-sdk-3.4.0)

# 3.3.0 (2021-04-01)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.3.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.3.0)

## Changes

### Common

- Add fullscreen.enabled flag
- Add actions and events for the chat opening/closing
- Add feature flag for help button
- Add ToggleScreenShare event and action
- Adaptive toolbar
- Brand new in-meeting UI
- Update translations

### Android

- Add ability to localize notification actions strings
- Apply flags when launching activity from non-activity context

Relevant native dependencies:

- react-native 0.61.5
- android-jsc r245459
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.2.0...android-sdk-3.3.0)

### iOS

- N/A

Built with Xcode 12.4

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.2.0...ios-sdk-3.3.0)

# 3.2.0 (2021-03-02)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.2.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.2.0)

## Changes

### Common

- Add actions and events for the chat
- Add feature flag for help button
- Make sure the lobby enable dialog follows the theme color
- Update translations

### Android

- N/A

Relevant native dependencies:

- react-native 0.61.5
- android-jsc r245459
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.1.0...android-sdk-3.2.0)

### iOS

- Change the participantInfo completion handler reference to strong

Built with Xcode 12.4

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.1.0...ios-sdk-3.2.0)

# 3.1.0 (2021-02-05)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.1.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.1.0)

## Changes

### Common

- Add feature flags for audioMute, videoMute and overflowMenu
- Add ability to retrieve participantsInfo array
- Add ToggleScreenShare event and action.
- Implement aggressive layer suspension
- Update translations

### Android

- Add ability to disable the use of requestFocus
- Add ability to localize notification actions strings

Relevant native dependencies:

- react-native 0.61.5
- android-jsc r245459
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-3.0.0...android-sdk-3.1.0)

### iOS

- N/A

Built with Xcode 12.2

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-3.0.0...ios-sdk-3.1.0)

# 3.0.0 (2021-01-22)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-3.0.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-3.0.0)

## Changes

### Common

- New hangup, mute audio native APIs
- New participant joined left native events
- Added connection stats (long press on participant tile)
- Stop using nicknames in chat
- Updated WebRTC to M87
- Unified Amplitude handlers across web and mobile
- Stop room name generator when field is focused
- New feature flags to control tile-view, notifications, toolbox, filmstrip
- UI/UX improvements
- Update translations

### Android

- Add BroadcastService based APIs for native events / actions
- Disable the RNWebViewFileProvider
- Set stream type hardware buttons should control
- Reset audio route after audio focus was lost
- Use modern API for requesting audio focus
- Prevent crashes when destroying the Fragment
- Set compile/target SDK versions to 30

Relevant native dependencies:

- react-native 0.61.5
- android-jsc r245459
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.11.0...android-sdk-3.0.0)

### iOS

- BREAKING: SDK name changed to JitsiMeetSDK to fix a Swift compiler bug
- BREAKING: SDK is now released in XCFramework format
- Added ability to use an external CXProvider and CXCallController

Built with Xcode 12.2

**NOTE:** Due to some publishing issues this version was released as 3.0.2 in CocoaPods.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.11.0...ios-sdk-3.0.0)

# 2.11.0 (2020-11-17)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.11.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.11.0)

## Changes

### Common

- Add mute everyone / (else) capabilities
- Replace swipe options with long-press sheet in recents list
- Increase config load timeout to 10 seconds
- Prevent homograph attacks in chat
- Fix error when reloading a failed conference
- UI/UX improvements
- Update translations

### Android

- Add screen-sharing support
- Update AndroidX core library dependencies
- Fix crash when requesting permissions in certain cases
- Avoid crash when fetching calendar entries
- Update Gradle and the plugin to the latest versions
- Revert to JSC as our JS engine

Relevant native dependencies:

- react-native 0.61.5
- android-jsc r245459/
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.10.0...android-sdk-2.11.0)

### iOS

- Fix not rendering images on iOS 14

Built with Xcode 12.2

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.10.2...ios-sdk-2.11.0)

# 2.10.2 (2020-09-18)

- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.10.2)

## Changes

### iOS

Built with Xcode 12

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.10.0...ios-sdk-2.10.2)

# 2.10.0 (2020-09-15)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.10.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.10.0)

## Changes

### Common

- Add feature flag to enable / disable conference timer
- Add flag to show/hide video share button
- Add grant moderator functionality
- Add screen-sharing indicator to thumbnails
- Fix chat issues
- Fix starting native call integration multiple times
- Avoid logging error log when there are no analytics handlers
- Show lonely experience only after joining
- Tile view UI/UX improvements
- Updated translations

### Android

- Disable PiP on Android Go devices
- Bump minimum API level to 23 and target API level to 29

Relevant native dependencies:

- react-native 0.61.5
- hermes-engine 0.2.1
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.9.3...android-sdk-2.10.0)

### iOS

- Specify the correct keyboard type and content

Built with Xcode 11.4.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.9.3...ios-sdk-2.10.0)

# 2.9.3 (2020-07-22)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.9.3)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.9.3)

## Changes

### Common

- Fix overriding custom server URL

### Android

- N/A

Relevant native dependencies:

- react-native 0.61.5
- hermes-engine 0.2.1
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.9.2...android-sdk-2.9.3)

### iOS

- N/A

Built with Xcode 11.4.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.9.2...ios-sdk-2.9.3)

# 2.9.2 (2020-07-17)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.9.2)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.9.2)

## Changes

### Common

- Fix ghost participants after kicking them

### Android

- Fix crash when refreshing calendar under certain circumstances

Relevant native dependencies:

- react-native 0.61.5
- hermes-engine 0.2.1
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.9.1...android-sdk-2.9.2)

### iOS

- N/A

Built with Xcode 11.4.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.9.1...ios-sdk-2.9.2)

# 2.9.1 (2020-07-14)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.9.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.9.1)

## Changes

### Common

- Add ability to override resolution using a feature flag
- Update WebRTC engine to M84
- Add share YouTube video
- Add lobby mode
- Fix toolbox displaying in Picture-in-Picture mode
- Introduce unsafe room name warning indicator

### Android

- Add serverURL configuration for MDM/EMM environments

Relevant native dependencies:

- react-native 0.61.5
- hermes-engine 0.2.1
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.9.0...android-sdk-2.9.1)

### iOS

- N/A

Built with Xcode 11.4.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.9.0...ios-sdk-2.9.1)

# 2.9.0 (2020-05-28)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.9.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.9.0)

## Changes

### Common

- Fix room lock prompt text
- Add unsafe room name warning
- Add "toolbox.alwaysVisible" flag
- Enable custom deeplinking domain
- Add feature flag to show/hide 'Tile View' button
- Add feature flag to show/hide the 'Raise Hand' button
- Fix language detection to take region into account
- Improved internationalization

### Android

- N/A

Relevant native dependencies:

- react-native 0.61.5
- hermes-engine 0.2.1
- okhttp: 3.12.1

NOTE: Androidd got a quick follow-up 2.8.2 release fixing a botched 2.8.1.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.8.2...android-sdk-2.9.0)

### iOS

- N/A

Built with Xcode 11.4.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.8.1...ios-sdk-2.9.0)

# 2.8.1 (2020-04-29)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.8.2)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.8.1)

## Changes

### Common

- Fix on-screen keyboard overlapping dialog boxes
- Fix opening private messages dialog
- Fix detecting sysstem language
- Add new feature flags for disabling buttons

### Android

- N/A

Relevant native dependencies:

- react-native 0.61.5
- hermes-engine 0.2.1
- okhttp: 3.12.1

NOTE: Androidd got a quick follow-up 2.8.2 release fixing a botched 2.8.1.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.8.0...android-sdk-2.8.2)

### iOS

- N/A

Built with Xcode 11.4.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.8.0...ios-sdk-2.8.1)

# 2.8.0 (2020-04-21)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.8.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.8.0)

## Changes

### Common

- Add column layout to settings fields
- Use random room name generator on the welcome page
- Fix accented room name display
- Add share button to add people dialog
- Add feature-flag to disable close captions
- Improve text for room lock prompt
- Accessibility fixes
- Updated translations

### Android

- Parcel the serverURL in JitsiMeetConferenceOptions
- Disable PiP button on Android < 26

Relevant native dependencies:

- react-native 0.61.5
- hermes-engine 0.2.1
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.7.0...android-sdk-2.8.0)

### iOS

- Built with Xcode 11.4.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.7.0...ios-sdk-2.8.0)

# 2.7.0 (2020-03-25)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.7.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.7.0)

## Changes

### Common

- Add ability to eassily invite others when alone
- Refactor in-conference menu
- Updated translations

### Android

- Disable HW video decoder
- Fix crashes with AudioManager

Relevant native dependencies:

- react-native 0.61.5
- hermes-engine 0.2.1
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.6.0...android-sdk-2.7.0)

### iOS

- N/A

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.6.0...ios-sdk-2.7.0)

# 2.6.0 (2020-02-07)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.6.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.6.0)

## Changes

### Common

- Update React Native to version 0.61.5
- Add conference timer
- Fix autogenerated BOSH address, it could prevent custom deployments on a non-sstandard HTTPS port from working
- Fix not displaying Dropbox storage text

### Android

- Switch to the Hermes JavaScript engine
- Turn on HW video decoder

Relevant native dependencies:

- react-native 0.61.5
- hermes-engine 0.2.1
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.5.1...android-sdk-2.6.0)

### iOS

- Fix opening datachannels
- Fix not playing sounds on certain occassions

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.5.3...ios-sdk-2.6.0)

# 2.5.1 (2020-01-09)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.5.1)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.5.3)

## Changes

### Common

- N/A

### Android

- Handle ConnectionService failures more resiliently

Relevant native dependencies:

- react-native 0.61.3
- okhttp: 3.12.1

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/android-sdk-2.5.0...android-sdk-2.5.1)

### iOS

- Fix opening datachannels

NOTE: due to a build issue this version was released as 2.5.3 on CocoaPods.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.5.2...ios-sdk-2.5.3)

# 2.5.0 (2019-12-13)

- [Android](https://github.com/jitsi/jitsi-meet/releases/tag/android-sdk-2.5.0)
- [iOS](https://github.com/jitsi/jitsi-meet/releases/tag/ios-sdk-2.5.2)

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

NOTE: due to a build issue this version was released as 2.5.2 on CocoaPods.

[Full changelog](https://github.com/jitsi/jitsi-meet/compare/ios-sdk-2.4.2...ios-sdk-2.5.2)

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
