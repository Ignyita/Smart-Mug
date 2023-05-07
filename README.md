# Smart-Mug
The Smart Mug project is an innovative device that is designed to maintain the temperature of a beverage at a specified level.       
It is equipped with a temperature sensor, PTC heater  and an Arduino microcontroller, which is programmed to regulate the heating elements inside the mug. The device features a local web interface, which has been developed using the HTML, CSS, and JavaScript languages.     
## Apparatus specifications        
### 1.DHT11 sensor    
Digital temperature and humidity sensors like the DHT11 are inexpensive.  Any micro-controller, including Arduino, Raspberry Pi, etc., may easily interface with this sensor to instantly monitor humidity and temperature.      
The DHT11 sensor is made up of a capacitive humidity measuring element and a thermistor for temperature detection.  A moisture-holding substrate serves as a dielectric between the two electrodes of the humidity sensor capacitor. The capacitance value changes as the humidity level changes. The IC measures, processes, and converts the resistance values into digital form.        
DHT11 has a temperature range of 0 to 50 degrees Celsius with a 2-degree accuracy. This sensor has a humidity range of 20 to 80% with a 5% accuracy. This sensor has a sampling rate of 1Hz, which means it takes one reading per second.  DHT11 is a tiny device with an operational voltage range of 3 to 5 volts. The highest measurement current is 2.5mA.         
### 2.	PTC heater    
12V PTC Heaters Heating Element Hair Dryer Accessories Curlers Heater 220 Degree Celsius Air Heater       
This PTC is used for heating air. Made up of an Aluminum shell, the PTC material has the characteristic that it is the constant temperature on the surface can be dry heated for a long time.          
Applications:    
•	Heater for water, cup, gas      
•	A hair straightener, yogurt maker, Instrumentation dehumidification, Chocolate extrusion, coffee maker     
•	Car and components preheating          
Features:    
•	12V Constant Temperature PTC Heating Element Thermostat Heater Plate      
•	Widely used in foot bath devices, water boiler, yogurt maker, chocolate extrusion, coffee maker      
•	Made of Aluminum shell, eco-friendly, durable, and sturdy to use     
•	Constant temperature and surface insulation, safe to use     
•	Also used for car and components preheating     
•	Can be dry heated for a long time           
Specifications:    
•	Heating Material: PTC Thermistor    
•	Shell Material: Aluminum    
•	Lead wire: Silicone Line    
•	Voltage: 12V    
•	Power: 30W    
•	Surface Dry Heating Temperature: 220ºC   
•	Dimension: 35 x 21 x 5mm (Approx.)    
### 3. DLithe IOT cube (Arduino ESP32)   
### 4. 12V Adaptor   
### 5. Wires
<hr>
When the code is run , the serial monitor will show the following   
![serial monitor](https://user-images.githubusercontent.com/109460604/236690123-3024e250-52ff-408d-ad63-4ad06773a50e.jpg)     
The local id generated in the serial monitor when typed into a browser connected to the same wifi we get the below webpage            
![web page](https://user-images.githubusercontent.com/109460604/236690256-560ab092-01d4-4776-9a7f-c242244e98f1.jpg)       
The overall circuit is as shown below    
![the circuit](ht![iot cube connections](https://user-images.githubusercontent.com/109460604/236690297-ac988374-7d1a-4631-ad50-9db62a7abe34.jpg)    
The connections are as follows :
1) The IOT cube connections    
tps://user-images.githubusercontent.com/109460604/236690280-47a13338-0fcb-41b2-9942-966d3af684f9.jpg)    
2) The PTC heater connections     
![Ptc heater connections](https://user-images.githubusercontent.com/109460604/236690338-656e82ee-9856-47c3-bf92-4690af74ae73.jpg)    



