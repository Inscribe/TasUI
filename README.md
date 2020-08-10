:rotating_light: **WARNING: PROJECT SUSPENDED UNTIL FURTHER NOTICE** :rotating_light:

## TasUI

TasUI is a zero-install device management interface web application for all your Tasmota devices. 
It will discover your deployed devices and allow you to set up and configure every device from a single dashboard. 
This initial version includes multiple views (Control, Health, Firmware, Wi-Fi, & MQTT) to allow you to quickly assess the state of your devices. There is also a detailed view (e.g., SetOptions, Status, etc.) available. 

TasUI provides a syntax-aware command interface for every Tasmota command by category (e.g., Configuration, Timers, Sensors, Lights, etc.) as well as the "familiar" Console interface to enter commands directly. This is a beta version (i.e., we expect you to find some unexpected features). As these issues are fixed, it will not require you to reinstall any software to get these fixes. This also applies to new features as they are added to the app.

## Docker

For those who prefer to have everything locally, a Docker image for linux/amd64 (more architectures coming soon) is available for [download](https://hub.docker.com/r/iotreboot/tasui).

```
docker pull iotreboot/tasui
docker run -p [PORT]:80 iotreboot/tasui:latest
```
## Home Assistant

Coming soon.
