# Smart School Bus Management System

## Overview
The **Smart School Bus Management System** is an embedded system integrating **RFID** and **GPS tracking** to improve school bus safety, efficiency, and accountability. The system enables real-time tracking, automated attendance logging, and usage-based billing, ensuring transparency for parents and school administrators.

## Features
- **Live Alerts**: Instant notifications to parents and administrators if a student fails to board or alight at the designated stop.
- **Geofencing**: Alerts if the bus deviates from its route or approaches predefined locations.
- **Integrated Dashboard**: A centralized interface displaying real-time bus locations, attendance records, and route adherence.
- **Usage-Based Billing**: Charges parents based on the actual usage of the bus service.

## System Architecture
### **Hardware Components**
- **ESP32 Microcontroller**: Central processing unit
- **RFID Module**: Tracks student attendance
- **GPS Module**: Provides real-time location tracking
- **GSM/GPRS Module**: wireless communication via GSM/GPRS
- **OLED Display**: Displays notifications
- **Wi-Fi Module (ESP32 Built-in)**: Sends data to the cloud
- **Power Supply Circuit**: Ensures stable power delivery
- **Backup Battery**: Supplies power during outages

### **Communication Protocols**
- **I2C**: For OLED display communication
- **UART**: For integrating RFID and GPS modules
- **MQTT**: Real-time data broadcasting to a central dashboard
- **HTTP**: API-based communication between the cloud and dashboard
- **AES Encryption**: Secures RFID attendance logs and location updates

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/amodhyh/school-bus-tracking-system.git
   ```
2. Install required dependencies.
3. Upload the firmware to **ESP32**.
4. Set up the **dashboard** and **cloud services**.
5. Configure **RFID tags** for students.
6. Deploy and test the system.

## Usage
- **Parents & Administrators**: Use the dashboard to track buses and receive alerts.
- **Drivers**: Ensure RFID scanning for students during boarding and alighting.
- **Schools**: Monitor attendance records and implement usage-based billing.

## Wiring Diagram
![Wiring Diagram](https://github.com/user-attachments/assets/8d49ca01-cbd5-48ba-b8ba-bb224206bbc3)


## Contributors
- **Rathnayake U.S** (2020/E/131)
- **Nugegodaarachchi G.L** (2021/E/038)
- **Bandara S.C.M** (2021/E/090)
- **Herath H.M.A.Y** (2021/E/045)

## License
This project is licensed under the MIT License.

## Repository
[GitHub Repository](https://github.com/amodhyh/school-bus-tracking-system.git)

## notes 
This project was developed as part of the **Embedded Systems EC6020** course in University Of Jaffna Faculty of Engineering to gain more hands on experience with the IOT and embedded systems
