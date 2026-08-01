<div align="center">

# 📡 RFID Attendance System

### Smart Attendance Management using ESP32, RFID & Google Sheets

<img src="./images/RFID attendence system.png" alt="RFID attendance system" width="100%">

<br>

![ESP32](https://img.shields.io/badge/ESP32-IoT-red?style=for-the-badge&logo=espressif)
![RFID](https://img.shields.io/badge/MFRC522-RFID-success?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Arduino-IDE-blue?style=for-the-badge&logo=arduino)
![Google Sheets](https://img.shields.io/badge/Google-Sheets-34A853?style=for-the-badge&logo=googlesheets)

</div>

---

# 🚀 About the Project

The **RFID Attendance System** is an IoT-based smart attendance solution developed using the **ESP32** and **MFRC522 RFID Module**.

Whenever a registered RFID card or RFID tag is scanned, the ESP32 authenticates the UID, records the **Date**, **Time**, and **Attendance Status (Check-In / Check-Out)**, and uploads the data directly to **Google Sheets** over Wi-Fi.

This system reduces manual work, improves attendance accuracy, and provides real-time cloud-based attendance records.

---

# 📸 Project Gallery

## RFID Attendance System

<p align="center">
<img src="./images/RFID system.png" width="850">
</p>

---

## Google Sheets Attendance Log

<p align="center">
<img src="./images/google-sheet-output.png" width="850">
</p>

---

# ✨ Features

- 📶 ESP32 Wi-Fi Connectivity
- 🪪 RFID Card & Tag Authentication
- ⏰ Real-Time Date & Time Logging
- 📊 Google Sheets Integration
- ✅ Automatic Check-In / Check-Out
- ⚡ Fast Attendance Processing
- 🔒 Secure RFID UID Verification
- 🌐 Cloud-Based Attendance Storage

---

# 🛠 Hardware Components

| Component | Description |
|-----------|-------------|
| ESP32 Development Board | Main Controller |
| MFRC522 RFID Reader | RFID Card Reader |
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

# 🔄 System Workflow

```text
RFID Card / RFID Tag
          │
          ▼
MFRC522 RFID Reader
          │
          ▼
ESP32 Controller
          │
          ▼
UID Verification
          │
          ▼
Get Current Date & Time
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
├── docs/
│   └── Project_Report.md
│
├── hardware/
│   ├── Block_Diagram.png
│   └── Circuit_Diagram.png
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

## Installation Steps

1. Install Arduino IDE.
2. Install the ESP32 Board Package.
3. Connect the MFRC522 module to the ESP32.
4. Install the required Arduino libraries.
5. Configure your Wi-Fi credentials.
6. Upload the code to the ESP32.
7. Scan an RFID card or tag.
8. Attendance data will automatically appear in Google Sheets.

---

# 📊 Applications

- 🎓 College Attendance System
- 🏫 School Attendance System
- 🏢 Office Employee Attendance
- 📚 Library Access Control
- 🏠 Hostel Entry Monitoring
- 🏭 Industrial Workforce Management

---

# 🔮 Future Scope

- 📱 Android Application
- ☁ Firebase Integration
- 👤 Face Recognition
- ✋ Fingerprint Authentication
- 📊 Web Dashboard
- 📧 Email Notifications
- 📈 Attendance Analytics

---

# 👨‍💻 Author

### Mukul Vaid

**IoT Developer | ESP32 Projects | Embedded Systems Enthusiast**

---

# 📜 License

This project is developed for educational and academic purposes.

---

<div align="center">

## ⭐ If you found this project useful, please give it a Star!

**Made with ❤️ using ESP32 & RFID**

</div>
