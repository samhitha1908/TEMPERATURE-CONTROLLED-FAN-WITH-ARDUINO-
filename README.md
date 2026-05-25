## TEMPERATURE-CONTROLLED-FAN-WITH-ARDUINO :
An automatic temperature-controlled fan system built using Arduino Uno, DHT11 Temperature Sensor, and L298N Motor Driver.
The fan automatically adjusts its speed based on room temperature, helping to save energy and provide efficient cooling.

## Project Overview
This project uses an Arduino Uno to monitor the surrounding temperature through a DHT11 sensor.
When the temperature rises, the Arduino automatically turns ON the fan and controls its speed using PWM (Pulse Width Modulation).

This system is useful for:
🏠 Home Automation
💻 Electronic Cooling Systems
🌱 Smart Agriculture
🖥️ Server Rooms
🏭 Industrial Temperature Monitoring

## Components Used
ComponentQuantityArduino Uno1DHT11 Temperature Sensor1L298N Motor Driver1DC Fan / Motor1Jumper WiresAs RequiredSwitch1Rechargeable Power Supply1

# Working Principle

The DHT11 sensor reads the surrounding temperature.
The Arduino Uno processes the temperature value.
Based on preset temperature limits:
❄️ Low Temperature → Fan OFF
🌤️ Medium Temperature → Fan runs at medium speed
🔥 High Temperature → Fan runs at full speed
PWM (Pulse Width Modulation) is used for smooth fan speed control.


## Temperature Conditions
Temperature RangeFan StatusBelow 25°CFan OFF25°C – 40°CFan speed increases graduallyAbove 40°CFan runs at full speed


## Circuit Connections
📍 DHT11 Sensor Connections
DHT11 PinArduino PinVCC5VGNDGNDDATADigital Pin 2
📍 L298N Motor Driver Connections
L298N PinArduino PinENAPin 5IN1Pin 6IN2Pin 7
📍 Fan Connection
Connect the DC Fan to the output terminals of the L298N Motor Driver.

## How to Run the Project
Step 1
Connect all components properly according to the circuit diagram.
Step 2
Install the DHT Sensor Library in the Arduino IDE.
Step 3
Upload the Arduino code to the Arduino Uno.
Step 4
Open the Serial Monitor.
Step 5
Observe temperature readings and automatic fan speed control.

## Features
✅ Automatic Fan Control
✅ Energy Efficient System
✅ PWM-Based Speed Variation
✅ Low-Cost Implementation
✅ Simple and Easy to Build
✅ Real-Time Temperature Monitoring

## Future Improvements
📱 IoT-Based Mobile Control
📟 LCD Display Integration
🏠 Smart Home Automation Support
🎙️ Voice Assistant Integration
☀️ Solar-Powered System
🤖 AI-Based Temperature Prediction


## Output
❄️ Fan remains OFF at low temperature
🌤️ Fan speed increases as temperature rises
🔥 Full-speed cooling at high temperature

## Applications
🏠 Smart Homes
💻 Computer Cooling Systems
🌱 Greenhouses
🏭 Industrial Automation
🏥 Medical Equipment Cooling
🖥️ Server Room Ventilation

## Conclusion
The Temperature Controlled Fan using Arduino is a simple and efficient automation project that controls fan speed according to environmental temperature.
It helps reduce power consumption and improves cooling performance using embedded system concepts.
