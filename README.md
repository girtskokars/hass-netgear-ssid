# Netgear SSID 
Add SSIDs as devices for Netgear presence detection in Home Assistant.

## Installation
Download the [latest release](https://github.com/girtskokars/hass-netgear-ssid/releases/latest).
Unpack the release and copy the custom_components/netgear_ssid directory into the custom_components directory of your Home Assistant installation.
Add/configure the netgear_ssid platform (all options from [official Netgear integration](https://www.home-assistant.io/integrations/netgear/) are available) and add the ```include_ssids``` configuration variable.
Restart Home Assistant.

## Configuration
```yaml
device_tracker:
  - platform: netgear_ssid
    password: YOUR_ADMIN_PASSWORD
    include_ssids: true
```