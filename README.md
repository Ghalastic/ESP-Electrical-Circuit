# ESP Electrical Circuit Design
#### 
## Task Description:
#### 
Design and program any electronic circuit containing ESP with any sensor or electronic part with an explanation of the function of the circuit.
#### 
### Chosen Sensor: Temperature and Humidity Sensor (DHT22)
#### 
A temperature and humidity sensor is a device that detects and measures the temperature and the humidity of its environment and converts that measurement into an electrical signal. These sensors are commonly used in a variety of applications, from industrial processes to consumer products.
#### 
### 1- The Initial Goal:
#### 
To use DHT22 temperature and humidity sensor with ESP32, and to display the output values on I2C LCD.
#### 
### 2- The Function of the Electrical Circuit:
Detects and measures the temperature and the humidity of the surrounding environment and converts that measurement into an electrical signal.
#### 
### 2- Simulation Program:
#### 
Wokwi.
#### 
## Steps:-
#### 
### 1- Gather Components: 
#### 
- ESP32
- DHT22 Sensor
- LCD 16x2 (I2C - has I2C interface)
- VCC Symbol
- GND Symbol
#### 
### 2- ESP32 and DHT22 Connections:
#### 
1- Connect the GND pin on the DHT22 sensor to the GND.1 pin on ESP32  
2- Connect the VCC pin on the DHT22 Sensor to the 3V3 pin on ESP32    
3- Connect the SDA pin on the DHT22 Sensor to the D15 pin on ESP32
#### 
### 3- ESP32 and LCD 16x2 (I2C) Connections:
#### 
1- Connect the VCC Symbol to the VCC pin on the LCD  
2- Connect the GND Symbol to the GND pin on the LCD  
3- Connect the SDA pin on the LCD to the D21 pin on ESP32  
4- Connect the SCL pin on the LCD to the D22 pin on ESP32
#### 
### 4- Write the Code Using the Arduino Programming Language
#### 
### 5- Test:
After running the code that is used to control the electrical circuit, the temperature (in ℃) and the humidity (in %) output values should be displayed on the LCD device. 
#### 
### Link
[Wokwi Electrical Circuit Design](https://wokwi.com/projects/402880151500617729)
 




#### 
## Screenshots
#### 
![‏‏image](https://github.com/Ghalastic/ESP32-Electrical-Circuit/assets/173709501/63e621d4-1694-4ceb-91f1-fe5431ce752d)
#### 
![‏‏image](https://github.com/Ghalastic/ESP32-Electrical-Circuit/assets/173709501/59433be0-5cbf-4d6d-967b-4314379b7147)
