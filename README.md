# Sigfox Devices for IoT

An end-to-end Internet of Things (IoT) monitoring project using the Sigfox LPWAN network and multiple cloud platforms.

> **Project Year:** 2017
> **Status:** Completed (Archived Project)

## Overview

This project was developed in **2017** to evaluate the capabilities of the **Sigfox Low-Power Wide-Area Network (LPWAN)** for transmitting sensor data over long distances with minimal power consumption.

The objective was to test:

* Reliable sensor data transmission over the Sigfox network
* Signal strength and radio communication performance
* Integration with multiple IoT cloud platforms
* Real-time notifications through messaging services

This project was originally shared on my X (formerly Twitter) account:
**https://x.com/NimicMe**

---

## About Sigfox

Sigfox is a proprietary Low-Power Wide-Area Network (LPWAN) technology designed for IoT devices that transmit small amounts of data while consuming very little battery power.

Unlike LoRaWAN, which is an open standard, Sigfox operates as a closed, managed network.

Sigfox communicates over the ISM radio spectrum, with operating frequencies varying by region. For example, Singapore operates between **920–923 MHz**.

---

## Project Architecture

```text
Sensors
    │
    ▼
Sigfox Development Board
    │
    ▼
Sigfox Network
    │
    ├── ThingSpeak Dashboard
    ├── Ubidots Dashboard
    ├── Slack Notifications
    └── Telegram Notifications
```

---

# Project Showcase

## 1. Sigfox Development Board

The Sigfox development board provided by UnaBiz was used to collect sensor data and transmit it over the Sigfox network.

<img width="1536" height="2048" alt="sigfoxboard1" src="https://github.com/user-attachments/assets/f366350a-2b17-494c-b8f3-3b9c66063496" />

<img width="1536" height="2048" alt="sigfoxboard" src="https://github.com/user-attachments/assets/43322483-2b0a-45d4-9616-66c28cc2e2db" />

---

## 2. Device Registration

The Sigfox device was registered and configured before transmitting sensor data to cloud services.

<img width="2048" height="1536" alt="deviceReg" src="https://github.com/user-attachments/assets/bddd356e-724d-432e-b0e5-ec2633105d1a" />

---

## 3. ThingSpeak Integration

Sensor data was successfully forwarded to ThingSpeak for visualization and monitoring.

<img width="1536" height="2048" alt="sigfox_dash" src="https://github.com/user-attachments/assets/7bcd18fc-c720-4896-ac03-4efd3954eadb" />

<img width="1536" height="2048" alt="sigfox_dash1" src="https://github.com/user-attachments/assets/dc570b5b-b66d-4865-a4da-9e4c589783b3" />

---

## 4. Signal Strength Monitoring

The Sigfox backend provided radio communication statistics, including signal strength and network information for transmitted messages.

<img width="2048" height="1536" alt="sigfox_sig_strength" src="https://github.com/user-attachments/assets/ba16edae-56cd-4801-8ae5-944a5d97f282" />

---

## 5. Ubidots Dashboard

Sensor data was also integrated with the Ubidots IoT platform for dashboard visualization and monitoring.

<img width="2048" height="1536" alt="sigfox_to_ubidots" src="https://github.com/user-attachments/assets/c104b63b-6e8a-45de-a9bc-c7cac2255811" />

<img width="2048" height="1536" alt="sigfox_to_ubidots1" src="https://github.com/user-attachments/assets/4f38f678-82a4-4958-954e-911eabcd7f7e" />

---

## 6. Slack Notifications

Incoming Sigfox messages were forwarded to Slack for real-time event notifications.

<img width="1536" height="2048" alt="sigfox_to_slack" src="https://github.com/user-attachments/assets/137f5edf-a22f-4b2c-8298-fe01abaf8754" />

---

## 7. Telegram Notifications

Sensor events were also delivered to Telegram, enabling mobile monitoring and alerts.

<img width="2048" height="1536" alt="sigfox_to_telegram" src="https://github.com/user-attachments/assets/fdc9044e-3426-455b-ac76-a8da8bd75abf" />

---

## 8. GPS Module for positioning
<img width="2048" height="1536" alt="image" src="https://github.com/user-attachments/assets/9a4d98af-4ce3-42d7-9234-e5eeb1c0e3d9" />

<img width="2048" height="1536" alt="image" src="https://github.com/user-attachments/assets/c79df2b6-6b57-423b-97d0-a95b4940f150" />






# Technologies Used

* Sigfox LPWAN
* UnaBiz Sigfox Development Board
* ThingSpeak
* Ubidots
* Slack API
* Telegram Bot API
* ISM Radio (920–923 MHz)

---

# Key Learning Outcomes

* Deploying devices on the Sigfox LPWAN network
* Integrating IoT devices with cloud platforms
* Monitoring wireless signal quality and radio performance
* Implementing real-time notification systems
* Building an end-to-end IoT data pipeline

---

## Notes

Although this project was completed in **2017**, it demonstrates practical experience with LPWAN technologies, cloud IoT integration, and remote monitoring solutions. While some services and interfaces have evolved since then, the overall architecture and concepts remain relevant for modern IoT systems.
