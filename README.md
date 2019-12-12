# Home Assistant Configuration

This is my [Home Assistant](https://home-assistant.io/) configuration. I have installed HA on a [HP ProDesk 600 G3 Mini](https://support.hp.com/us-en/document/c05364047). I am running Ubuntu 18.04 on this machine and running mostly Docker images on it. This includes the [Home Assistant Docker Image](https://hub.docker.com/r/homeassistant/home-assistant/).

I regularly update my configuration files. You can check my current HA version [here](.HA_VERSION). If you like anything here, be sure to star my repo!

Proud Supporter of [NabuCasa](https://www.nabucasa.com/) - Help keep Home Assistant alive.

## Docker Containers Related to my Home Assistant Instance

* [Mosquitto Broker](https://hub.docker.com/_/eclipse-mosquitto) - For managing my Sonoff devices and any future MQTT devices (Docker Container)
* [NodeRed](https://hub.docker.com/r/nodered/node-red) - NodeRed for my more complex automations
* [Microsoft SQL Server](https://hub.docker.com/_/microsoft-mssql-server) - For logging to keep my HA instance fast by offloading to the work

## Components / Devices

  * [Aeotec Z-Stick Gen5](https://www.amazon.com/dp/B00X0AWA6E/) for Z-Wave control
  * Assistance
    * Managed by [NabuCasa](https://www.nabucasa.com/)
  * Presence Detection - Only for visual use currently
    * [NMap](https://www.home-assistant.io/integrations/nmap_tracker/)
  * Security
    * [Abode Home Security](https://home-assistant.io/components/alarm_control_panel.abode/)
    * [Ring Video Doorbell](https://home-assistant.io/components/ring/) 
    * [Amcrest Cameras](https://www.home-assistant.io/components/camera.amcrest/)
  * Notifications
    * [Join](https://www.home-assistant.io/components/joaoapps_join/) - Join is an awesome app that allows you to push notifications to Android devices (like PushBullet, but free).
  * Remotes / Hubs
    * [OctoPrint](https://www.home-assistant.io/components/octoprint/) (_Work In Progress_)
  * Sensors
    * [EcoBee Thermostat](https://www.home-assistant.io/components/ecobee/)
    * [Dark Sky](https://www.home-assistant.io/components/weather.darksky/)
    * [Moon](https://www.home-assistant.io/components/sensor.moon/)
    * [Template Sensors](https://www.home-assistant.io/components/sensor.template/)
    * [Time/Date Sensor](https://www.home-assistant.io/integrations/time_date/)
  * Switches
    * [Sonoff](https://sonoff.itead.cc/en/) Switches using MQTT
  * Text-To-Speech
    * [Google Home](https://www.home-assistant.io/components/tts.google/) - For TTS (_Work In Progress_)
    