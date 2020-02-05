# HA_admin_cmd
Administrator's commands for Home Assistant

Under default pi account

**Home Assistant**

- $ sudo systemctl start home-assistant@homeassistant.service
- $ sudo systemctl stop home-assistant@homeassistant.service
- $ sudo systemctl status home-assistant@homeassistant.service
- $ sudo systemctl restart home-assistant@homeassistant.service

Edit configuration

- $ sh toha.sh
- $ cd 
- $ vi .homeassistant/configuration.yaml


**Homebridge for Apple HomeKit**

- $ sudo systemctl start homebridge.service
- $ sudo systemctl stop homebridge.service
- $ sudo systemctl status homebridge.service
- $ sudo systemctl restart homebridge.service


**Raspberry Camera (GStream)**

Start

- $ sudo systemctl start raspicam.service
- $ sudo systemctl stop raspicam.service
- $ sudo systemctl status raspicam.service
- $ sudo systemctl restart raspicam.service
