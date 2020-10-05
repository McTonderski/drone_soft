# drone_soft
This software is a part of UAV - Unmanned aerial vehicle. Software takes video as input and by image processing, commands UAV what to do.


This is based on arduino MultiiWii project with adjustments for basic video processing and RaspberryPi support. 

This code is only for Arduino.

Software uses 2 IMU sensors and GPS for learning its oritentation. 

Raspberry Pi makes final decisions and controls UAV movement.

System works in two steps: 
- Arduino is responsible for first hand reactions like wind gusts and systems failures
- RaspberryPi on the other hand uses its onboard computing power to process images and based on image input decides where drone should be positioned

### Tests
Tested on Arudino Uno.
