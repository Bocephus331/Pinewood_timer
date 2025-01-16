# Pinewood_timer
This code will work with ardunino. 
This configuration is a two lane, with no starting optic sensor or switch. Additionally there is no timer.  
Code is designed to blink lane led to show winning car for thirty seconds, at which time it will reset  and will be ready for the next race. 
Current setup uses three pin Reflective Photoelectric Module. 

IR Infrared wiring: 
GND -> GND
VCC -> Connect to 5v Arduino pin 
Out -> Connect lane1sensor to  digital Pin2 / Connect lane2sensor to digital Pin3
