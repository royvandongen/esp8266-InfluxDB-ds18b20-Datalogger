===ESP8266 InfluxDB Data logger ( DS18B20 Sensor )===

This sketch can be used to create a data logger with a single DS18B20 or multiple DS18B20 sensors. At system boot this software will perform an OneWire scan to see what sensors are connected.

When the update times passes by, all the connected sensors will be sensing an update to the InfluxDB server.

Fill in your variables ( SSID, Password, InfluxDB server ) and you're ready to log!

Please note, NTP code is available because this is needed for some logging platforms. At this moment it is not used.

NTP Code written by Niek Blankers https://www.github.com/niekproductions
