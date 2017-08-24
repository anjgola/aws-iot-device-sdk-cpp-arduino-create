# aws-iot-device-sdk-library-for-arduino-create
This library enables the use of the [AWS IOT Device SDK for CPP](https://github.com/aws/aws-iot-device-sdk-cpp) in the Arduino Create IDE. 

* It organizes the SDK according to specifications of the 
[Library Specifications](https://github.com/arduino/Arduino/wiki/Arduino-IDE-1.5:-Library-specification). 
* It updates the samples to work in the Arduino Create environment. 
* It updates the samples to use the secret tab feature.


To update the library based on updates in the original SDK : 
1. Do a fresh clone of the AWS IOT Device SDK for CPP. 
2. Run script.sh. This script organizes the SDK the way Arduino Create IDE expects it to be. It also creates an overall header file that includes all other header files. 
3. Pay special attention to Licensing files being in the correct place.
4. Overwrite the samples code.


