***Hotspot Wifi direct Raspberry Pi 4***

Scripted by this method: https://frillip.com/using-your-raspberry-pi-3-as-a-wifi-access-point-with-hostapd/

Working with Debian Hypriot OS (include Docker): https://downloads.hypriot.com

* connect to raspberry pi 4 with ssh
* run commands

```
sudo -s
mkdir /home/pi/code
cd /home/pi/code
wget -P /home/pi/code https://raw.githubusercontent.com/TamataOcean/rpi_wifi_direct/master/raspberry_pi4/install_wifi_direct.sh; chmod +x /home/pi/code/install_wifi_direct.sh; bash -x /home/pi/code/install_wifi_direct.sh
```

* reboot
* enjoy
________________________________________________________

* After reboot, connect your pc, phone,... to the hotspot wifi "WifiRaspi"
* password: wifiraspi 
* ip of raspberry pi wifi : 172.24.1.1
* hotplug ethernet
* hotspot wifi

________________________________________________________



