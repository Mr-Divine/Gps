📡 GPS Tracking System Using SIM868 & STM32

This repository contains a hardware + firmware prototype of a GPS-based tracking system built around the SIM868 GSM/GPRS + GNSS module and an STM32 microcontroller.

The project is currently in development / production stage, and this repository is published only as a technical sample and proof of capability.

🚀 Key Features
🛰 Real-Time GPS Tracking

Acquisition of live GPS coordinates

Support for GNSS positioning (GPS / GLONASS / BDS depending on configuration)

📡 Wireless Data Transmission

GPRS data upload to remote servers or cloud platforms

SMS-based location reporting for offline/backup communication

Suitable for private server or third-party IoT platforms

🔋 Low-Power Embedded Design

Optimized power management for battery-operated devices

Ideal for long-term outdoor / mobile use cases

🔗 Easy System Integration

Can be connected to mobile apps, tracking dashboards, or MQTT/REST APIs

Hardware and firmware structure designed for scalable upgrades

🛠 Applications

✔ IoT asset and container tracking
✔ Vehicle and fleet monitoring
✔ Personal safety / wearable trackers
✔ Smart mobility and logistics systems
✔ Field monitoring and security devices

📁 Repository Status

⚠ This is not the final production release.
Some files, firmware code, and documentation have been intentionally omitted due to ongoing development.

This repository serves as:

A portfolio/sample work showcase

A technical demonstration of experience in STM32 embedded design, GSM/GPRS communication, and GNSS positioning modules

Full production documentation, code, and PCB revisions are maintained privately.

🧩 Technology Stack

MCU: STM32 Series (ARM Cortex-M)

Cellular / GNSS Module: SIM868

Communication: AT commands via UART interface

Data output formats: NMEA (GPS), JSON / text frames for server transmission

PCB Toolchain: Altium Designer (prototype layout)
