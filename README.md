# Thinkbook14S-IWL-EFI-OpenCore
 Lenovo Thinkbook 14s OpenCore EFI for Hackintosh

MacOs Version: MacOS Vemtura 13.1

OpenCore Version: 0.8.7

Tested machine:

Thinkbook 14s IWL i5-8265U
Below is machine spec that I use to test the EFI. If you have similar model and spec, this EFI should work for you.

Laptop Specifications:

|Hardware|Info|
|:---|:---|
|CPU|Intel(R) Core(TM) i5-8265U CPU @ 1.60GHz|
|MEMORY|	8 GB DDR4|
|GRAPHICS|	Intel UHD Graphics 620 (Mobile)|
|DISK|	WDC PC SN520| 
|SOUND|	Realtek ALC257|
|Network|	Intel AC9560|

What's Working:

|Name|	Comment|
|:---|:---|
|Graphics| Acceleration|	
|Trackpad|	Gesture enabled. Using VoodooI2CHID|
|Keyboard|	Almost all shortcut key work|
|Internal Speaker|	
|Internal Microphone|	
|Headphone|
|USB Type-A|	
|USB Type-C|	tested with USB type C hub|
|Camera|
|Battery Indicator|	
|Brightness|	Keyboard shortcut is working|
|Wifi|	using itlwm+Heliport|
|Bluetooth| tested with airpodspro2|
|HDMI|
|Sleep mode|

What's Not Working/Partially working:

|Name|	Comment|
|:---|:---|
|Fingerprint|	

Bug: Ventura Wireless need use itlwm.kext 2.2.0 version and Heliport tool to stable wireless connect.

Note:

You can use GenSMBIOS to generate SMBIOS.
Use ProperTree to edit config.plist.


please change the config.plist Seriea numer with SMBIOS first.


Thanks for [cupugila](https://github.com/cupugila/Thinkbook-13s-IWL-EFI-Hackintosh) bigsur opencore 0.7.2 repository. upgraded from his repository.
