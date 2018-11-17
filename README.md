My personal HomeAssistant setup with customizations.  Seems like it always a work in progress.
Currently using HomeAssistant version 0.82.0

RaspberryPi Model 3b+
ZWave - Aeotec Z-Stick Gen5


### Lights - GE Zwave Plus Paddle switches
  I prefer smart switching to smart bulbs as it seems cheaper.  $35 or so for a switch vs $20 per bulb.  I can definitely see use cases for bulbs though.

### Climate
Nest Thermostat

### Garage Door Opener

### Garage Door Sensor
  Monoprice Z-Wave Garage Door Sensor.  Simply mounted about 5 feet up on the door.  This detects garage door open or closed.

### Door Sensors

Ga

### SpaceX Launch Information
  Uses SpaceX API as a sensor to get next launch information from SpaceX.  
  https://api.spacexdata.com/v3/launches

### Freezer Temperature Sensor

### Water Softener Salt Level Sensor

### Internet Speed Test
Tests the speed every 6 hours, gets download and upload bandwidth as well as latency.

### Cameras
I run Ubiquiti Unifi on a virtual machine using vagrant and virtualbox.  Homeassistant has an api key into that system

| Camera Model          |
| --------------------- |
| Ubiquiti UVC-Dome     |
| Ubiquiti UVC-G3       |
| Ubiquiti MVC-Micro    |
| Ubiquiti UVC-G3-Micro |
