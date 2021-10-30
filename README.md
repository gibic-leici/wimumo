# WIMUMO

[WIMUMO](https://labs.ing.unlp.edu.ar/gibic/?page_id=857) (from WIreless MUltiMOdal acquisition platform) is a device capable of acquiring biopotential signals from the body and transmitting them over WiFi.  

Specifically, it measures electromyographic and electrocardiographic signals (from the muscles and hearth respectively). It is designed as a low-cost, easy to build, and easy to use platform. 

It was born as a device for use in artistic performances, measuring signals produced by a performer's body and transmitting them using the OSC protocol to produce images and sound. 

The project consists in:
- A hardware platform built with low-cost electronic components such as ESP32 and the now almost vintage LM324 amplifier, 3D-printed housing, and commonplace audio and textile supplies.  
- Firmware programmed in the Arduino IDE using high an low level ESP32 libraries to provide simplified internet connection, signal measurement, processing, and delivery to a web page via websockets and/or to any local IP and port address using the OSC protocol. 

When the project reaches an appropriate maturation level, hardware and software will be made available. 

WIMUMO is developed by researchers at [GIBIC](https://www.gibic.ar), [LEICI (CONICET-UNLP-CIC)](http://leici.ing.unlp.edu.ar/)
