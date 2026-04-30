# Smart-parking-system

## . Project Overview
The Smart Parking System is an automated solution developed using Arduino UNO and simulated in Tinkercad. It efficiently manages parking spaces by detecting vehicles using ultrasonic sensors and controlling entry and exit gates using servo motors. The system provides real-time parking status through an OLED display and LED indicators, reducing manual effort and improving parking efficiency.

## . Key Features
- Automatic vehicle detection using ultrasonic sensors  
- Servo motor-based gate automation (entry and exit)  
- Real-time parking slot status display using OLED and LEDs  
- Fast and efficient operation  
- Automatic update of slot status (occupied/vacant)  
- Simple, cost-effective, and easy to implement  
- Fully simulated in Tinkercad  

## . Components Used
- Arduino UNO  
- Ultrasonic Sensors (HC-SR04) × 2  
- Servo Motors × 2  
- OLED Display (I2C)  
- LEDs with resistors  
- Breadboard  
- Jumper wires  
- 5V Power Supply  

## . Working Principle
The system continuously monitors the parking area using ultrasonic sensors. When a vehicle is detected within a distance of 10–15 cm, the Arduino processes the input and activates the servo motor to open the gate. After the vehicle enters, the system updates the parking slot status as occupied using LEDs and displays the information on the OLED screen. Similarly, at the exit, when a vehicle is detected, the gate opens and the slot is marked as vacant. This ensures smooth and automated parking management.

## . Applications
- Shopping malls  
- Office buildings  
- Hospitals  
- Airports and railway stations  
- Smart city infrastructure  

## . Troubleshooting

### . Sensor not detecting vehicle
- Check TRIG and ECHO pin connections  
- Ensure correct detection range (10–15 cm)  
- Verify power supply  

### . Servo motor not working
- Check signal pin connection  
- Ensure common ground connection  
- Verify correct pin configuration in code  

### . OLED display not showing output
- Check SDA (A4) and SCL (A5) connections  
- Verify I2C address in code  
- Ensure required libraries are installed  

### . Incorrect slot status
- Recheck sensor placement  
- Use Serial Monitor for debugging values  

## . Conclusion
This project demonstrates an efficient and automated parking system using Arduino, sensors, and actuators. It reduces manual effort, saves time, and provides real-time parking management, making it suitable for modern infrastructure.
