# Home Assistant Configuration

## ⚠️ WARNING: ⚠️

## ⚠️ This repo will be removed soon. It is outdated and does not accurately represent my Home Assistant instance anymore

---

This is my [Home Assistant](https://home-assistant.io/) configuration. I have installed HA on a [HP ProDesk 600 G3 Mini](https://support.hp.com/us-en/document/c05364047). I am running Ubuntu on this machine and running mostly Docker images on it. This includes the [Home Assistant Docker Image](https://hub.docker.com/r/homeassistant/home-assistant/).

I regularly update my configuration files. You can check my current HA version [here](.HA_VERSION). If you like anything here, be sure to star my repo!

Proud Supporter of [NabuCasa](https://www.nabucasa.com/) - Help keep Home Assistant alive.

## Docker Containers Related to my Home Assistant Instance

* [Mosquitto Broker](https://hub.docker.com/_/eclipse-mosquitto) - For managing my Sonoff devices and any future MQTT devices (Docker Container)
* [NodeRed](https://hub.docker.com/r/nodered/node-red) - NodeRed for my more complex automations (and maybe all automations in the future. We will see.)

## Hardware

  * [HP ProDesk 600 G3 Mini](https://support.hp.com/us-en/document/c05364047)
  * [Aeotec Z-Stick Gen5](https://www.amazon.com/dp/B00X0AWA6E/) for Z-Wave control

## Components / Devices / Integrations

  * [Abode Home Security](https://home-assistant.io/components/alarm_control_panel.abode/)
  * [EcoBee Thermostat](https://www.home-assistant.io/components/ecobee/)
  * [Logitech Harmony Hub](https://www.home-assistant.io/integrations/harmony/)
  * [Meteorologisk institutt (Met.no)](https://www.home-assistant.io/integrations/met/)
  * [Moon](https://www.home-assistant.io/components/sensor.moon/)
  * [Network UPS Tools (NUT)](https://www.home-assistant.io/integrations/nut/)
  * [OctoPrint](https://www.home-assistant.io/components/octoprint/)
  * [Plex Media Server](https://www.home-assistant.io/integrations/plex/)
  * [Ring Video Doorbell](https://home-assistant.io/components/ring/) 
  * [Sonoff](https://sonoff.itead.cc/en/)
  * [Synology](https://www.home-assistant.io/integrations/synology/)
  * [Template Sensors](https://www.home-assistant.io/components/sensor.template/)
  * [Time/Date Sensor](https://www.home-assistant.io/integrations/time_date/)
  * [Ubiquiti UniFi](https://www.home-assistant.io/integrations/unifi/)
  * [Weather](https://www.home-assistant.io/integrations/weather/)

## HACS ([Home Assistant Community Store](https://hacs.xyz/))

  * [Alexa Media Player](https://github.com/custom-components/alexa_media_player)
  * [Midnight Theme](https://github.com/home-assistant-community-themes/midnight)
  * [ShellyForHass](https://github.com/StyraHem/ShellyForHASS) (May remove in favor of MQTT/NodeRed)
  * [Vacuum Card](https://github.com/denysdovhan/vacuum-card)