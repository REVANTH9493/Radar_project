# Radar project
🛰️ Arduino RADAR System with Ultrasonic Sensor and Servo
This project simulates a simple RADAR system using an Arduino, an ultrasonic sensor (HC-SR04), and a servo motor. The servo rotates the ultrasonic sensor from 15° to 165° and back, continuously scanning the surrounding area and measuring distances. The data is printed via the Serial Monitor in a format that can be visualized or processed further.

🔧 Components Used
Arduino Uno

HC-SR04 Ultrasonic Sensor

SG90 Servo Motor

Jumper Wires

Breadboard

USB Cable

🧠 How It Works
The servo sweeps back and forth in a 150° arc (15° to 165°).

At each angle, the ultrasonic sensor sends out a sound pulse.

It calculates the distance based on the time taken for the echo to return.

Angle and distance data are output via Serial in the format:

matlab
Copy
Edit
angle,distance.
📦 Features
Real-time obstacle scanning and distance detection

Easy to connect with external radar visualizer tools (like Processing or Python)

Compatible with both Windows and macOS versions of Arduino IDE

🚀 Getting Started
Upload the code to your Arduino board.

Open the Serial Monitor at 9600 baud.

Watch angle-distance data stream as the servo rotates.

📁 Code Credits
Original code by Dejan Nedelkovski

macOS compatibility adapted by Niam Moltta

Minor tweaks and documentation by [N. Revanth]
