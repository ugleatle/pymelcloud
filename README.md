# MELCloud

Home Assistant support for Mitsubishi air conditioner/heatpump (MELCloud)

For more details about this platform, please refer to the documentation at
https://home-assistant.io/components/?????/

## Installing

Copy climate.py to custom_components\melcloud

To enable the platform, add the following lines to your configuration.yaml file
	
	climate:
	  -platform: melcloud
	   email: MY_EMAIL@gmail.com
	   password: MY_PASSWORD


This is a modified version of the original component by o0Zz https://github.com/o0Zz


Logging options

	logger:
	  default: debug
	  logs:
	    homeassistant.components.climate.melcloud: debug

