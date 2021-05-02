This EFI Uses OpenCore 0.6.8
------------
NUC5i5RY* NUC5i7RY*

:

CPU: i5-5250U

------------

Integrated graphics: Intel® HD Graphics 6000.

  Just set AAPL,ig-platform-id to 06002616, no need framebuffer patches on my nuc.

------------

Wireless Network and Bluetooth Card: Intel® Wireless-AC 7265 (Build-in, soldering on board)(802.11ac & Bluetooth*4).

  use itlwm.kext and HeliPort(WiFi APP) for WiFi,and IntelBluetoothFirmware from https://github.com/OpenIntelWireless

------------

Integrated LAN: Intel® Ethernet Connection I218-V (10/100/1000Mbps). 

  use IntelMausi.kext 

------------

Audio card: Realtek ALC 283 (Frontpanel 3.5mm headphone/microphone combo jack). 

  layout-id: 11


------------


Not a good EFI. Just work, but not work well, because i don't know Hackintosh a lot.
------------
Issues:
Hibernation: sometime take a long time to recover from sleep. 
HDMI/DP audio haven't test. 
------------
Sorry for my poor English :)
