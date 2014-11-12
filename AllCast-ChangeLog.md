## AllCast Changelog ##


### 1.1.4.4 10/17/2014
Crash fixes for Android Lollipop! If you're running the Android Lollipop preview, please make sure you are on the latest version released on October 16th!

Lollipop, lollipop
Oh lolli, lolli, lolli, lollipop, lollipop

Call my baby lollipop, tell you why
His kiss is sweeter than an apple pie
And when he does his shaky rockin' dance
Man, I haven't got a chance

### 1.1.4.1 8/26/2014
- Make the AllCast receiver splash screen an optional setting
- Add a new "Recents" drawer section to quickly get back to folders or media that you had viewed recently
- Add Crashalytics support

### 1.1.3.9 8/16/2014
- Fix some Chromecast detection issues
- Improve the startup experience by immediately starting AllCast on the target receiver

### 1.1.3.8 8/12/2014
More transcoding fixes for a bunch of devices (Nexus 4, Galaxy S3/4, etc)

### 1.1.3.2 8/5/2014
I AM HAPPY WITH THIS RELEASE THERES A LOT OF FIXES AND SOME FEATURES

Uh, sorry about that. *adjusts mic*

- AllCast now has volume controls. Just hit the volume buttons while on the Now Playing screen, and it'll adjust the volume! Easy!
- Fixed Twitch TV after the Twitch app update apparently broke it.
- Use cleaner, simple, placeholder images
- Various UI enhancements for the Chromecast receiver app.
- Implement a new transcoding engine. Fix transcoding on Android L.
- Fix cloud image casting to DLNA.


### 1.1.2.4
Flexing some of my new coding muscles after Google I/O 2014!

- More Support for Android L Material UI!
- Added a new Photo Albums sorting tab!
- New Card UI for Google Drive, Media Servers, and Albums!
- Bug fixes around the purchase flow.
- General bug fixes.

### 1.1.2.3 6/30/2014
I live in a Material World, and I am a Material girl! (Updated for the new Material UI in Android L)


### 1.1.2.1 6/29/2014
Android L preview came out and broke a bunch of stuff, so I fixed it. Cool story.

### 1.1.1.6 6/15/14
It's been quiet... too quiet. That's cause I've been working on new features (and probably making new bugs as a result, derp):

There's a new split view tablet UX. Can browse/control media playback on one screen when in landscape mode.

Photos are way easier to cast now with a new swipey UI. And slideshow mode was added to boot.

Ever get interrupted during a cast when the pizza guy calls? The cast will now pause automatically! (thanks bekit)

So, I just saw the GoT finale, Hodor for King, 2016.

### 1.1.1.3 6/4/2014
Websites that open full screen videos can be sent to AllCast. (tested with Chrome)

 - Smashing some bugs:
  - Media server now shows mp3s
  - Don't offer to intercept all web pages to AllCast

"SMASH THE BEETLES. SMASH EM!. KUKUNG CLUNG KUNG!"

### 1.1.1.1 5/31/2014
Something wonky happened with Twitch. Fixed it.

### 1.1.1.0 5/28/2014
AllCast Receiver for Chrome support... whaaaaat?

https://chrome.google.com/webstore/detail/allcast-receiver/hjbljnpdahefgnopeohlaeohgkiidnoe

### 1.1.0.9 5/25/2014
Bug fixes galore!

- Airplay: Possible fix for disconnect issues when casting from media servers or the cloud.
- Twitch TV: Wasn't working for lots of people before. Should be working for everyone now.
- Minor UI enhancements in the drawer and search. Tweaked some fonts and such.

### 1.1.0.8 5/23/14
- Bug fixes:
 - Fixed casting from ES File Explorer (smb) and other third party apps.
  - Fixed premium detection when casting from third party apps.

Software development, in a nutshell:

99 outstanding bugs in the app,
99 outstanding bugs,
pick one out, and patch it about,
105 outstanding bugs in the app

### 1.1.0.5 5/21/14

Fellow gaming nerds rejoice, this version of AllCast supports casting Twitch.tv! This will work on Chromecast, Apple TV, and Roku. Fire TV and the AllCast receiver coming soon too! DLNA, unfortunately, can not be supported.

To browse the new Twitch feed in your side drawer, make sure you have the Twitch app installed. Only live feeds are supported at the moment.

I also fixed a bunch of more Roku bugs.


### 1.1.0.4 4/19/2014 ###
- Oh, hello! I did not see you there. I've been playing too much Hearthstone lately. Fun!
- Boring:
 - Roku fixes. Album art, stop button fix.
- Cool:
 - Google Music now sees AllCast devices as Cast targets! Check out AllCast settings to enable this. It's awesome (req. root).

- HEADPHONE HOOK OMG. I'm not even going to tell you what this is. I'll just link a video:
http://www.youtube.com/watch?v=ZZdcGAD5ASU
Currently this only works w/ Fire TV and AllCast Receiver.

Oh, and there's a new AllCast Receiver.

Some users were saying they'd start playing something on their FireTV or their Smart TV, and nothing would happen. I told them it was just a matter of motivation, and they just needed to ask the TV nicely. That wasn't entirely true. Turns out there was a bug in my DLNA media playback code. But be nice to your TV anyways. And brush your teeth.

People do crazy things like use Windows Media Player to share media, and tether their chromecast to their phones! I accidentally broke those in a past update :(

But I fixed them. Please accept my apologies. And this update. And this cookie.

### 1.0.9.9 4/19/2014 ###

- Dear Artem, this will make DLNA browsing faster.

Yours truly,
  Koush


### 1.0.9.8 4/16/2014 ###

- Cache Apple TVs when found in case discovery fails later due to Android mdns issues.

### 1.0.9.6 4/12/2014

- Crash fixes
- Performance Fixes
- Redeem code support
- BETA: Amazon Fire TV support
- BETA: Google Drive
- Potential fix for disconnecting after 30+ minutes

### 1.0.8.8 3/30/2014 ###

- BETA: Subtitle support in Chromecast (requires a media server like Serviio)
- BETA: Dropbox browsing
- Chromecast letterbox is now black instead of grey
- Roku playback fixes: now supports fast forward and rewind. Seek bar is hidden.
- While seeking, the new seek position time will be displayed
- Fixes: jumpy lists, share-to crashing, album art crash, better file type detection



### 1.0.8.7 3/20/2014 ###

- Crash fixes
- Add a new Setting for Media Server proxying
- Fix various crashes when using the drawer
- Translations
- New Now Playing screen
- Lock screen controls
- Cover Art for music and videos
- Volume Control of Chromecast works with phone volume buttons
- Tons of bug fixes
- Fix up DLNA device discoverability
- Better playlist management
- Better playback controls after exiting/resuming the app
- Relax the "trial" notices if not using premium

