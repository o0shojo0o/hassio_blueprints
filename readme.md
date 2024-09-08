<!--- https://my.home-assistant.io/create-link/?redirect=blueprint_import -->

## Controller - IKEA E1743 Tradfri Switch as a Push-Button to Light via zigbee2mqtt
Controls a light with any number of switches given by ENTITY.  
The switch is interpreted as a push-button so that 'ON' and 'Brightness Move Up' can control a different light to 'OFF' and 'Brightness Move Down'  
For example, 'Brightness Move Up' first dims up and then dims down again when pressed repeatedly.  
Unfortunately, a helper of the type boolean (switch) is required for this functionality.  
For dimming, the zigbee2mqtt functionality 'brightness_move' is used to enable smooth and network-friendly dimming.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fo0shojo0o%2Fhassio_blueprints%2Fblob%2Fmain%2Fcontroller_ikea_e1743_switch_to_light.yaml)

## Controller - IKEA E2123 Symfonisk sound controller GEN2 for media
Control the selected media player with an IKEA Symfonisk sound controller GEN2 via Zigbee2MQTT (Z2M)  
Supports single press on media buttons and single, double and long press for the "dot" buttons.
  
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fo0shojo0o%2Fhassio_blueprints%2Fblob%2Fmain%2Fcontroller_ikea_E2123_symfonisk_sound_controller_for_media.yaml)

## Avoiding the feed-in of PV energy into the grid
This automation will react on changes of energy imported or exported from the grid.  
It will control the Photovoltaic power generation by setting the limit to a value avoiding exporting to the grid.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fo0shojo0o%2Fhassio_blueprints%2Fblob%2Fmain%2Fpv_zero_feed_in.yaml)

## Simple Cover Control
A simple control mechanism for managing the position of a cover using one or more switches.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fo0shojo0o%2Fhassio_blueprints%2Fblob%2Fmain%2Fcover_control.yaml)
