<div align="center">

# 📡 RFID Attendance System

### Smart Attendance Management using ESP32, RFID & Google Sheets

<img src="images/rfid-attendance-system.png" alt="RFID Attendance System Banner" width="100%">

<br>

![ESP32](https://img.shields.io/badge/ESP32-IoT-red?style=for-the-badge&logo=espressif)
![RFID](https://img.shields.io/badge/MFRC522-RFID-success?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Arduino-IDE-blue?style=for-the-badge&logo=arduino)
![Google Sheets](https://img.shields.io/badge/Google-Sheets-34A853?style=for-the-badge&logo=googlesheets)

</div>

---

# 🚀 About the Project

The **RFID Attendance System** is an IoT-based smart attendance solution built using the **ESP32** and **MFRC522 RFID Reader**.

When a registered RFID card or tag is scanned, the ESP32 verifies the UID, records the current **Date**, **Time**, and **Attendance Status (Check-In / Check-Out)**, then uploads the information directly to **Google Sheets** through Wi-Fi.

---

# 📸 Project Gallery

## RFID Attendance Hardware

<p align="center">
<img src="images/rfid-system.png" width="850">
</p>

---

## Google Sheets Attendance Log

<p align="center">
<img src="images/google-sheet-output.png" width="850">
</p>

---

# ✨ Features

- 📶 ESP32 Wi-Fi Connectivity
- 🪪 RFID Card & Tag Authentication
- ⏰ Real-Time Date & Time
- 📊 Google Sheets Integration
- ✅ Automatic Check-In / Check-Out
- ⚡ Fast Processing
- 🔒 Secure UID Verification
- 🌐 Cloud Data Storage

---

# 🛠 Hardware Components

| Component | Description |
|-----------|-------------|
| ESP32 | Main Controller |
| MFRC522 | RFID Reader |
| RFID Cards / Tags | User Identification |
| Breadboard | Prototype |
| Jumper Wires | Connections |
| USB Cable | Power Supply |
| Wi-Fi | Internet Connection |

---

# 🔌 ESP32 ↔ MFRC522 Connections

| MFRC522 | ESP32 |
|----------|-------|
| SDA | GPIO 5 |
| SCK | GPIO 18 |
| MOSI | GPIO 23 |
| MISO | GPIO 19 |
| RST | GPIO 22 |
| 3.3V | 3.3V |
| GND | GND |

---

# 🔄 Working Flow

```text
RFID Card / Tag
        │
        ▼
MFRC522 Reader
        │
        ▼
ESP32
        │
        ▼
UID Verification
        │
        ▼
Date & Time
        │
        ▼
Google Sheets
```

---

# 📂 Repository Structure

```text
RFID-Attendance-System/
│
├── README.md
├── code/
├── docs/
├── hardware/
└── images/
    ├── rfid-attendance-system.png
    ├── rfid-system.png
    └── google-sheet-output.png
```

---

# 🚀 Getting Started

### Requirements

- Arduino IDE
- ESP32 Board Package
- MFRC522 Library
- SPI Library
- WiFi Library

### Steps

1. Connect the ESP32 and MFRC522.
2. Install the required libraries.
3. Enter your Wi-Fi credentials.
4. Upload the code.
5. Scan an RFID card or tag.
6. View attendance in Google Sheets.

---

# 📊 Applications

- College Attendance
- School Attendance
- Office Attendance
- Library Management
- Hostel Entry System
- Employee Tracking

---

# 🔮 Future Scope

- Android Application
- Firebase Integration
- Face Recognition
- Fingerprint Authentication
- Web Dashboard
- Email Notifications
- Attendance Analytics

---

# 👨‍💻 Author

## Mukul Vaid

**IoT Developer • ESP32 Projects • Embedded Systems**

---

# 📜 License

This project is developed for educational purposes.

---

<div align="center">

## ⭐ If you like this project, please give it a Star!

**Made with ❤️ using ESP32 & RFID**

</div>
