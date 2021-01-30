# Spirit-ZigBee
Support for [Spirit ZigBee thermostatic device](https://eurotronic.org/produkte/zigbee-heizkoerperthermostat/spirit-zigbee/).

## Guides
[OTA update guide via deCONZ](https://github.com/EUROTRONIC-Technology/Spirit-ZigBee/wiki/OTA-update-guide-via-deCONZ)

## Updating Spirit-ZigBee Firmware files via Home Assistant deCONZ
With Home Assistant you do not have direct access to the deCONZ container. For this install install Portainer via Addons and disable "Protection Mode":
![image](https://user-images.githubusercontent.com/1632781/106361896-2b361500-6320-11eb-8025-19e1af362998.png)

Go to "Settings" and remove the "addon" type so that you can access the container:
![image](https://user-images.githubusercontent.com/1632781/106361940-60426780-6320-11eb-8935-1335922ba7ab.png)

Execute the "Console"
![image](https://user-images.githubusercontent.com/1632781/106361975-8ec04280-6320-11eb-87cd-ea740fae5ef2.png)

Copy the link to the latest release from [Spirit-ZigBee Releases](https://github.com/EUROTRONIC-Technology/Spirit-ZigBee/releases) and then execute:
```
cd /data/otau/

wget https://github.com/EUROTRONIC-Technology/Spirit-ZigBee/releases/download/20190408/20190408_EUROTRONIC_Spirit_Zigbee_0x00122C380.ota
```
![image](https://user-images.githubusercontent.com/1632781/106362026-dcd54600-6320-11eb-9d66-a791f3c7784d.png)

After this you have the latest firmware available for download.


## Firmware releases
Spirit supports an OTA updates: [releases](https://github.com/EUROTRONIC-Technology/Spirit-ZigBee/releases)
