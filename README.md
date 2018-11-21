# MelCloud

Home Assistant support for Mitsubishi air conditioner/heatpump (MELCloud)

For more details about this platform, please refer to the documentation at
https://home-assistant.io/components/climate.melcloud/

## Installing

Edit configuration.yaml and add below lines:
	
	climate:
	  -platform: melcloud
	   email: MY_EMAIL@gmail.com
	   password: MY_PASSWORD


	logger:
	  default: debug
	  logs:
	    homeassistant.components.climate.melcloud: debug


The library is used as part of Home Assistant
