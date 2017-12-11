# PP Home Assistant Configuration
My configuration for HASS.io on a Raspberry Pi 3 model B (https://home-assistant.io/)

## Integrations in use:

 * Chromecast - media player
 * Ubiquiti Unifi - presence detection
 * Nest - climate control
 * Pushbullet notifications
 * (WiP) Darksky weather
 * (WiP) Google Travel Time
 * (WiP) Fast.com connection monitoring
 * (WiP) System monitoring - CPU, RAM

## Automations:

### Away

* Turn off all lights and set Nest to away mode based off phone presence detection.
* Send push notification when away mode is activated.

### Return Home

* Turn on hall light and set Nest to home mode based on phone presence detection

### Night

* Turn on porch lights 15 minutes before sunset
* Turn off porch lights on after 11pm.

### Notifications

* House temperature is below 15 degC
* Internet connection goes down or comes back up
* Presence notification for home/away status of tracked devices
