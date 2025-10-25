🦺 Safety Guardian Bag
Smart Safety Bag for Women and Emergency Situations
📘 Overview

The Safety Guardian Bag is an IoT-based smart safety device designed to help women and travelers during emergencies.
It’s an embedded system project that automatically sends alerts, location, and sound alarms during unsafe or panic situations.

This project combines electronics, sensors, and IoT connectivity to create a portable safety solution that can be easily carried as a normal bag.

⚙️ Technologies & Components Used
🔧 Hardware Components

Arduino Uno / NodeMCU (ESP8266) – Microcontroller for system control

GPS Module (NEO-6M) – Tracks real-time location

GSM Module (SIM800L / SIM900) – Sends alert messages to emergency contacts

Buzzer / Alarm – Alerts nearby people during emergencies

Push Button (SOS Button) – Activates the emergency system

Power Supply / Battery Pack – For portability

Bag (Wearable Unit) – Contains all components securely

💻Software Used

Arduino IDE (for programming and simulation)

Embedded C / C++ (for microcontroller code)

IoT Dashboard / Serial Monitor (for testing and debugging)

Project Idea

The goal is to reduce response time during emergencies by creating a portable system that can instantly:

Send an SMS alert to pre-saved contacts.

Include the GPS location of the user in the message.

Trigger a loud alarm/buzzer to attract public attention.

Optionally send data to an IoT cloud or mobile app for real-time tracking.

⚙️ Working Principle

When the user presses the SOS button, the microcontroller activates the emergency mode.

The GSM module sends an alert SMS containing:

Emergency message

Real-time GPS coordinates

The buzzer turns on to alert people nearby.

The system can be reset only by a secure button or code to prevent false alarms.

📡 Example Output (SMS Alert)
⚠️ EMERGENCY ALERT ⚠️
I am in danger! Please help me.
Location: https://maps.google.com/?q=12.9716,77.5946

📁 Project Structure
Safety_Guardian_Bag/
├── Arduino_Code/
│   └── safety_guardian_bag.ino
├── Circuit_Diagram/
│   └── safety_guardian_schematic.png
├── Components_List.txt
├── Project_Report.pdf
├── Images/
│   ├── Prototype.jpg
│   ├── Bag_Setup.jpg
│   └── Working_Demo.jpg
└── README.md

🚀 Features

✅ One-click emergency alert (SOS button)
✅ Sends SMS with live GPS location
✅ Triggers loud alarm for attention
✅ Compact and rechargeable
✅ Low-cost, real-time safety solution

🧱 Advantages

Provides immediate help during danger

Can be easily carried anywhere

Works independently without internet (via GSM)

Low-cost solution (< ₹3000 total)

Customizable for students, women, and travelers

📸 Prototype Demo (Add when ready)

✅ Circuit connection image

✅ Final bag photo

✅ SMS alert screenshot

🧰 Future Improvements

Add mobile app integration using IoT platform (Blynk / Firebase)

Include temperature or motion sensors for additional safety detection

Integrate voice command activation

🧑‍💻 Contributors

Vigneswaran – Developer & Hardware Designer , Kavinesh - Developer & Hardware Designer
