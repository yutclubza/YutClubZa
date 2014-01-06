### Helium Support Wiki

**Before sending an email to support, please take the time to read through the wiki to search for an answer to your issue.**

# Unsupported and Problematic Devices.

* **Any Motorola device** - There is something in the firmware that prevents Helium from working.
* **Some Sony devices** - If you're seeing an issue where Helium is asking for a desktop password, and your device is _not_ encrypted, then you're hitting a known issue with some Sony devices. There is something in the firmware of these devices that prevents Helium from working. 
* **Asus Transformer** line of devices. Some Transformers have an issue in the firmware that causes a Helium backup or restore process to hang. There is no fix or workaround for devices running stock ROM's.

# Common Helium Desktop Related Issues

## Helium Desktop App Installation Errors and solutions - Windows

### .DLL missing error
This error is caused by an elevation issue on your PC. You will need to run the .msi installer file as admin. To do so, right-click the installer and click run as admin. If you don't have that dialog when right-clicking, you will need to do a [Google Search](https://www.google.com/search?q=how+to+run+a+.msi+as+admin+windows&oq=how+to+run+a+.msi+as+admin+windows&aqs=chrome..69i57j0l5.9184j0j7&sourceid=chrome&espv=210&es_sm=122&ie=UTF-8) on how to run a .msi as admin for your version of Windows.

### .net 2.0 error
Some users experience an error telling them to install .net 2.0 on their systems, even though they are running a higher version of the .net framework. The solution to this is to install .net 3.5, as 4.0 does not contain the necessary files for some reason. It will not harm your system to do so. 

### Helium Desktop App Not Recognizing Your Device 
More than likely, this is a driver issue on your PC. To fix this, we include a universal ADB USB driver with the desktop installer package. Please follow the directions below to make use of it. 

Make sure you have ALL software and drivers for your device uninstalled including Helium desktop, then restart your machine. Then re-download Helium desktop and install ONLY that. During the install, make sure your device is NOT connected via USB. The driver should install to your system, then be used the next time you try to connect your device via USB.

### Additional Troubleshooting
* Make sure that you are connecting directly to your computer via USB, and not using a hub or an extension cable.
* Check your Windows device manager to ensure that there are no driver issues. If there is a yellow triangle by your device, then there is a driver issue that you need to address.
* Try a different USB port and USB cable. USB cables do indeed go bad.

### For LG G2 devices only

If you're having difficulty getting the Helium desktop to recognize your device, please follow the steps below.

1.	Install Helium desktop for Windows
2.	Install Helium for Android on your G2
3.	Go here ([http://www.lg.com/us/support-mobile/lg-LGVS980](http://www.lg.com/us/support-mobile/lg-LGVS980)), and download and install the USB driver that LG now has on their site (the default Windows driver won't suffice, even when using ethernet mode)
4.	Plug the G2 into the USB cable connected to your PC, and switch to ethernet mode

## Helium Desktop App Installation Errors and solutions - Mac

### Helium desktop app won't install due to unrecognized developer error
You will need to turn down your security settings to install Helium Desktop

### Helium Desktop app not recognizing your device
Try a different USB port and different USB cable with your computer. Also, disable Kies or HTC Sync software. If that doesn't help, try installing Android File Transfer.

