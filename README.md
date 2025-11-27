# Smart Room Management System

## Overview
This project is a prototype system designed to monitor room occupancy and control the indoor environment using sensors and automated mechanisms.  
The idea originated during the COVID-19 period, where overcrowding in closed spaces became a critical safety issue. Studies showed that high occupancy levels and poor ventilation significantly increased the risks of suffocation and virus transmission.

## System Purpose
- Count the number of people inside a room using ultrasonic sensors.
- Display the live occupancy count on a 4-digit TM1637 display.
- Control a 12V fan based on room temperature.
- Adjust fan speed dynamically — higher temperatures increase fan speed, and lower temperatures reduce it.
- This prototype demonstrates how smart environments can help reduce overcrowding risks and improve air quality in shared indoor spaces.

## How It Works: 
**Occupancy Counting**
- Two ultrasonic sensors detect entry and exit.
- Each detection updates the occupancy count.
- The live count appears on the TM1637 display.
- If the room exceeds its safe capacity (future version), the system can trigger alerts or lock further entry.

**Temperature Monitoring & Fan Control**
- A temperature sensor reads the room’s temperature continuously.
- When temperature rises, the fan turns on.
- Fan speed increases with higher temperature thresholds to improve ventilation.

## Hardware Components
- Arduino board  
- Ultrasonic Sensors (Entry/Exit)  
- TM1637 4-Digit Display  
- 12V Fan (4×4)  
- Temperature Sensor  
- Transistors (for fan control)  
- Buzzer  
- Diode  
- Breadboard & wiring  

## Demo Video:
- A short demonstration of the system in action:  
https://drive.google.com/file/d/1zMNII6vpOPzXLju6JpfHt85-VI5F0npG/view?usp=sharing

## Features
- Real-time occupancy counting  
- Automatic temperature-based fan control  
- Dynamic fan speed adjustment  
- Modular code (separated into counters and fan control)  
- Clear circuit and block diagrams  

## Future Improvements
- Adaptive occupancy limits based on room dimensions (e.g., 3×4 vs. 5×5 rooms).
- Integration with hospital systems to divert patients if a room becomes full.
- Automatic alerts for overcrowding (SMS, notifications, alarms).
- Expanding the system for multi-room monitoring.
- Adding cloud connectivity for real-time dashboards.

## Notes
This is a functional prototype demonstrating how smart systems can help manage crowds and improve indoor safety.It can be extended into a complete IoT-based room management solution with relatively small enhancements.

