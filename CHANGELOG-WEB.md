# Web Changelog

Full changelogs are available in each project's release page: click on one of the releases below, click on Assets and there's the CHANGELOG. 

##  2.0.5390 (21-01-12)
- [jitsi-meet 1.0.4628](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_5390)
	- New features:
		- feat(jaas) allow tile view to be disabled
		- feat(jaas) add config for displaying participants stats and conference subject
		- Skip p2p when the participant is jigasi.
		- emit raise hand event to external API (#8312)
		- feat(analytics) unify Amplitude handlers across web and mobile
		- feat(stats) add stats for mobile
		- feat(analytics): Adds metric for SS issues.
		- feat(ios) rename SDK target to JitsiMeetSDK
		- Update spanish translation (#8023)
		- feat(ios) added ability to use an external CXProvider and CXCallController
		- feat(tile-view) optimize for less margins
		- Update the Czech translation (#8133)
		- feat(analytics): Add tenant.
		- Exposes a method for checking is remote track received and played/testing. (#8186)
		- Add option to force pc to use turn relay candidates. Helps with testing turn relay cases.
		- feat(ConferenceTimer): Add config option to hide.
		- Remove the min-participants config.
		- feat(rn) switch to XCFramework and WebRTC M87
		- Makes it possible to hide the "Save Logs" link. (#8143)
		- Include "Latvian" in the languages list (#8129)
		- feat(avatar) add ability to customize Gravatar base URL
		- Skips the default tile view when jibri is loading.
		- Drops filmStripOnly mode. (#8074)
		- feat(rn) add mute everyone / (else) capabilities
		- feat(external_api) drop support for noSSL option
		- feat(BrowserCapabilities) drop supportsVideo
		- Drop enableUserRolesBasedOnToken and isGuest.
		- Show cc button for ongoing transcribed meetings for guests
		- Drop lockRoomGuestEnabled.
		- Drop HIDE_KICK_BUTTON_FOR_GUESTS setting.
		- Drop buttons tooltips specific to guests.
		- Profile tab does not depend on isGuest.
		- Drops SHOW_JITSI_WATERMARK_FOR_GUESTS and SHOW_WATERMARK_FOR_GUESTS.
		- feat(welcome_page): Redesign welcome page
		- feat(android) add screen-sharing support
		- feat(misc) automatically assign feature-request tag to issues
		- Reduce pings and adds xmpp ping config.
		- feat(prejoin): Add name from jwt to prejoin screen
		- feat(vpaas): Track vpaas conference join
		- feat(iFrame): Add recording options for RTMP streaming. Add methods for start/stop recording in addition to the commands that we already have.
		- feat(pwa) update TWA Android project
		- feat(pwa) do not display chrome extension banner for TWA
		- feat(pwa) add fastlane integration for building TWA APK
		- feat(pwa) update mask icon
		- feat(presenter): apply 'text' contentHint
		- feat(pwa) update generated Android project
		- feat(pwa) move twa manifest to twa/
		- feat(pwa) update twa manifest with new (old) colors and manifest path
		- feat(pwa) use current icons
		- feat(pwa) add TWA generated files
		- feat(mobile) add splash screen
		- feat(prejoin): handle disabled precall test.

	- Fixes:
		- fix(JitsiStreamPresenterEffect): frozen on Safari
		- fix(filmstrip) fix button not considering interface config settings
		- fix(ios) fix drag handle not rendering with latest react-native-svg
		- fix(ios) fix crash on startup on iOS 11
		- fix(setAudioOutputDeviceId): check if supported
		- Process pre-existing participants properties.
		- Fixes showing phone icon for jigasi participants.
		- fixed admin check for token verification
		- fix(jitsi-meet-web-config.postinst) allow cert and key pre-selection (#8319)
		- fix(lang) update zhCN translation
		- fix(lang) update German translation
		- fix(tile-view) allow watermark to be covered
		- fix(tile-view) reduce margins, take 2
		- fix(ios,fastlane) adjust scheme name after rename
		- fix(android) avoid crashes if view is null
		- fix(jaas) update recording label and hide option for jaas users
		- fix(password): Fix add password button on Safari
		- fix(branding): Use config url for dynamic branding
		- fix(script) add commits list to update LJM message
		- Skip sending multiple times disco-info to jicofo.
		- fix(welcome-page) fix .insecure-room-name-warning margin
		- fix(main-ko) add keyboardShortcuts videoQuality (#8264)
		- fix(main-ko.json) Update some korean spelling & words (#8253)
		- #8095 (#8101)
		- fix(remote-control) skip on mobile
		- fix(ios) fix joining a meeting when the app was closed
		- fix(conference.js): 2 tracks of the same media type
		- Skip sending unnecessary signalling for raise hand.
		- fix(LoginDialog) added missing double quotes
		- Start p2p only when we have received all presences.
		- fix(video):Always show avatar if video is inactive
		- the user placeholder translation issue #8219 (#8233)
		- Fixes VP9 support on Chrome. chore(deps) lib-jitsi-meet@latest
		- Fixes detecting websocket disconnect by using xmpp pings.
		- fix(lang) fix a few typos in Italian translation
		- fix(config) remove openBridgeChannel
		- fix(tracks): Do not add a second audio track.
		- fix(lang) typo
		- fix(android) set stream type hardware buttons should control
		- fix(android) reset audio route after audio focus was lost
		- fix(android) use modern API for requesting audio focus
		- fix(lang) update Italian translation
		- fix(android) disables the RNWebViewFileProvider
		- fix(TPC): Do not scale down desktop track in p2p/non-simulcast cases. chore(deps) lib-jitsi-meet@latest
		- fix(deps) update logger
		- fix(connection-status): action
		- fix(avatar) revert back to defaulting to Gravatar
		- fix(lastN): select screenshare endpoint always when auto pinning. When trying to auto pin screenshare, always select the endpoint even though it happens to be the large video participant in redux. The auto pin screenshare logic kicks in after the track is added.  If the screenshare endpoint is not among the forwarded endpoints from the bridge, it needs to be selected again.
		- fix(lastN): Do not override channelLastN value. If limitLastN values are specified and channelLastN < limitLastN, configure channelLastN on the conference.
		- Fixes 404 page link when base is used.
		- fix(UI): Add method for returning the video type of remote participants. This is needed for the torture clients to determine the video type for the remote participants when testing desktop share.
		- fix(jaas) replace only the first slash in a pathname
		- fix(screenshare): do not reconfigure encodings for simulcast SS chore(deps) lib-jitsi-meet@latest
		- fix(chat) stop using nicknames
		- get subdomain function
		- fix(Toolbox) Maintain overflow button visible at all times
		- fix(welcome_page): Fix background image url path
		- fix(safari): Ensure simulcast stream resolutions don't change. Safari 14.1 has a bug where it returns 720p for every simulcast stream when RTCRtpSender.getParameters is called even though the stream resolutions are different. By using the encodings config used when source was added, on every RTCRtpSender.setParameters call, we ensure that simulcast stream resolutions don't change. chore(deps) lib-jitsi-meet@latest
		- fix(welcome_page): Add max width to welcome card
		- fix(vpaas): Make user media permission message more generic
		- fix(lang) update Japanese translations
		- Fix module allowners and moderated rooms.
		- fix(password) set input type to "password"
		- fix(welcome_page): Update header to latest design & use generic key name
		- fix(lang) update Russian translation
		- fix(build) fix webpack-dev-server on Windows
		- fix(external_api) replace special chars in roomName before constructing URL
		- fix(lang) update Italian translation
		- fix(lang) update Italian translation
		- fix(lang) update German translation
		- fix(lang) update for Occitan
		- fix(lang) improve Spanish translations
		- fix(lang) fix rendering accented characters in Italian
		- fix(welcome_page): Fix mobile version
		- fix(CalendarList): calendar.svg path.
		- fix(screenshare): Fixes for the blurry desktop share issues. Do not resize the desktop share to 720p by default when the desktop track resolution is higher than 720p. This is causing bluriness when presenter is turned on. Remove the 'detail' contentHint setting for the desktop+presenter canvas stream as it forcing chrome to send only 5 fps stream for high resolution desktop tracks. Move the desktop resizing logic behind a config.js option - videoQuality.resizeDesktopForPresenter.
		- Optimizes hot paths in prosody modules, string comparisons.
		- Hide copy password if it is not available. Fixes #7783
		- Show livestream button only for moderators.
		- fix(jaas) fix double slash for branded invite urls
		- Prosody modules - drop unused and duplicate code and drop chatty debug statements (#8027)
		- fix(rn, screen-sharing) don't render own screen-share in large view
		- fix(conference) remove no longer needed code
		- Avoids storing lobby room instance in the main room object.
		- fix(lang): update fr translation
		- fix(lang) update ptBR translation
		- fix(vpaas) fix invite url flicker for jaas users
		- fix(StatusIndicators): Improve isScreenSharing check
		- fix(logging): Add more details to onerror and onunhandledrejection errors.
		- fix(screenshare): bring back 'x-google-flag:conference' flag in remote description for SS. chore(deps) lib-jitsi-meet@latest
		- fix(video-quality): set lastN to 1 when screenshare is added to call in audio-only mode. This fixes an issue where lastN is not bumped to 1 on an audio-only client when a screenshare source is added to the call.
		- fix(deviceChange):Dont create video track if muted
		- fix(conference): start muted values on initial GUM
		- fix(iFrame): capturScreenshot - check if the remote participant has a track attached. Participants that join video muted do not have video tracks attached. Fixes https://github.com/jitsi/jitsi-meet/issues/7942.
		- fix(pwa) move manifest to the root
		- fix(pwa) remove no longer used file
		- fix(xmpp): Update previd value when trying to resume connection. lib-jitsi-meet@latest
		- fix(android) fix runtime WebRTC issue
		- fix(prejoin): Fix moving content when device status bar is toggled
		- fix(pwa) fix PWA worker script origin
		- fix(pwa) fix auto-generated TWA icons
		- fix(pwa) fix loading the service worker
		- speakerstats_component, attempt to index (a nil value)
		- fix(thumbnail): cleanup unused hover properties.
		- fix(avatar) remove participant's "avatarID"
		- fix(pwa) move logic for registering pwa worker
		- fix(pwa) remove window.load event handler for pwa registrator
		- fix(flow): ignore contentHint
		- fix(pwa) bypass loading in electron. ensure same origin with registrator
		- fix(UI): Do not re-compute the container width when chat window is closed. Since the external API now sets preferredWidth/preferredHeight for resizing the large video, we don't need to add chat width to the computed window width when the chat window is closed. Fixes https://github.com/jitsi/jitsi-meet/issues/7889
		- fix(pwa) improve upon pwa specs
		- fix(avatars) refactor preloading
		- fix(rn) use a RN-friendly URL polyfill
		- fix(rejoin) fix adding track parameters to rejoin URL
		- fix(prejoin) guard case for locationUrl being falsy in prejoin screen
		- fix(deps) update react-native to fix iOS 14 icons

	- Translation updates:
		- Updating and uniforming italian translation (#8288)
		- update French translation (#7725)
		- * languages-ka.json
		- Update Arabic translation
		- * lang:New translation malayalam(ml-in)


	lib-jitsi-meet
	- New features:
		- Skip p2p when the participant is jigasi.
		- feat(stats) migrate RN to new stats
		- Add option to force pc to use turn relay candidates.
		- Remove the min-participants config. (#1418)
		- Log the jvb version. (#1410)
		- feat(BrowserCapabilities) drop supportsVideo
		- feat(RTC) bump minimum supported Chromium version to 72
		- Reduce pings and adds xmpp ping config (#1389)
		- feat(rn) support getDisplayMedia
		- feat(twa) add TWA check function
		- feat(e2ee) log Olm version

	- Fixes:
		- fix(stats) fix parsing codec in new stats
		- Skip sending multiple times disco-info to jicofo.
		- Maybe start p2p only when we have received all presences.
		- Implement the encodings workaround only on Safari. Explicitly check if all the encodings report the same scaleResolutionDownBy value before trying to ensure they match the expected values. This makes Chrome VP9 work again.
		- Fixes ping options usage.
		- fix(XMPP): Get the correct domain for XMPP ping.
		- Updates ping logic around detecting xmpp activity.
		- add `getParticipants` to JitsiConference docs
		- Always query the main domain for features. Fixes jitsi/jitsi-meet#8173 (#1428)
		- fix(TPC): Do not scale down desktop track in p2p mdoe.
		- fix(deps) update logger to 1.0.0
		- fix(last-n): Do not let Jicofo initialize last-n for the whole conference. The plan is to move the lastNLimits logic to bridge. The clients will be able to override(lower) the bridge limits through the bridge channel only. Also, this lets us configure last-n per receiver and not set the last-n value for the whole conference the way Jicofo sets it currently.
		- fix(TPC): do not update encodings for simulcast desktop tracks. Fixes https://github.com/jitsi/jitsi-meet/issues/8094.
		- typos
		- typos on comments
		- fix(TPC): Do not update encodings for non-simulcast sources.
		- fix(TPC): Ensure encodings resolutions match configured values. On every call to RTCRtpSender.setParameters(), ensure that the resolution configured for the encoding matches that of the value configured on the RTCRtpSender when the source was added to the peerconnection. This should prevent us from overriding the default values if the browser returns erroneous values when RTCRtpSender.getParameters is used for getting the encodings info. This fixes the issue on recent versions of Safari where the 'scaleResolutionDownBy' value comes back as 1 for all encodings even though the encoding resolution is different from the stream capture resolution.
		- fix(video-quality): Fix p2p desktop share quality. In p2p mode, 'scaleResolutionDownBy' is used for downscaling a stream when needed, i.e. when the user receives a receive constraint of 360p because the other participant is in tile view. When desktop share is started, the encoding config has to be scaled back up so that the other participant starts receiving HD resolution for the share as desktop shares are autopinned. Therefore, encodings have to enabled/disabled for desktop shares as well. Earlier it was done only for camera tracks.
		- fix(stun) update default list of STUN servers
		- fix(rn) release audioVideo stream after creating new MediaStream
		- fix(audio-recorder) remove no longer needed code
		- fix(RTC): Fix log formatting
		- fix(video-quality): do not disable encodings when sender constraints are not configured on the conference. Fixes https://github.com/jitsi/lib-jitsi-meet/issues/1333 in applications that use lib-jitsi-meet and do not have layer suspension enabled.
		- Add the x-google-conference flag on RD when screensharing. Add the conference flag back since the bridge is able to handle the case where more than 1 temporal layers are received even when only 1 ssrc is signaled.
		- fix(xmpp): Update previd value when trying to resume connection.
		- fix(JingleSession) log initialization error

- [jicofo 1.0-690](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_5390)
	- New features:
		- Adds conference property in the presence for terminate-restart. (#658)
		- Add config to enable/disable Octo. Remove client-side config. (#640)
		- Move minParticipants to local config (not configured by the client). (#638)

	- Fixes:
		- Don't treat Jibri busy response as transient error (#659)
		- Fixes sending last seen presence. (#662)
		- Skip sending duplicate identical presences.
		- Fix attempt to cast.
		- Fix the REST interface. (#653)
		- Do not start the nonexistent VersionActivator bundle. (#637)
		- reading the "enabled" property from legacy config. (#628)
		- Fixes checkstyle (#627)
		- Fix stat names (put ice_failed and request_restart under participant_notifications as intended). (#618)
		- Remove non-operational bridges and add stats. (#614)
		- Do not immediately move conferences away (#612)

- [jitsi-videobridge 2.1-416-g2f43d1b4](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_5390)
	- New features:
		- bump jmt: stats improvements. (#1534)
		- Announce version in ServerHello (optionally). (#1528)
		- Add oversending time stat (#1514)
		- Increase bucket size for rate trackers (decrease memory usage). (#1460)

	- Fixes:
		- sending an "active=true" message when an endpoint is connects after being recreated. (#1538)
		- Included the bridge version in ServerHello sent over WS. (#1536)
		- Suppress sending SenderVideoConstraints(height=0) (#1533)
		- Fix getting mediaSource for OctoEndpoint. (#1531)
		- Fix serializing when version==null. (#1529)
		- Fix raw type warnings (reduce use of generics, use List instead of array). (#1512)
		- Adapt to new Jetty version deprecations; fix compilation warnings. (#1511)
		- Avoid IllegalStateException when StatsCollector is disabled (#1507)
		- Fix failures to re-login to XMPP and reload config (jicoco) (#1501)
		- Fix resetting lastPresenceSent (jicoco). (#1493)
		- move jvb ice4j overrides to application.conf so they are respected (#1490)

##  2.0.5142 (20-10-14)
- [jitsi-meet 1.0.4466](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_5142)
	- New features:
		- feat(pwa) add pwa specifics
		- feat(prejoin) show connection status in exported prejoin screen
		- feat(prejoin) improve ux
		- Adds more debug information in the GSM bars popover (#7627)
		- feat(external-local-storage): support
		- feat(android) revert to JSC as our JS engine
		- Enable bridge websockets by default for new installs (#7781)
		- feat(iFrame): Add method for pinning a participant on stage view

	- Fixes:
		- fix(vpaas): Count endpoint only when there are 2 or more participants
		- fix(VideoLayout) make thumbnail iteration more resilient
		- fix(prejoin) allow libs loaded in prejoin.html to be cached
		- fix(build) increase external_api bundle size
		- fix(ios) fix not rendering images on iOS 14
		- fix(video-quality-dialog): Initial value.
		- fix(native) add missing function
		- Show focus indicator only when navigating via keyboard
		- fix(video-quality): Add the ability to request Ultra HD resolutions Change the preferredVideoQuality and maxReceiverVideoQuality values to Ultra HD resolutions. The requested resolution can be as high as 4K to facilitate VPaaS customers to request 4K. The sender video resolution will always max out at the value specified in the video constraints from config.js settings.
		- fix(misc) update update-ljm script commit message
		- fix(config) drop useStunTurn
		- fix(android) - separates the invocation of the gradle tasks. It was noticed on some configurations that the publish task was executed before assembleRelease finished
		- fix(android) - adds the import for the VersionName, since on some configurations it is not automatically imported
		- Makes the code more defensive to prevent an error. (#7837)
		- fix(android) excludes hermes related libs from the apk
		- fix(e2ee) handle Olm initialization error
		- fix(lang) update Slovak translation
		- fix(lang) update turkish translation
		- fix(lang) add basic support for serbian
		- fix(rn,config) increase config load timeout to 10 seconds
		- fix(android) increase gradle JVM heap size
		- fix(presenter): Do not change the video mute state on presenter mute. This fixes the issue where the local preview appears muted when presenter camera is turned on and then off while screenshare is in progress.
		- fix(crashlytics) add missing dependency
		- fix(android) update Gradle and the plugin to the latest versions
		- fix(lang) update French translation
		- fix(lang) typo in German translation
		- fix(chat) prevent homograph attacks
		- fix(analytics) clarify log line
		- fix(analytics) make handler loading more resilient
		- fix(analytics) make sure rtcstats is not enabled on mobile
		- fix(analytics) avoid Amplitude initialization failure on mobile
		- fix(vpaas) hide embed meeting for vpaas users
		- fix(vpaas) fix vpaas redirect
		- fix(callstats): Use callStatsThreshold for % of users instead of conferences


	lib-jitsi-meet
	- New features:
		- feat(precallTest):disable if callstats is disabled
		- feat(e2ee) publish olm id key in presence
		- feat(e2ee) emit PARTICIPANT_E2EE_CHANNEL_READY also for the initiator
		- feat(xmpp) drop the useStunTurn option
		- feat(RTC): force cursor of ScreenObtainer to be always captured
		- Adds a method that finds the SSRC of a JitsiTrack (#1338)
		- feat(external-storage): Support.
		- feat(video-quality): Add a log message for max. height message received from JVB
		- feat(TPC): add p2p rtcstats meta info to tpc (#1331)

	- Fixes:
		- fix(TPC): maxBitratesVideo break screenshare
		- fix(e2ee) add more documentation
		- fix(updateDevices): On enumerateDevices.
		- fix(audio-levels): Reset audio level to 0 when remote user is muted. When using getSynchornizationSources on the audio receiver to gather audio levels for remote tracks, browser reports last known audio levels even when the remote user is audio muted, we need to reset the value to zero here so that the audio levels are cleared.
		- fix(safari): Remove old remote tracks when a new track is received for an endpoint. On Safari, MediaStream.onremovetrack is not fired when a remote desciption with a removed MSID is applied. As a result, new remote tracks for the same endpoint are not created causing issues where the video is not updated on Safari. Also, make sure local tracks on pc are updated when devices are changed while the user is in muted state.
		- Disable RTX on Firefox. Disable RTX on FF as we are seeing video freezes on FF80 and later - https://bugzilla.mozilla.org/show_bug.cgi?id=1668028
		- disable google conference flag for screenshare
		- fixed incorrect kick() with kickParticipant() in doc/API.md
		- fix(karma): After adding 2nd webpack configuration
		- fix(callstats): Go back to enabling callstats on % of users rather than conferences

- [jicofo 1.0-644](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_5142)
	- New features:

	- Fixes:
		- Handle Jibri errors on initial request (#603)

- [jitsi-videobridge 2.1-376-g9f12bfe2](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_5142)
	- New features:
		- Port AWS harvester config (update ice4j). (#1486)
		- Enable bridge websockets by default for new installs (#1462)
		- Add loss stats based on total number of packets. (#1455)

	- Fixes:
		- Fix PingManager being disabled after a temporary failure (jicoco)
		- Increase the T3 threshold to 1500. (#1485)
		- publishing stats to callstats, add loss stats. (#1480)
		- JMT bump: fix double buffer return; link srtp with openssl 1.1.x. (#1477)
		- NullPointerException if conferenceName is not defined.
		- always assume 3 temporal layers (#1472)

##  2.0.5076 (20-09-23)
- [jitsi-meet 1.0.4428](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_5076)
	- Fixes:
		- fix(mediaDeviceHelper): fix typo in dispatch
		- fix(LargeVideoManager): large video resizing
		- fix(iframe): Use largeVideo video element for screenshot. Get the existing HTMLVideoElement for large video instead of creating a new video element for capturing the screenshot. This should prevent the video player from getting displayed on mobile Safari.

##  2.0.5073 (20-09-23)
- [jitsi-meet 1.0.4425](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_5073)
	- New features:
		- Throttle out call attempts to the max number per minute (#7742)
		- feat(stats): Add the ability to enable callStats for certain % of confs
		- feat(iFrame): Add a method for capturing screenshot of the large video (#7717)
		- feat(iFrame): Add a method for resizing large video container from iFrame
		- feat(iFrame): add a method for getting the participants info
		- feat(loggin) forward logs to external api
		- feat(external_api): Add method for displaying participant on large video
		- feat(external_api): Add cmd for selecting a user to be displayed in large video
		- feat(video-quality): add iframe event and getter.
		- feat(video-quality): persist.
		- Allows jvb to control DTLS/SRTP protection profile. (#7626)
		- feat(vpaas) disable deeplinking page
		- Whitelist option to hide lobby button.
		- Adds interface config to hide lobby button. (#7619)
		- Automatically copy invite URL after creating a room (#7581)
		- feat(vpaas): Add endpoint counter & remove branding on vpaas meetings

	- Fixes:
		- fix(UI): Re-compute large-video width only once if the chat window is open. Deduct the chat window width from large-video width only once if we keep toggling between stage view and grid view while the chat window is open.
		- fix(build) reduce bundle size by about 700K
		- fix(iFrame): Make resizeLargeVideo only available on web
		- fix(ios,version) versions must match
		- fix(SmallVideo) screen-sharing indicator
		- fix(config) remove unused options (#7723)
		- fix(branding): Fix dynamic logo display
		- fix(ios) add local network usage description for iOS 14
		- fix(config) remove no longer valid option
		- fix(android,calendar) avoid crash
		- fix(background-blur) refactor to improve performance
		- fix(embed): remove legacy attribute from embed meeting code
		- Fix ws reconnect piling up previd param.
		- fix(embed) fix embed meeting code
		- Updates docs and verification to halt joining process.
		- fix(ifarme-api): set-video-quality to use redux.
		- fix(RN): crash on undefined state['features/dynamic-branding']
		- enable token_verification during installation of jitsi-meet-tokens (#7630)
		- keep plugin_paths while removing jitsi-meet-tokens (#7632)
		- disable token_verification while removing jitsi-meet-tokens (#7631)
		- added libssl1.0-dev to the dependencies of jitsi-meet-tokens (#7629)
		- jitsi-meet-tokens - the first installation check (#7618)
		- fix(close3): Add close3.js
		- fix(vpaas): Fix billing counter auth (#7595)
		- fix(vpaas): Fix tenant typo
		- fix(iframe-api): setDevice.
		- fix(settings): store url display name and email.

	- Translation updates:
		- fix Dutch dialog.kickTitle
		- update Korean translation
		- update French translation
		- update kabyle translations


	lib-jitsi-meet
	- New features:
		- feat(stats): Add the ability to enable callStats only on a certain % of conferences
		- Allows jvb to control DTLS/SRTP protection profile. (#1300)
		- feat(xmpp): resume the connection when online
		- detect broken XMPP WebSocket using ping
		- feat(video-quality): Implement max bitrates for video on p2p sessions Calculate the bitrate based on the sender video constraint applied on the track and the bitrates specified for different resolutions.
		- send conference.left analytics event
		- feat(chrome|safari): stop the video for maxFrameHeight 0
		- restart Jingle session on ICE failed

	- Fixes:
		- Fix ws reconnect piling up previd param.
		- Do not negotiate H264 when E2EE is enabled
		- fix(video-quality): make sure the LD stream is enabled even when requested resolution is lower This should fix the case when camera is started with 1080p and LD simulcast stream's resolution is 270p but the requested resolution is 180p.
		- update token doc for tenant details, new prosody (#1316)
		- fix(RTCUtils): system audio share multiple desktop
		- fix(RTCUtils): Cannot read property 'find' of undefined
		- Only advertise opus-red if the browser supports it.
		- fix(video-quality): Fix a typo, max. bitrates are always applied on unified plan clients
		- fix(XmppConnection.connected): check the underlying websocket
		- fix(XmppConnection): sendIQ2 pass the 'timeout'
		- fix(tests): source maps for Karma
		- fix(xmpp/Caps): features for a user without caps support
		- fix(TCPUtils): set 'sendrecv' only for the local track
		- crash in Safari on unmute
		- Scale down localVideo which is already smaller than requested resolution

- [jicofo 1.0-636](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_5073)
	- New features:
		- Passes room bare jid to conference IQ. (#585)

	- Fixes:
		- Escape the display name. (#593)

- [jitsi-videobridge 2.1-351-g0bfaac1c](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_5073)
	- New features:
		- Avoid benchmarking srtp engines, and make srtp engine configurable. (#1457)
		- Support GCM for DTLS/SRTP. (#1450)
		- Adds an option to pass extra label for the version string (#1437)
		- Support for RED streams. (#1401)
		- Updates jitsi-stats intorducing SiteID.  (#1413)
		- Optimize bwe calculations (#1405)

	- Fixes:
		- minor followup improvements to bandwidth probing fix (#1449)
		- don't over-send bandwidth probing, and send bandwidth probing even when no sources can be sent. (#1447)
		- Fix serialization of the "last-n endpoints" message. (#1446)
		- Fix redirects for /colibri/debug/stats/*. (#1424)
		- JMT update: enumerate encodings, not layers, in MediaStreamSources debug. (#1431)
		- jvb overloaded state stat string (#1428)
		- Updates log messages around dominant speaker and sctp.
		- Fixes #1412 NoClassDefFoundError JdkDeserializers

##  2.0.4966 (22-09-01)
- [jitsi-meet 1.0.4370](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_4966)
	- New features:
		- feat(prejoin): Show warning if audio device does not receive data
		- feat(branding) allow invite links to be branded
		- configurable quality levels for video height
		- feat(prejoin): Add precall connection quality indicator
		- feat(prejoin) show error when trying to join and name is required
		- feat(close3): Move readyToClose flow to the close page
		- jibri queue clear asap cache for token util on config reload
		- token util better logging for timeouts, verification
		- feat(Watermarks): Add deafault logo prop.
		- support updating accepted issuer/aud for token lib
		- feat(prejoin): Hide invite link
		- jwt pubkey cache inside object
		- feat(welcome): Add variables.
		- default value for jibri queue region
		- validate keys at specific URL for jibri queue Provide region value in POST to jibri-queue service
		- feat(video-quality): Impose max-bitrates on video sender based on videoQuality settings (#7467)
		- feat(video quality): add maxFullResolutionParticipants (#7403)
		- feat(config): add last N limit mapping (#7422)
		- auto tile view
		- Updates @atlaskit/flag to use the testId prop for integration tests.
		- Adds id to the notifications and buttons so we can check for them in the integration tests.
		- Changes security dialog button to toggle dialog.
		- Adds id to the notifications so we can check for them in the integration tests.
		- feat(embed) implement embed meeting feature
		- feat(blur): terminate blur web worker when disabled (#7347)
		- proper outbound iq handler for REST requests
		- feat(prejoin): Add settings options for prejoin page
		- feat(chat): Make chat push content to the side in tile view
		- feat(chat): Make chat push content to the side in large view
		- jibri queue authorization header handler
		- feat(StateListenerRegistry): add 'deepEquals' option
		- add test hint for grant moderator availability
		- prosody: add http handler for jibri queue

	- Fixes:
		- fix(prejoin): Make avatar resizable
		- syntax error
		- fix(subject): set to ' ' after settings change.
		- call after timeout
		- fix(prejoin): Fix join without audio
		- fix(prejoin) remove version parameter
		- Fixes #7514 when promoting new moderator and lobby is enabled.
		- token util keyurl definition move to above callback definition
		- prosody token util handles race on timeout gracefully
		- prosody jibri queue component reloads configuration
		- jibri-queue module log improvements
		- Fixes uncaught exception on malformed jwt.
		- add flag to control whether to check room claim in JWT validation jibri queue component stop checking room validation in token Jibri queue component debug output when bad token is found
		- fix(prejoin) fix css loading path
		- prosody: output string for time and position in jibri queue
		- prosody: comment on destroy_request
		- prosody: destroy_request check
		- prosody: room validation on jibri-queue
		- fix(prejoin): Auto focus display name input
		- fix(last-n-limits): crash on undefined
		- lint error
		- Send SS stopped analytics event when SS was started in video mute state
		- Adds display name to notifications about lobby operations.
		- Fixes syncing state about lobby in security dialog.
		- no new msg notifications after opening chat modal  [NATIVE]
		- fix(prejoin) hide skip prejoin for exposed app
		- fix(prejoin) fix libs path
		- use correct URL paths for jibri queue service
		- use consistent moderator semantics
		- rename disco info component to correct name FIX: reply to iq only on successful reply from queue server
		- prosody jibri queue handle iq properly
		- better URL handler for jibri queue events

	- Translation updates:
		- updated Japanese translation
		- update French translation
		- update Russian translation
		- update brazilian portuguese translation
		- update Czech translation
		- update German translation
		- fix typo
		- add missing kabyle language
		- update/fix Polish translation, add missing fields in main-pl.json (#7395)
		- updated Polish translations


	lib-jitsi-meet
	- New features:
		- Apply max bitrates on video sender (#1275)
		- PerformanceObserverStats initial commit Add a performance stat around long tasks. Chrome supports PerformanceObserver API that lets us register for long tasks event. Any task that takes longer than 50ms is considered a long task.
		- feat(prejoin): Expose method to make a precall test

	- Fixes:
		- Fixes setting non moderators to members when lobby is enabled.
		- fix(video-quality): add missing simulcast stream constraints When the client starts video muted and the track is later added, make sure we construct the simulcasr stream constraints then.
		- fix(video-quality): Get downsampled video for p2p case When the video sender constraint changes in the p2p case when the remote user switches between stage/tile view, get a downsampled video of the original 720p stream instead of requesting the camera for a new stream with the lower resolution. Fixes https://github.com/jitsi/jitsi-meet/issues/7267
		- fix(video-quality): add a check for local video track before applying max bitrates
		- Fix unit tests for PerformanceObserverStats
		- Scale remote audio levels reported on receiver to getStats levels The audio levels reported on the audio receivers are lower when compared to the value reported by getStats. Values reported by getStats on chrome do not follow the the spec and since we have combination of clients using both getStats and getSynchronizationSources, lets stick to one scale to make them look uniform. Also, the receivers seem to be reporting audio level for a little bit after the remote user has muted. Make sure the track is unmuted before setting the audio level on the track.
		- Clears Lobby room instance and resets joined flag.
		- Removes unused event.
		- fix(StropheLastSuccess): refresh the timestamp in connected
		- Fix filtering out non TLS TURN servers.
		- fix(JitsiConference): skip participant kicked event for kicker
		- let camera pick the best aspect ratio when applying sender video contraints

- [jicofo 1.0-626](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_4966)
	- New features:
		- advertise support for session restart

	- Fixes:

- [jitsi-videobridge 2.1-304-g8488f77d](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_4966)
	- New features:
		- feat(systemd): restart jvb service automatically (#1354)

	- Fixes:
		- Fix the json format in debug output. (#1355)

Full changelogs are available in each project's release page: click on one of the releases below, click on Assets and there's the CHANGELOG. 

##  4627 (2020-05-26)

- [Jitsi Meet 1.0.4127](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_4627)
- [Jicofo 1.0-589](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_4627)
- [Jitis Videobridge 2.1-202-g5f9377b9](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_4627)

##  4548 (2020-05-01)

- [Jitsi Meet 1.0.4074](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_4548)
- [Jicofo 1.0-567](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_4548)
- [Jitis Videobridge 2.1-197-g38256192](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_4548)

##  4546 (2020-05-01)

- [Jitsi Meet 1.0.4073](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_4546)
- [Jicofo 1.0-566](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_4546)
- [Jitis Videobridge 2.1-197](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_4546)

##  4468 (2020-04-17)

- [Jitsi Meet 1.0.4025](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_4468)
- [Jicofo 1.0-549](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_4468)
- [Jitis Videobridge 2.1-183](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_4468)


##  4416 (2020-04-10)

- [Jitsi Meet 1.0.3992](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_4416)
- [Jicofo 1.0-544](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_4416)
- [Jitis Videobridge 4416 (?)](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_4416)


## 4384 (2020-04-03)

- [Jitsi Meet 1.0.3969](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_4384)
- [Jicofo 1.0-541](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_4384)
- [Jitis Videobridge 2.1-164](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_4384)


## 4376 (2020-04-02)

- [Jitsi Meet 1.0.3962](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_4376)
- [Jicofo 1.0-541](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_4376)
- [Jitis Videobridge 2.1-163](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_4376)


## 4335 (2020-04-01)

- [Jitsi Meet 1.0.3928](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_4335)
- [Jicofo 1.0-539](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_4335)
- [Jitis Videobridge 2.1-157](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_4335)


## 4101 (2019-11-26)

- [Jitsi Meet](https://github.com/jitsi/jitsi-meet/releases/tag/stable/jitsi-meet_4101)
- [Jicofo](https://github.com/jitsi/jicofo/releases/tag/stable/jitsi-meet_4101)
- [Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable/jitsi-meet_4101)


## 3936 (2019-08-20)

- [Jitsi Meet](https://github.com/jitsi/jitsi-meet/releases/tag/stable/jitsi-meet_3936)
- [Jicofo](https://github.com/jitsi/jicofo/releases/tag/stable/jitsi-meet_3936)
- [Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable/jitsi-meet_3936)


## 3734 (2019-05-10)

- [Jitsi Meet](https://github.com/jitsi/jitsi-meet/releases/tag/stable/jitsi-meet_3734)
- [Jicofo](https://github.com/jitsi/jicofo/releases/tag/stable/jitsi-meet_3734)
- [Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable/jitsi-meet_3734)
