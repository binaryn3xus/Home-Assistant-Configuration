# Home Assistant Configuration

This is my [Home Assistant](https://home-assistant.io/) configuration. I have installed HA on a [Raspberry Pi 3 B+](https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/). I am currently running [Hass.io](https://www.home-assistant.io/hassio/installation/) on on the Raspberry Pi. Though in the future I would like to migrate to a NUC device using docker. Thats for the future though.

I regularly update my configuration files. You can check my current HA version [here](.HA_VERSION). If you like anything here, Be sure to star my repo!

## Add-ons running on my Home Assistant (Hass.io) instnace

* [DuckDNS](https://home-assistant.io/addons/duckdns/) - For keeping my SSL certificate validated through [Let's Encrypt](https://letsencrypt.org/).
* [Mosquitto Broker](https://home-assistant.io/addons/mosquitto/) - For managing my Sonoff devices and any future MQTT devices
* [SSH Server](https://home-assistant.io/addons/ssh/) - For SSH into the Raspberry Pi
* [Samba Share](https://home-assistant.io/addons/samba/) - For exploring the config files from a Windows computer

## Components / Devices

  * [Aeotec Z-Stick Gen5](https://www.amazon.com/dp/B00X0AWA6E/) for Z-Wave control
  * Assistance
    * [Alexa Skill](https://www.home-assistant.io/components/alexa/) - This is the custom developer alexa skill, not the HA Cloud skill. Therefore, I had to create my own intents. You will find those in this repository as well.
    * [Emulated Hue](https://www.home-assistant.io/components/emulated_hue/)
  * Presence Detection - This is currently not used for much since I have been experimenting with different methods though getting close to picking one.
    * [Google Maps](https://www.home-assistant.io/components/device_tracker.google_maps/)
  * Security
    * [Abode Home Security](https://home-assistant.io/components/alarm_control_panel.abode/)
    * [Ring Video Doorbell](https://home-assistant.io/components/ring/) 
    * [Amcrest Cameras](https://www.home-assistant.io/components/camera.amcrest/)
  * Notifications
    * [Join](https://www.home-assistant.io/components/joaoapps_join/) - Join is an awesome app that allows you to take notifications based on an IP. I found it when pushbullet went to a pay scale and I never looked back. The developer makes a lot of useful automation apps.
  * Remotes / Hubs
    * [OctoPrint](https://www.home-assistant.io/components/octoprint/) (_Work In Progress_)
  * Sensors
    * [EcoBee Thermostat](https://www.home-assistant.io/components/ecobee/)
    * [Weather Underground](https://www.home-assistant.io/components/sensor.wunderground/) - Though I may switch to [Dark Sky](https://www.home-assistant.io/components/weather.darksky/) eventually
    * [Moon](https://www.home-assistant.io/components/sensor.moon/)
    * [Template Sensors](https://www.home-assistant.io/components/sensor.template/)
  * Switches
    * [Sonoff](https://sonoff.itead.cc/en/) Switches using MQTT
  * Text-To-Speech
    * [Google Home](https://www.home-assistant.io/components/tts.google/) - For TTS
    