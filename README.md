### Zigbee Base Project ###
A project base for Zigbee ESP32 devices, created for my ESP32 Smart-Home devices

Based on the Espressif Temperature Sensor example project at https://github.com/espressif/arduino-esp32/tree/master/libraries/Zigbee/examples/Zigbee_Temperature_Sensor

### Changes made on-top of the original Espressif source:

* Converted project from Arduino IDE to PlatformIO
* Split Zigbee logic off into its own source files
* Split Switch/button logic off to its own source files
* Added logic to handle the Zigbee "Identify" functionality, via a WS2182 LED on GPIO8
* Added callbacks for Zigbee events to our main application logic
* Restart device automatically if Zigbee network setup fails
* General code tidyup