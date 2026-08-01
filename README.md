<div align="center">

# 📡 RFID Attendance System

### Smart Attendance Management using ESP32, RFID & Google Sheets

<img src="./images/RFID attendence system.png" alt="RFID attendence system.png" width="100%">

<br>

![ESP32](https://img.shields.io/badge/ESP32-IoT-red?style=for-the-badge&logo=espressif)
![RFID](https://img.shields.io/badge/MFRC522-RFID-success?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Arduino-IDE-blue?style=for-the-badge&logo=arduino)
![Google Sheets](https://img.shields.io/badge/Google-Sheets-34A853?style=for-the-badge&logo=googlesheets)

</div>

---

# 🚀 About the Project

The **RFID Attendance System** is an IoT-based attendance management solution developed using the **ESP32** and **MFRC522 RFID Module**.

Whenever a registered RFID card is scanned, the ESP32 authenticates the card, records the current **Date**, **Time**, and **Attendance Status (Check-In / Check-Out)**, and uploads the data directly to **Google Sheets** using Wi-Fi.

The system eliminates manual attendance errors, provides real-time attendance records, and can be easily expanded for educational institutions, offices, and access control systems.

---

# 📸 Project Preview

## RFID Attendance Hardware

<p align="center">
<img src="./images/RFID syatem.png" width="850">
</p>

---

## Google Sheets Output

<p align="center">
<img src="./images/google-sheet-output.png" width="850">
</p>

---

# ✨ Features

- 📶 ESP32 Wi-Fi Connectivity
- 🪪 RFID Card Authentication
- 📅 Automatic Date Logging
- ⏰ Real-Time Time Logging
- 📊 Google Sheets Integration
- ✅ Check-In / Check-Out System
- ⚡ Fast Attendance Processing
- 🔒 Secure RFID UID Verification
- 🌐 Cloud-Based Attendance Storage

---

# 🛠 Hardware Components

| Component | Description |
|-----------|-------------|
| ESP32 Development Board | Main Controller |
| MFRC522 RFID Module | RFID Reader |
| RFID Cards / Tags | User Authentication |
| Breadboard | Circuit Assembly |
| Jumper Wires | Connections |
| USB Cable | Power Supply |
| Wi-Fi Network | Internet Connectivity |

---

# 🔌 Circuit Connections

| MFRC522 Pin | ESP32 Pin |
|-------------|-----------|
| SDA (SS) | GPIO 5 |
| SCK | GPIO 18 |
| MOSI | GPIO 23 |
| MISO | GPIO 19 |
| RST | GPIO 22 |
| 3.3V | 3.3V |
| GND | GND |

---

# 🔄 Working Principle

```text
RFID Card / Tag
        │
        ▼
MFRC522 RFID Reader
        │
        ▼
ESP32 Controller
        │
        ▼
User Authentication
        │
        ▼
Fetch Current Date & Time
        │
        ▼
Generate Attendance Record
        │
        ▼
Upload Data to Google Sheets
```

---

# 📂 Repository Structure

```text
RFID-Attendance-System/
│
├── README.md
├── code/
│   └── Attendance_System.ino
│
├── hardware/
│   ├── Circuit_Diagram.png
│   └── Block_Diagram.png
│
├── docs/
│   └── Project_Report.md
│
└── images/
    ├── RFID attendence system.png
    ├── RFID syatem.png
    └── google-sheet-output.png
```

---

# 🚀 Getting Started

## Software Required

- Arduino IDE
- ESP32 Board Package
- MFRC522 Library
- SPI Library
- WiFi Library
- Google Apps Script

---

## Installation

1. Install Arduino IDE.
2. Install the ESP32 Board Package.
3. Install the required libraries.
4. Connect the ESP32 with the MFRC522 RFID module.
5. Configure your Wi-Fi credentials.
6. Upload the program to ESP32.
7. Scan an RFID card.
8. View attendance data in Google Sheets.

---

# 🌍 Applications

- 🎓 College Attendance
- 🏫 School Attendance
- 🏢 Office Attendance
- 📚 Library Access
- 🏠 Hostel Entry Monitoring
- 🏭 Employee Attendance Tracking

---

# 🚀 Future Scope

- 📱 Mobile Application
- ☁ Firebase Integration
- 👤 Face Recognition
- ✋ Fingerprint Authentication
- 📊 Web Dashboard
- 📧 Email Notifications
- 📈 Attendance Analytics

---

# 👨‍💻 Author

### Mukul Vaid

**IoT Developer | Embedded Systems | ESP32 Projects**

---

# 📜 License

This project is developed for educational and academic purposes.

---

<div align="center">

## ⭐ If you found this project useful, don't forget to Star the Repository!

Made with ❤️ using ESP32 & RFID

</div>
