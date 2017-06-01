# Garduino-ESP-Blynk
A wireless (solar poweed) sensor controlled garden irrigation system.

This is still a work in progress. I'll write up a readme later on but feel free to pick it up and try it out. 

Hardware: 

* 3.3V or 5V Relay Module (HIGH or LOW active)
* ESP8266-Dev (WeMos/NodeMCU style)
* Liquid Flow Meter (I used model YF-S201) 
* 12VDC Solenoid water valves

Software:

* Download this project as a zip and extract to your project directory in its own folder.
* Match the pinouts from the code (settings.h). 
* Download the Blynk mobile app and create a project, add your base and 3 sensors as devices and email yourself the auth codes and put them in the sketchs.
* Create a new folder in your library dir called 'wifi_credentials' and create a new file called 'wifi_credentials.h' and copy the example below. 

```cpp
/**************************************************************
 *           Settings - Wifi Credentials
 **************************************************************/

/*
   Wifi Credentials
*/
#define WIFI_SSID               "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
#define WIFI_PASS               "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
