# EduTrack Pro – IoT Based Smart Attendance System

EduTrack Pro is a **ready-to-go IoT attendance solution** designed for schools, colleges, and organizations.  
It seamlessly integrates **RFID hardware**, **ESP8266 Wi-Fi connectivity**, and a **real-time web dashboard** powered by Google Sheets backend.  

This isn’t just a prototype – it’s a **production-ready system** that can be deployed directly in real institutions. 🚀  

---

## ✨ Features

- ✅ **Plug-and-Play** – Works right after powering on  
- ✅ **Multiple Card Scanning** – Handles more than one RFID card at a time  
- ✅ **Real-time Web Dashboard** – Live attendance tracking anywhere in the world  
- ✅ **Auto Wi-Fi Configuration** – Configure via hotspot without coding  
- ✅ **Visual Feedback** – LCD + buzzer + LED indicators for user interaction  
- ✅ **Google Sheets Integration** – Cloud database for attendance records  
- ✅ **Responsive Web App** – Accessible on mobile, tablet, and desktop  
- ✅ **Secure & Scalable** – Works for a single class or an entire school  

---

## 🛠️ Hardware Used

- ESP8266 NodeMCU Wi-Fi Development Board  
- MFRC522 RFID Module  
- 16x2 LCD Display (I2C interface)  
- Buzzer & LEDs for feedback  
- Push Button (for Wi-Fi reset/config)  
- RFID Cards/Tags  
- Breadboard, jumper wires, and power supply  


---

## ⚙️ How It Works

1. **Power On** – Device auto-initializes and connects to saved Wi-Fi  
2. **Scan RFID** – Tap your RFID card, attendance is recorded in real-time  
3. **Dashboard** – Visit [bhupusainik.netlify.app](https://bhupusainik.netlify.app) and log in  
   - View present, absent, total students, reports & more  
4. **Change Wi-Fi** –  
   - Press boot button for 3 sec → `EduTrack Pro` hotspot appears  
   - Connect & enter new credentials → Device reconnects automatically  

---

## 📊 Dashboard Preview

- **Attendance Summary** (Present, Absent, Total Students)  
- **Reports & Analytics** (Export CSV, Date filters, Graphs)  
- **Student Management** (Profiles, quick search)  
- **Admin Panel** (Secure login, remote monitoring)  

---

## 🚀 Use Cases

- Schools & Colleges  
- Offices & Organizations  
- Hackathons / Tech Competitions  
- DIY Hobby & Learning Projects  

---

## 🔒 Security & Reliability

- HTTPS-based Apps Script communication  
- Duplicate scan prevention  
- Auto Wi-Fi reconnection  
- Cloud backup (Google Sheets)  

---

## 👨‍💻 Author

Created with ❤️ by **Sakshyam Bastakoti**  
📧 Contact: sakshyamxeetri@gmail.com  
📺 YouTube: [Tech World XYZ](https://www.youtube.com/@techworldxyz/)  

---

## 📜 License

This project is open-source under the **MIT License**.  
You are free to use, modify, and distribute with proper attribution.  

---

## 🌟 Final Note

EduTrack Pro isn’t just another attendance project –  
it’s a **full-stack IoT platform** bridging hardware, cloud, and web apps.  
Perfect for real-world deployment and educational innovation. 🎯  

---


## 📂 Project Structure
EduTrack-Pro/
│
├── ArduinoCode/                # ESP8266 firmware code
│   ├── EduTrackPro.ino          # Main Arduino sketch
│   ├── config.h                 # Wi-Fi & project configurations
│   ├── RFID.cpp / RFID.h        # RFID logic (if modularized)
│   └── utils.h                  # Helper functions
│
├── AppScript/                   # Google Apps Script backend
│   ├── Code.gs                  # Main Google Apps Script file
│   └── README.md                # Setup instructions for Apps Script
│
├── WebDashboard/                # Web front-end (Netlify hosting)
│   ├── index.html               # Main dashboard HTML
│   ├── style.css                # Custom styles
│   ├── script.js                # Dashboard logic
│   └── assets/                  # Images, icons, logos
│
├── CircuitDiagram/              # Electronics schematics
│   ├── circuit.png              # Full wiring diagram
│   └── fritzing.fzz             # Editable Fritzing file
│
├── Docs/                        # Documentation
│   ├── Project-Report.pdf        # Detailed documentation
│   ├── User-Manual.pdf           # End-user manual
│   └── Images/                  # Photos/screenshots
│
├── LICENSE                      # Open-source license (MIT recommended)
├── README.md                    # Main documentation
└── .gitignore                   # Ignore build/temp files


