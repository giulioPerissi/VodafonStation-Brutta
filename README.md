# VodafonStation-Brutta
Remove-"Vodafone"-from-SSID-on-VodafoneStation

Simple way to remove the "Vodafone" from SSID VodafoneStation, this work for me with the VodafoneStationRevolution (the crappiest of the Ones):
1) Open the WiFi page of the router;
2) press F12, or right button -> Inspect;
3) Go to console;
4) Insert: "FC.ssid_prefix = false";
5) Set your SSID to what you want and apply change.

To revert the change simply repeat instruction but inserting: "FC.ssid_prefix = true", or reboot.

This work at least for me, I've found this instruction long time ago and cannot find the source again.
To my understanding this does not work on new firmware or other VodafoneStation model.
