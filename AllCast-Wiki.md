## Common Problems
 * [Device Detection](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#device-detection-issues)
 * [Android Premium License Issues](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#android-premium-license-issues)
 * [Showbox App](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#showbox-app)
 * [Refunds](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#refunds)
 * [Casting videos from Gallery is slow](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#casting-videos-from-gallery-is-slow)

## Common Device Issues
 * [Chromecast](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#chromecast)
 * [PlayStation](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#playstation)
 * [Xbox 360](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#xbox-360)
 * [Xbox One](https://github.com/koush/support-wiki/wiki/AllCast-Wiki#xbox-one)
 * [Apple TV] (https://github.com/koush/support-wiki/wiki/AllCast-Wiki#apple-tv)

##Refunds
We do not offer refunds, as there is a try before you buy version that lets you test streaming for 5-minutes. Please do not purchase the app if you're having issues, buying premium will not magically make it work. 

##Android Premium License issues.
If you're having trouble installing the premium license for AllCast, or having trouble getting the trial version to recognize the premium license follow these steps.

 1. Uninstall the premium key from your device.
 2. Reboot your device.
 3. Go to a computer and go to the Play store web portal, and go to your list of purchased apps.
 4. Navigate to the premium key in your list of purchased apps.
 5. Push an install of the premium key to your device through the web portal.

This should resolve the issue. 


## Showbox App
To cast from Showbox to Allcast, download the [Growbox](https://www.reddit.com/r/showbox/comments/2xeiwi/growbox_a_solution_for_not_being_able_to_cast/) app.

Showbox servers are often very slow. This can not be resolved by AllCast.

## Casting Videos from Gallery is Slow

This is usually due to congestion on your wireless network. To send a lower quality video that uses less wireless bandwidth, go into AllCast Settings and set the bitrate to 600000.

## Stop Casting
When casting a file, there is a stop button that appears over the file. When you want cease casting, press that button, and the casting should stop.

## General Troubleshooting steps (Can't discover destination, choppy playback etc.)
If you're experiencing issues when using AllCast, follow these few simple steps to see if they will help you before contacting us at support. 

1. Reboot your device, casting location and your wireless router.
2. Make sure you have no network bottlenecks, such as other devices, that might be slowing your network down.
3. If you have multiple routers on your network, make sure that your Android device and casting destination are connected to the same one. 
4. If your file that you're having trouble casting is located in the cloud, try bringing it to local storage to see if it casts successfully. Let us know at support if it does. It both locations fail, try bringing the file to a local computer or other media player to see if it will successfully play. 

## Windows DLNA Support

### Files shared on a Windows-based machine. 
Make sure that the network that the computer is connected to is set to a home network. We have included a screenshot to demonstrate what we mean.
<img src="http://i.imgur.com/xNsYGpZ.png" title="Hosted by imgur.com" />


## Subtitle Support
Subtitle support has been added to AllCast. To ensure the app picks up you subtitle file, make sure the file is in the same folder location as the video you are trying to cast, and has the EXACT same title as said video. IE you want to cast avengers.*, your subtitle file needs to be titled avengers as well. 
 
## Images and video turned sideways on your destination screen.
When you take images and video in portrait mode, it's like holding a camera sideways. The media is recorded and then rotated by your device so you can see it. However, the media is still shot sideways. When you stream to your TV or other device, the media is going to show up sideways since it was taken in that way. There is no way to rotate through AllCast. The solution is to stop taking images and video sideways, or to put the media into an editor that can rotate the media and save it in landscape mode. 

## Codec issues
While the Chromecast does support the .MKV container, it doesn't support the wide array of audio codecs that can be present in said container. To work around this, try using the HLS feature found in the top right hand corner of the app after you select a casting destination. It will adjust bit rate and format on the fly. 

### Chromecast

### Device detection issues.
If you are having difficulty detecting your chromecast, reboot it by unplugging from power and plugging it back in. If this still does not work, hold the reset button on the device for 30 seconds to factory reset and go back through the setup with the chromecast app.

Lastly, if you have a multi-band router, disable the 5ghz band as Chromecast sometimes hates to see two different signaled networks. Also, go into the settings of your router to turn off any multi-cast filtering that might be in place.

If your router is old (more than two years) it may not be compatible with Chromecast and streaming. Consider upgrading to a newer device. 

### Roku
Please be aware that AllCast can only stream to Roku devices that are capable of this functionality. Older Roku's do not support the feature. The best way to find out if your device is supported is to download the free Roku app, and try to stream from it to your Roku device. If it can do so, then AllCast will work, if it will not, then AllCast cannot either.

If you're having difficulty finding your Roku through AllCast, make sure to reboot the Roku as well as the device, also make sure that both devices are on the same network that you own and control. Lastly, reboot the router if you continue to have trouble. 

### PlayStation
PlayStation (3 and 4) is a DLNA browser, not a DLNA renderer. A DLNA renderer is necessary here, unfortunately.
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

You *can not* be playing a game while attempting to use AllCast. The Xbox One will not be detected. Quit the game by returning the the dashboard, pressing the menu button, and Quitting it.

### Apple-TV

If you are having trouble casting to your Apple TV, first check if there is a sharing password. If so, remove it and try again. Also, try rebooting the device as well. 
