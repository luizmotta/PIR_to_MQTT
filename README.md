# This is a Wemos D1 Mini sketch that reads a PIR sensor and publishes data to a MQTT server
 
1) Connect your PIR sensor to power (5V and GND) and connect DATA to any digital input pin of the board
2) Copy config.h.sample to config.h
3) Edit your newly created config.h to add your wifi, MQTT, OTA credentials and input pin 
4) Compile and upload the sketch to your board and wait for the data to be published to your MQTT server

The board must be running continuously to read the PIR so a mains power adapter is a better choice than a battery, which could be depleted quickly.

This sketch supports OTA for wireless updates