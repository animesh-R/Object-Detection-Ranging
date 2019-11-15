# Object-Detection-Ranging
Designed to obtain information about distance and angle if there is any object in its operating range to detect and prevent intrusion from unidentified aerial vehicles.  It employs Arduino as communication medium between sensor and display device(Laptop). For display of graph, we used processing software based on Java environment. Serial Peripheral Interface(SPI) protocol is used as a bridge of communicating.
The basic objective of our design is to ascertain the distance position and speed of the obstacle set at some distance from the sensor. 
Ultrasonic sensor sends the ultrasonic wave in various ways by rotating with help of servo motors. 
This wave goes in air and gets reflected back subsequent to striking some object. 
This wave is again detected by the sensor and its qualities is analyzed and output is shown in screen indicating parameters, 
for example, distance and position of object. 

Arduino IDE is utilized to compose code and transfer coding in Arduino and causes us to detect position or angle of servo motor 
and it is communicated through the serial port alongside the covered distance of the nearest object in its way. 
Output of all of this working is shown in the software called processing, 
it will display the input/output and the range of the object. 
Implementations of the sensors are done in such a way that ultra-sonic sensor is attached on top of the servo motor because it has to detect the object and its distance. 
Arduino (micro-controller) will control the ultra-sonic sensor and servo motor and also powered will be given to both of them through micro-controller.
