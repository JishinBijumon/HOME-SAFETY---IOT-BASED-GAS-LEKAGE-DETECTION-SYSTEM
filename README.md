The Smart Home Security System is a real-time, cloud-connected embedded project designed to monitor environmental safety conditions such as gas leakage and humidity levels. This system uses an ESP8266 Wi-Fi microcontroller to interface with sensors and transmit live data to the Firebase Realtime Database, enabling smart alerts and remote monitoring.

This project demonstrates how embedded systems and IoT can be combined to develop practical, safety-focused solutions for homes or industrial environments. It also showcases sensor data acquisition, wireless communication, cloud integration, and automated alerts using LEDs and buzzers.


🛠️ Hardware Components:

ESP8266 NodeMCU – for Wi-Fi communication and microcontroller functions

Gas Sensor (MQ-series) – to detect the presence of harmful gases

DHT11 Sensor – to measure humidity and temperature

White LED – indicates that the system is powered and running

Red LED – indicates danger when unwanted gas is detected

Buzzer – produces audio alerts based on detection status

Jumper Wires, Breadboard, USB Cable – for circuit prototyping


🌐 Software & Tools Used:

Arduino IDE – for writing and uploading code

Firebase Realtime Database – for storing and displaying live sensor data

Serial Monitor – for real-time debugging and status tracking

Embedded C / Arduino C++ – programming language used for logic and control


⚙️ System Functionality:

System Initialization:

White LED turns ON indicating that the system is powered and ready.

Sensor Monitoring:

The Gas Sensor continuously monitors for harmful gases.

The DHT11 Sensor measures humidity (moisture content) in the air.

Real-Time Alert Mechanism:

When gas levels exceed a threshold, the Red LED turns ON.

After a 2-second delay, the Buzzer begins to beep.

If gas presence continues for 15 seconds, the buzzer frequency increases to indicate elevated danger.

Cloud Integration:

Real-time data from both the gas and humidity sensors are sent to Firebase Cloud, where it can be monitored remotely.

This allows the system to be integrated with mobile apps or dashboards in future extensions.

Serial Monitoring:

The status of the network connection, sensor initialization, and live sensor readings are printed on the Serial Monitor for debugging and tracking.


🎯 Learning Outcomes:

Through this project, we gained hands-on experience and a deeper understanding of:

Working with ESP8266 for wireless communication

Real-time sensor data acquisition and processing

Interfacing multiple input/output components (LEDs, buzzers, sensors)

Programming in Arduino C

Sending and retrieving data from Firebase Realtime Database

Handling timing logic and implementing conditional operations

Debugging using the Serial Monitor

Applying IoT principles to solve real-world safety problems



