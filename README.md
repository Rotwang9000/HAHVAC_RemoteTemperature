# HAHVAC_RemoteTemperature
Controlling a heatpump/aircon in home assistant using a remote temperature gauge

I could only find a basic thermostat for Home assistant that turned it on/off.
Here is an automation that uses a remote temperature sensor to get the heater to change it's desired temperature based on what the external thermometer says and what the heater's internal thermometer thinks it is.
It's set to just use heat mode until it is warm outside, so won't start wasting energy actively cooling if it gets just a little too warm.

Just a simple yaml at the moment that will need hardcoding but I may develop into a proper control later.

