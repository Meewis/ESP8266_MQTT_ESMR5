# ESP8266_MQTT_ESMR5
Smartmeter ESMR5 port P1 gateway to MQTT

A smart energy meter with a P1 port with the ESMR5 protocol produces every second an ascii string of data of the electic and gas meters.
The serial RX of the ESP8266 is interfaced to P1 with a signal level converter made by some electronic components.
The P1 port also supply +5V power, enough for the ESP8266 in conjuction with and 5V-to-3.3V converter
The data from the smartmeter is tranmitted seriel to the ESP8266 and the ESP8266 does a MQTT publish to get the data to a MQTT broker
