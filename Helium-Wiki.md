### Helium Support Wiki

**Before sending an email to support, please take the time to read through the wiki to search for an answer to your issue.**

# Unsupported and Problematic Devices.

* **Any Motorola device** - There is something in the firmware that prevents Helium from working.
* **Some Sony devices** - If you're seeing an issue where Helium is asking for a desktop password, and your device is _not_ encrypted, then you're hitting a known issue with some Sony devices. There is something in the firmware of these devices that prevents Helium from working. 
* **Asus Transformer** line of devices. Some Transformers have an issue in the firmware that causes a Helium backup or restore process to hang. There is no fix or workaround for devices running stock ROM's.

# Common Helium Desktop Related Issues

### Helium Desktop App Installation Errors and solutions
### Helium Desktop App Not Recognizing Your Device - Windows
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


