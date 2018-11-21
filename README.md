# MelCloud

Home assistant support for mitsubishi air conditioner/heatpump (MELCloud)

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
