## Devices
 * [Chromecast](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#chromecast)
 * [PlayStation 3](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#ps3)
 * [Xbox 360](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#xbox-360)
 * [Xbox One](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#xbox-one)

## Cloud Playback
 * [Google Drive](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#google-drive)
 * [Dropbox](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#dropbox)

## Subtitle Support
Subtitle support has been added to AllCast. To ensure the app picks up you subtitle file, make sure the file is in the same folder location as the video you are trying to cast, and has the EXACT same title as said video. IE you want to cast avengers.*, your subtitle file needs to be titles avengers as well. 
 
## Images and video turned sideways on your destination screen.
When you take images and video in portrait mode, it's like holding a camera sideways. The media is recorded and then rotated by your device so you can see it. However, the media is still shot sideways. When you stream to your TV or other device, the media is going to show up sideways since it was taken in that way. There is no way to rotate through AllCast. The solution is to stop taking images and video sideways, or to put the media into an editor that can rotate the media and save it in landscape mode. 

## Codec issues
While the Chromecast does support the .MKV container, it doesn't support the wide array of audio codecs that can be present in said container. To work around this, try using the HLS feature found in the top right hand corner of the app after you select a casting destination. It will adjust bit rate and format on the fly. 

### Chromecast

Chromecast is now supported! To be able to stream to Chromecast devices, you must first update the Google Play Services app on your Android device. This sometimes takes a few days to roll out via the Play store for various regions. You can also update Play Services manually by following the directions at this link: http://www.androidpolice.com/2014/02/03/apk-teardown-download-google-play-services-4-2-refines-play-games-adds-cast-api-signs-of-auth-enhancements/

If you experience issues detecting your Chrome Cast even after updating your Play Services, please unplug the Chrome Cast from it's slot then plug it back in. We have seen this force an update that will allow you to detect the device. 

### Roku
Please be aware that AllCast can only stream to Roku devices that are capable of this functionality. Older Roku's do not support the feature. The best way to find out if your device is supported is to download the free Roku app, and try to stream from it to your Roku device. If it can do so, then AllCast will work, if it will not, then AllCast cannot either.

If you're having difficulty finding your Roku through AllCast, make sure to reboot the Roku as well as the device, also make sure that both devices are on the same network that you own and control. Lastly, reboot the router if you continue to have trouble. 

### PS3
PS3 is a DLNA browser, not a DLNA renderer. A DLNA renderer is necessary here, unfortunately.
The PS3 can browse DLNA servers (pull files), but it can not be used as a remote renderer (push files).

More info here:
http://superuser.com/questions/502989/getting-play-to-working-on-windows-8-and-a-playstation-3


### Xbox 360

Then make sure your Play To feature is turned on in [Xbox 360 Settings](http://support.xbox.com/en-US/xbox-360/system/playto-setup). Turn "Play To" off, then back on again if necessary. Also, turn on the DLNA proxy button in the HLS settings in the top right hand corner of the app after selecting the 360 as your destination. 

#### Xbox 360 Issues

The Xbox 360 does not play back videos taken from an HTC One or Nexus 5.

### Xbox One

Xbox One is a bit fussy to set up.
First, make sure you have the following apps installed:

 * Xbox Video
 * Xbox Music

Then make sure your Play To feature is turned on in Xbox One Settings. Turn "Play To" off, then back on again if necessary.


### Google Drive

 1. Open the Google Drive app and find the file you want to play.
 2. Long click file + Send Link to AllCast

### Dropbox

 1. Open the Dropbox app and find the file you want to play.
 2. Long click file + Share to AllCast

