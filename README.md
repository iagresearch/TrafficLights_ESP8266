# TrafficLights_ESP8266
Arduino code to operate the Traffic Lights via wifi  using WeMos.CC D1 boards

There is currently two versions of the traffic lights - one using a cheap 128x64 OLED display, the other without the display.
#Note:  The green control wire had to move to a different GPIO pin, to make way for the I2C bus control when using the ESP8266, as there are some shared pins involved.

The wiring diagram has been included here for the OLED version as well.  
