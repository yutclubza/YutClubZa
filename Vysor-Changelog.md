1.8.4
Update adb binaries
Fix crash bug related to key events in Android app

1.8.3
Custom colors on title and nav bar
Remove alipay option (was no longer supported)
Clean up purchase text on main page
Update adb


1.8.1
Don't use appspot urls
Uninstall Vysor prior to install

1.8.0
Add custom title bar

1.7.9
Android O fixes

1.7.8
Management URLs

1.7.7
Make Vysor work on Android O
Update adb binaries
Fix status window updates when installing and connecting

1.7.6
Vysor Server fixes

1.7.5
Vysor Server fixes on standalone apps

1.7.4
Fix Vysor Server UI issues

1.7.3
Update adb binary and built in adb to latest version
Stripe and Paypal licenses now remain cached longer

1.7.2
Display Settings warning

1.7.1
Vysor Share fixes

1.7.0
Fix black screen issue in Chrome 56

1.6.9
Vysor wireless improvements
License fixes for credit card purchases when the email has dots in them

1.6.8
Fix web video stream bugs

1.6.6
Fix bug report bug
Fix license manager retrieve license bug

1.6.5
Fixes around USB authorization and wireless

1.6.4
More Vysor startup options
Performance improvements when there's dozens of devices connected
Automatic connection code has been improved, and will only start if the device is authorized
More reconnect options on wifi disconnect

1.6.3
Fix bug where Vysor would spam registration update web requests when using Vysor Share

1.6.1
International Keyboard fixes
Enter key behavior fixes

1.5.8
Fix bug where login option was showing even when logged in
Further license quota fixes (offline/desktop scenarios)

1.5.7
Pressing enter now performs the default action (send text, etc)
Tweak when license fallback check is used to reduce quota usage
Android roundIcon for Pixel

1.5.6
Fix international keyboard setting not saving
Fix connection status text not being updated in some cases

1.5.5
Fix broken arrow key bindings (may require a key binding reset)

1.5.4
Provide a toast that notifies the user than an Advertisement is coming, so it is not a surprise.

1.5.3
Fix potential bug where ads may show up too often due to disconnect and reconnect
Custom mouse bindings

1.5.2
Add option to Dim Display while connected via Vysor

1.5.1
Vysor Share links now open in Inkwire on Android https://inkwire.io

1.4.9
Black screen fix on some devices

1.4.7
Custom key bindings and navigation bar

1.4.6
Update adb binaries for Windows

1.4.5
Resetting display settings on exit is now optional

1.4.4
New display settings to emulate any display size when connected with Vysor
Link to new desktop apps
Turn on ads for non-Pro users. Ads will be shown every 30 minutes on the Android device.

1.4.2
Record Screen available to Pro users
Tab to change focused control

1.3.7
Device farm disconnect fixes
Notify the user of the account being licensed on purchase
Disable vysor ime on session ending

1.3.4
Better support link for Android Device not found
Linux support via Electron

1.2.9
Workaround a bug in OPO3 firmware update that was causing Vysor to show a black screen

1.2.6
Fixes to make license checking work better in offline scenarios and behind firewalls

1.2.5
Use China friendly domains for Vysor's licensing, share, and enterprise servers

1.2.4
Fix license not found for new subscription methods

1.2.3
Add support for free trials
Add new payment options for monthly and annual subscriptions (Alipay and Credit Card)

1.2.1
Trim Chrome app size
Prevent view and share the device at the same time, as this does not work
Label and show messages for unauthorized and offline devices
Fix reset default settings not working on Vysor Free

1.1.3.9
Fix APK installation bug
Fix bug where screenshots wouldn't work if device was rotated
Remove need for port forwarding for mirroring
Improve vysor screenshots
Tons of changes to support the standalone Vysor app (no Chrome necessary)
Fix bug where license would not work after retrieve license


1.1.3.7
Improve mirroring latency

1.1.3.6
Add a web video streaming link in the device settings for recording and broadcasting

1.1.3.5
Vysor Share Server now supports 3 authentication models:
  - Whitelist
  - Open Server
  - Vysor Enterprise (users licensed by your Chrome account will also have access)
Retrieve License now shows feedback on failure

1.1.3.3
Fix Windows crash
Add Credit Card and Alipay lifetime purchase option

1.1.3.2
New per device configuration options:
  - name
  - always on top
  - resolution
  - bitrate
  - hardware acceleration
Share All Devices now persists between restarts/reloads
Easier to submit bug reports with a built in log collector

1.1.3.1
Fix Vysor Share All bugs
Fix bugs in purchase screen

1.1.3.0
Fix bug in license caching

1.1.2.9
Add email permission to Chrome app manifest, as it is necessary for offline use
Refactor license checking to handle auth token requests and errors better

1.1.2.8
Allow renaming devices in the UI

1.1.2.7
Add logging around license checking
Fix bug where license checks would fail prematurely if the user has not retrieved an auth token

1.1.2.4
Remove unnecessary audio capture permission

1.1.2.3
Fallback check the license if the Chrome web store check fails
Fix errors around startup license check
License will remain cached longer for older purchases
Add logging around adb server connection

1.1.2.2
Fix bug in caching Paypal licenses

1.1.2.1
Roll back change that seems to be causing license saving errors

1.1.2.0
Potential workaround to fix licensing issues when Chrome store responds with an error

1.1.1.9
Vysor Share fixes

1.1.1.6:
Fix size and centering issues in full screen mode

1.1.1.5
Add button to allow connecting to Android devices by IP (adb connect)

1.1.1.4
Fix crash on older Androids

1.1.1.3
Fix resize bugs

1.1.1.2
Fix issue where Vysor window would continually grow/shrink/wiggle
Improve Vysor Share All performance

1.1.1.1
Fix potential Vysor Pro license retrieval issues

1.1.1.0
Use modal dialogs instead of notifications when appropriate
Prompt when booting another user off a device on a Vysor Share Server
Fix several Vysor Share bugs

1.1.0.9
Fix Vysor Share All leaving dangling connections when disconnecting

1.1.0.8
Fix bug in Vysor Server where it doesn't show who was is using a device

1.1.0.7
Performance improvements for Vysor Share All

1.1.0.6
Make the title menu overflow less easily
Add a tutorial that explains the various Vysor buttons

1.1.0.5
Fix bug where older Androids sometimes do not get detected properly

1.1.0.4
Use a more efficient method of detecting when new Androids are connected. This should avoid a bug in the adb binary.
Fix bugs in going wireless on slower devices.
Show error when wireless mode fails
Fix bug where Vysor Share All did not work with Androids connected via ethernet or wireless

1.1.0.3
Fix various Wireless Mode bugs
Add button to reconnect to a disconnected Wireless window
Minor UI improvements
Add enterprise licensing option https://billing.vysor.io/
Fix licensing bug
Fix bug where Vysor Share All was available to non-Pro users
Better encoding resolution for low end devices

1.1.0.2
Fix "screen is unavailable" bug on a variety of devices
Remove superfluous logging and errors from the console log

1.1.0.1
Vysor Pro branding

1.1.0.0
Add more intuitive Paypal license retrieval button to purchase window

1.0.9.9
Fix bug where going into Wireless Mode would not work if Start Automatically was enabled.

1.0.9.8
Fix bug where Vysor Wireless was not available for some devices

1.0.9.7
Better auth token management
Retrieve Paypal purchases automatically when starting the purchase process

1.0.9.6
Fix bug for some users where increasing the quality was not doing anything

1.0.9.5
Fix the go wireless button not showing up for Vysor ADB users

1.0.9.3
You can now use Vysor wirelessly by clicking the Go Wireless button (wifi icon)
Minor UI improvements
Increase ADB server version to 36
Gracefully shutdown ADB sockets when appropriate to prevent adb binary from hanging

1.0.9.2
Fix crash bug when clipboard service is unavailable
Fix bug where Vysor will get stuck "Connecting"
Handle touch events on touch screen monitors
Fix fullscreen mode on WIndows
Handle bug where Vysor ADB server would not properly handle failed sockets

1.0.9.1
Fix the wording on the Paypal purchase. It is a one time lifetime pass, not an annual subscription.

1.0.9.0
Fix bug with Paypal purchases
Add support for pinning titlebar so it doesn't stick on the notification area

1.0.8.9
Add support for purchasing a lifetime pass with PayPal
Manage Vysor Keyboard disconnect and reconnect better
Add a settings button on all Vysor windows

1.0.8.8
Add option to enable/disable Vysor keyboard

1.0.8.7
Fix whitelist saving/loading bugs
Fix Enter no longer sending messages

1.0.8.6
Show an ongoing notification when Vysor is hiding your keyboard

1.0.8.4
Fix whitelist saving bug

1.0.8.3
Vysor now includes a Android IME for use with the Chrome app. There will be no on screen keyboard when using Vysor.
Support for international characters (UTF-8)

1.0.8.2
Fix rendering bugs in the Vysor whitelist
You can now purchase Vysor Pro with a buy once lifetime pass

1.0.8.1
More Vysor Share fixes
License caching is now more lenient for longer offline usage

1.0.8.0
Fix broken share button

1.0.7.9
Fix bug where input hangs when dragging, or the app idles

1.0.7.7
UI redesign
Vysor Share now lets you share all Android devices to a URL with the click of a button.
Manage which Google have access to your Android devices via Vysor Share.

1.0.7.6
If the decoder starts falling behind, purge all pending frames, and request a sync frame to catch up quicker

1.0.7.5
Fix broken back softkey

1.0.7.4
Improve image quality when switching between portrait and landscape
Fix regression where image quality option did not work
Fix regression where connections were not cleaned up when the Vysor window was closed
FIx window close error spam

1.0.7.3
Fix usage tracker with the new decoder
Fix bug where Vysor will replay all frames that were not shown while the app was inactive, causing frame delay

1.0.7.2
Show error message if trying to purchase while not logged into Chrome
Show error message while purchasing from a country that does not support Chrome Web Store payments
Force software decoding to fix possible decoder latency issues
Implement license caching so subscribers can use the app offline. Requires login.

1.0.7.1
Crash fixes related to purchasing

1.0.6.9
Add Vysor subscription options to unlock more features
Revamp h264 pipeline to be much more efficient
Add image quality option, supporting bit rates between 500Kbps (free) and 2Mbit (Pro)
Drag an drop files to open them
Drag and drop APKs to install them

1.0.6.8
Fullscreen mode
Fix bugs that caused crashes in React.js apps
1.0.6.7
Fix analytics

1.0.6.6
Fix various Vysor Share bugs
Vysor Share now allows you to share your Android to users that do not have Vysor (Chrome and Firefox)

1.0.6.5
Fix Vysor on N Preview

1.0.6.4
New loading screen

1.0.6.3
Fix crash related to resizing window

1.0.6.2
Extend trial duration

1.0.6.1
Fix window size bug with reopening a Vysor window after the soft keys hidden

1.0.6.0
Fix window resizing bug
Add softkeys. You can toggle visibility by pressing the keyboard button on the top.

1.0.5.9
New menu buttons: screenshot, volume up/down, rotate screen, power
Fix rotation issues on pre-Kitkat devices

1.0.5.8
Fix bug where Vysor ADB Server was potentially sending more data than is legally allowed by the protocol
This fixed the forever-spinner issue when installing the Vysor APK

1.0.5.7
Fix bugs in API level 16 and 17
Added support for FireTV and FireTV Stick

1.0.5.6
Initial support for API level 16 (Jellybean) devices
Improved network code
Fix bug where Vysor would automatically connect on launch or reload
Improve Vysor adb authentication
More logging

1.0.5.5
Show unauthorized devices in list (when using adb binary)
Add a debug setting to not use the Fetch APIs
Make the title bar fade out after 2 seconds. Will reappear on window refocus
More effecient screen capturing surface
Watch and warn for h264 high/main profiles being used. This happens with custom ROMs.
Fix potential race on connect
Do not autoconnect to emulators
Prevent window resizing from going beyond screen bounds
Force H264 baseline and profile level 4
Show warning if screenrecord is not supported

1.0.5.4
Fix Vysor share
Handle potential race on connect
Do not autoconnect to emulators
Prevent window resizing from going beyond screen bounds
Force H264 baseline and profile level 4
Show warning if screenrecord is not supported

1.0.5.3
Fix excessive reconnection occurring during rotation

1.0.5.2
Add thin title bar showing the Vysor serial number in the mirror window
Fix some issues with Vysor being blank or forever spinning
Add more logging
Add troubleshooting links
Fix crash that happens if Vysor list is closed
Better suggestions and info

1.0.5.1
Fix Windows 10 Chrome issues by requiring the native Universal ADB Drivers for adb server startup

1.0.5.0
Security fix: protect keyboard and screen access
Add a backup TURN server
Show notification and reload option if Android USB device failed to open
Attempt to connect multiple times on window open in case vysor is slow
Fix race hang condition on vysor connect
Fix bug where tips were not showing on first launch
Add mouse shortcut tips

1.0.4.9
Better error logging and graceful handling

1.0.4.8
Implement copy and paste

1.0.4.7
Retain user preferences when a Vysor window is resized and later reopened or rotated

1.0.4.6
Only show update notifications in response to user interaction
Watch for media_server hang on Android, as this causes the dreaded "black screen"

1.0.4.5
Notify on APK installation errors (older SDK, etc)

1.0.4.4
Fix potential bug in USB stack

1.0.4.3
Update check crash fix
Analytics crash fix

1.0.4.1

New Youtube link for USB Debugging tutorial
Add update checking
Add analytics to collect vendor id and product id of usb devices to ensure UniversalADBDriver stays up to date
Notification for USB device connection failure

1.0.4.0
Show a desktop notification if Chrome WebGL is disabled

1.0.3.9
Show a desktop notification when USB Debugging authorization is needed on the phone

1.0.3.8
Fix black or loading screens when attempting to connect to rooted devices.

1.0.3.7
Vysor now unshares devices upon disconnect, whereas before it would unshare when Vysor was closed

1.0.3.6
Note that ADB needs to be enabled.
Package new APK that has better instructions and graphics.

1.0.3.4
Fix bug where Vysor would not reconnect after disconnect

1.0.3.3
Point to different Vysor share url so SSL is supported

1.0.3.2
Fix bug with long running Vysor share connections
Fix bug where app_process is left hanging on multiple Vysor opens

1.0.3.1
Remove debug code that was always forcing use of the TURN server

1.0.3.0
Teardown fixes

1.0.2.9
Fix Vysor share issues associated with packet loss
Fix race condition when opening a Vysor window

1.0.2.8
Fix redundant connection multiplexing in the Vysor Share protocol

1.0.2.7
Teardown fixes for Vysor Share
Performance improvements in Vysor share

1.0.2.6
Fix bug with Vysor Share not starting adb server as necessary.

1.0.2.5
Use random port per Vysor Share device.

1.0.2.4
Imrove the Vysor Share protocol to not be latency bound.

1.0.2.3
Right click goes Back
Middle click goes Home
Fix Windows driver link
Initial implementation of Vysor Share. With this you can:
  - Share your adb devices via a hyperlink to developers.
  - Setup a test farm with a dozen devices, and use them remotely for development (with full adb).

1.0.2.1
Fix issues around multiple devices connected to vysor at the same time

1.0.2.0
Fix issues with key events
Allow permanent dismissal of Tips window
Show notification if the Vysor ADB server receives an unknown adb client command
Remove need to click the device in the list after selecting the USB device

1.0.1.9
Android viewer will open immediately upon click, show a loading gif
Fix bug where disconnected window would not reconnect automatically if the option was disabled
