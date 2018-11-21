My personal HomeAssistant setup with customizations.  Seems like it always a work in progress.
Currently using HomeAssistant version 0.82.0

RaspberryPi Model 3b+  
[ZWave - Aeotec Z-Stick Gen5](https://aeotec.com/z-wave-usb-stick)


### Lights
GE Zwave Plus Paddle switches  
  This got me into homeautomation in the first place.  Uses the sun sensor to determine sunset and sunrise and there is an autmoation to turn on/off the lights based on that data.

### Climate
Nest Thermostat

### Garage Door Opener
  Garage doors open and shut based on a simple on/off relay setup.  Using a Wemos D1 Mini, 5v Relay, and MQTT.  
  Credit to [DrZzs Youtube Tutorial](https://github.com/aderusha/MQTTCarPresence).  

### Automated Garage Door Close and Shut
  A Wemos D1 Mini is inside my car configured to connect to wifi and send messages over MQTT.  This powers on when the car is put in accessory mode which then tells the garage door to open.  30 seconds after I leave it then tells the door to close.  
  Similar setup for coming home.  Open as soon as it connects to wifi, and give it 1 minute until it closes the door.  
  Credit to [aderusha](https://github.com/aderusha/MQTTCarPresence).

### Garage Door Sensor
  [Monoprice Z-Wave Garage Door Sensor](https://www.monoprice.com/product?p_id=11987).  Simply mounted about 5 feet up on the door.  This detects garage door open or closed.

### Door Sensors
  [Monoprice Z-Wave Plus door and Window Sensor](https://www.monoprice.com/product?p_id=24259).  These 2 piece sensors use a magnet to detect open/close.  On flat doors with no trim I mount high on the top left of the door.  Have some doors with an inside trim piece so for those I've mounted on the bottom near the hinges and that's worked pretty well.

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
