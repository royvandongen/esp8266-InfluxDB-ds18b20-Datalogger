===ESP8266 InfluxDB Data logger ( DS18B20 Sensor )===

This sketch can be used to create a data logger with a single DS18B20 or multiple DS18B20 sensors. At system boot this software will perform an OneWire scan to see what sensors are connected.

When the update times passes by, all the connected sensors will be sensing an update to the InfluxDB server.

In this latest release i made an upgrade, You can now fill in your variables via the WiFiManager ( on first boot ). Just connect to the SENSOR-DS18B20-***** network and fill in all the fields.

If one field is missing, the device will become an AP again so you can change the values.

Please note, NTP code is available because this is needed for some logging platforms. At this moment it is not used.

NTP Code written by Niek Blankers https://www.github.com/niekproductions
