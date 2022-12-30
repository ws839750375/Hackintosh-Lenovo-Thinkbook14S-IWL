# Thinkbook14S-IWL-EFI-OpenCore
 Lenovo Thinkbook 14s OpenCore EFI for Hackintosh

Hello everyone.

So, I created this repository to share my OpenCore configuration on Lenovo Thinkbook-14S-IWL. Hopefully this will help someone who has same machine to install Hackintosh.

MacOs Version: MacOS Vemtura

OpenCore Version: 0.8.7

Tested machine:

Thinkbook 14s IWL i5-8265U
Below is machine spec that I use to test the EFI. If you have similar model and spec, this EFI should work for you.

Laptop Specifications:

Hardware	Info
CPU	Intel(R) Core(TM) i5-8265U CPU @ 1.60GHz
MEMORY	8 GB DDR4
GRAPHICS	Intel UHD Graphics 620 (Mobile)
DISK	WDC PC SN520 
SOUND	Realtek ALC257
Network	Intel AC9560
What's Working:

Name	Comment
Graphics Acceleration	
Trackpad	Gesture enabled. Using VoodooI2CHID.
Keyboard	Almost all shortcut key work
Internal Speaker	
Internal Microphone	
Headphone jack	Audio line-in not tested yet
USB Type-A	
USB Type-C	tested with USB type C hub
Camera	
Battery Indicator	
Brightness	Keyboard shortcut is working
Wifi	using airportitlwm
Bluetooth	
HDMI	
What's Not Working/Partially working:

Name	Comment
Fingerprint	
Bug:

Note:

You can use GenSMBIOS to generate SMBIOS.
Use ProperTree to edit config.plist.
Usefull Link and Credits:

OpenCore Install Guide: this is starting point if you want to install Hackintosh using OpenCore.
Acidanthera: for most of the kexts
Olarila: If you want to download Mac Os Vanilla image without having Mac.
OpenIntelWireless: for intel wifi & bluetooth kexts
VoodooI2C: Trackpad kexts
ECEnabler: for working battery status
