# Web Changelog

Full changelogs are available in each project's release page: click on one of the releases below, click on Assets and there's the CHANGELOG. 

##  2.0.5076 (20-09-23)
- [jitsi-meet 1.0.4428](https://github.com/jitsi/jitsi-meet/releases/tag/stable%2Fjitsi-meet_5076)
	- New features:

	- Fixes:
		- fix(mediaDeviceHelper): fix typo in dispatch
		- fix(LargeVideoManager): large video resizing
		- fix(iframe): Use largeVideo video element for screenshot. Get the existing HTMLVideoElement for large video instead of creating a new video element for capturing the screenshot. This should prevent the video player from getting displayed on mobile Safari.


	lib-jitsi-meet
	- New features:

	- Fixes:

- [jicofo 1.0-636](https://github.com/jitsi/jicofo/releases/tag/stable%2Fjitsi-meet_5076)
	- New features:

	- Fixes:

- [jitsi-videobridge 2.1-351-g0bfaac1c](https://github.com/jitsi/jitsi-videobridge/releases/tag/stable%2Fjitsi-meet_5076)
	- New features:

	- Fixes:

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
