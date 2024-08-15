NAME-NANDITHA.D
COMPANY NAME-CODTECH IT SOLUTIONS
ID-CT08DS5382
DOMAIN-EMBEDDED SYSTEM
DURATION-JULY 20 TO AUGUST 20th,2024
### Project Overview: Temperature and Humidity Monitoring using DHT11 and Arduino

This project involves building a simple temperature and humidity monitoring system using an Arduino Uno and a DHT11 sensor. The system reads real-time temperature and humidity data and displays it on the Serial Monitor.

#### **Components Required:**
1. **Arduino Uno**: The microcontroller board that reads and processes sensor data.
2. **DHT11 Sensor**: A temperature and humidity sensor that outputs digital data.
3. **Breadboard and Wires**: For connecting the components.
4. **DHT Library**: A library that simplifies communication with the DHT11 sensor.

#### **Project Functionality:**
- The DHT11 sensor measures the temperature and humidity in the environment.
- The Arduino reads this data and sends it to the Serial Monitor, where it is displayed in a user-friendly format with units (°C for temperature and % for humidity).
- The data is updated every second.

#### **How It Works:**
1. **Sensor Connection:**
   - The DHT11 sensor has 3 pins:
     - **S (Signal)**: Connected to pin 7 on the Arduino.
     - **+ (VCC)**: Connected to the 5V pin on the Arduino.
     - **- (GND)**: Connected to the GND pin on the Arduino.

2. **Arduino Setup:**
   - The Arduino is programmed to read data from the DHT11 sensor using the `dht` library.
   - The temperature and humidity data are then displayed on the Serial Monitor.

3. **Serial Monitor Display:**
   - The Serial Monitor shows the temperature in degrees Celsius and the humidity as a percentage, updating every second.

#### **Project Workflow:**
1. **Setup Phase:**
   - The Arduino initializes serial communication and sets up the sensor connection.

2. **Loop Phase:**
   - The sensor readings are continuously taken.
   - The temperature and humidity data are printed on the Serial Monitor.

#### **Applications:**
- **Weather Stations**: Monitor indoor or outdoor environmental conditions.
- **Smart Homes**: Control HVAC systems based on temperature and humidity levels.
- **Greenhouses**: Maintain optimal conditions for plant growth.

### Conclusion:
This project is a simple yet effective introduction to environmental sensing using Arduino. It is a great starting point for understanding how sensors work and how to interact with them programmatically. By understanding this project, you can expand to more advanced IoT or home automation projects.
