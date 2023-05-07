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
When the code is run , the serial monitor will show the following <br>         
![serial monitor](https://user-images.githubusercontent.com/109460604/236690702-ee1ea1c7-15c6-4113-8609-c1672d917ae1.jpg)

The local id generated in the serial monitor when typed into a browser (connected to the same wifi) we get the below webpage <br>            ![web page](https://user-images.githubusercontent.com/109460604/236690569-42aa8068-2799-42b5-8271-3644c7868d52.jpg)
  
The overall circuit is as shown below  <br>       
![the circuit](https://user-images.githubusercontent.com/109460604/236690580-5da602a3-53fa-46e7-8fa8-37cf7c857262.jpg)

The connections are as follows :
1) The IOT cube connections  <br>  
   ![iot cube connections](https://user-images.githubusercontent.com/109460604/236690596-03693664-2df0-4492-9484-ec568273ba61.jpg)
 
2) The PTC heater connections  <br>  
    ![Ptc heater connections](https://user-images.githubusercontent.com/109460604/236690620-abf3f78f-f153-406f-9f79-28bbfd207472.jpg)
  
          



