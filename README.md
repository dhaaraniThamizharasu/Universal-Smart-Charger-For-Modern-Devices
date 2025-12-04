Universal IoT-Enabled Smart Charger (USB-C PD + ESP32 + LTC3780)
📌 Project Overview

This project presents an intelligent, universal smart charger that supports USB-C Power Delivery, real-time monitoring, and IoT-based remote visibility. It uses a 19V adapter, LTC3780 buck–boost converter, STUSB4500 PD controller, INA219 sensing module, ESP32 WiFi microcontroller, and an OLED display to provide adaptive, safe, and cloud-connected charging for mobiles, laptops, and tablets.

⚡ Features

USB-C Power Delivery (5V–20V)

Buck–Boost voltage regulation using LTC3780

Real-time current, voltage, and power monitoring

ESP32-based IoT monitoring with Blynk

OLED on-device display

Safety monitoring: overload, abnormal power, short-circuit detection

Interchangeable ports (USB-C, USB-A, Barrel Jack)

🧩 System Architecture


<img width="701" height="368" alt="image" src="https://github.com/user-attachments/assets/9095de75-db63-4e1a-98f2-bdf4633961fd" />
<img width="419" height="347" alt="image" src="https://github.com/user-attachments/assets/fe69c18e-075e-4693-b152-566a662a7bb6" />
<img width="425" height="347" alt="image" src="https://github.com/user-attachments/assets/cb8959a7-fb5d-4d9b-9bcb-0a2f4cf2cc8e" />


🔌 Hardware Components
Component	Purpose
19V Adapter	Primary power source
LTC3780	Buck–boost regulation
STUSB4500	USB-C PD negotiation
INA219	Power sensing
ESP32	IoT + control
OLED Display	Local monitoring
Interchangeable Ports	USB-A, USB-C, Barrel
💻 Software

ESP32 Arduino Code

Blynk IoT Dashboard Setup

OLED UI Code

🚀 How It Works

<img width="268" height="185" alt="image" src="https://github.com/user-attachments/assets/e6de8b46-cb1f-4f98-b96c-2d34c3bbfce6" />


The 19V adapter powers the system.

LTC3780 adjusts voltage based on device requirement.

PD controller negotiates USB-C PD profiles.

INA219 measures real-time power data.

ESP32 uploads data to Blynk cloud + displays on OLED.

Output ports charge mobile, tablet, or laptop.

📲 IoT Monitoring (Blynk App)

View voltage, current, and power

Monitor device status

Remote logging

🔮 Future Improvements

Multi-port PD charging

Battery-powered portable version

Fast-charging analytics & prediction

Integration with AWS IoT or Firebase
