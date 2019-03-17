# Smart Garbage Monitoring System using IoT

### This program will get the distance from the HC-SR04 Ultrasonic sensor and upload it to Thingai cloud platfrm to monitor and visualize the data
The required connection for this program may be :

HC-SR04--> NodeMCU        
1. trig --> d5 of NodeMCU

2. echo --> d6 of NodeMCU

3. vcc --> vin of NodeMCU (remember NOT 3v3)

4. gnd --> gnd of NodeMCU 

->measured distance from the sensor gives output in cm unit
 (0.034 is the cm per uS)

->pulsein : Reads a pulse (either HIGH or LOW) on a pin.For example, if value is HIGH, pulseIn() waits for the pin to go HIGH, starts timing,then waits for the pin to go LOW and stops timing. Returns the length of the pulse in microseconds.
 LED is used here to give an alarm when the remaining level of tank is less than or equals to 20 cm.  