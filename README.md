# LPG-Gas-Sensor-Interfacing-with-LPC2148
### COMPONENTS REQUIRED
##### LPC2148 Development Board
##### GAS Sensor module
##### LCD Module

### COMPONENT CONNECTION 
#### IR Sensor
##### VCC- 5V
##### GND- Ground
##### DO- P1.24

#### LCD
##### RS-P0.8
##### RW- P0.9
##### EN- P0.10
##### Data Lines- P0.0 – P0.7

### CIRCUIT DIAGRAM
![image](https://github.com/praneethp4/LPG-Gas-Sensor-Interfacing-with-LPC2148/assets/123055147/8c65ba95-3bd3-425d-bf8e-ad815ce9bc0d)

### WORKING
Simply power the module with 5V and you should notice the power LED on the module to glow and when no gas is detected the output LED will remain turned off meaning the digital output pin will be 0V (LOW).
Now, introduce the sensor to the gas you want to detect and you should see the output LED to go HIGH along with the digital pin, if not use the potentiometer until the output gets high.
Now every time your sensor gets introduced to this gas at this particular concentration the digital pin will go high (5V) or else will remain low (0V).
Instead of LED we used LCD display where it displays Gas Detected when gas is actually detected or none.

#### WHEN GAS NOT DETECTED
 ![image](https://github.com/praneethp4/LPG-Gas-Sensor-Interfacing-with-LPC2148/assets/123055147/81949508-e1a3-433a-9df9-743284808b72)

#### WHEN GAS DETECTED
![image](https://github.com/praneethp4/LPG-Gas-Sensor-Interfacing-with-LPC2148/assets/123055147/9ea7d9c2-d797-4f3a-bd89-77fe0e4a8efc)

 
