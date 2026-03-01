# CrowdShield – Smart Metro Congestion & Safety Control System

CrowdShield is an AI-powered metro station management system designed to reduce peak-hour congestion, eliminate human errors, and automate entry flow using Edge AI, sensors, and computer vision.

##  Key Features
- Real-time passenger counting using IR sensors + AI camera
- RFID-based smart verification system
- Automatic gate control during heavy crowd
- AI-powered crowd prediction model
- AMD-powered Edge processing for real-time decisions
- Live dashboard for metro operators
- Error elimination through automated validation

---

##  Tech Stack
###  Hardware
- RFID Reader RC522
- IR Sensors
- Servo Motor for Gate
- Camera Module
- AMD Ryzen Embedded / Edge Device

###  Software
- Python (Edge Processing)
- PyTorch / ROCm for Model Training
- Node.js / Python Flask Backend
- HTML/CSS/JS Dashboard (or React)
- Firebase / PostgreSQL Database

---

##  System Architecture
![Architecture]<img width="1536" height="1024" alt="architecture" src="https://github.com/user-attachments/assets/08977b1c-d302-48e6-ba74-5e71660cadb6" />


---

## Prototype Demo
Video available in `https://app.animaker.com/animo/BXyqCOcS6TAPgiSu/`

---

## Folder Overview
- `hardware/` → sensor connections & circuit diagrams  
- `firmware/` → Arduino/Raspberry Pi firmware  
- `edge-processing/` → AI inference, AMD ROCm optimization  
- `dashboard/` → operator UI + backend  
- `architecture/` → diagrams, flowcharts  
- `images/` → AI-generated illustrations for documentation  
- `demo/` → final video, screenshots, PPT  

---

## How It Works
1. Passenger taps RFID card  
2. Sensor fusion validates entry  
3. Edge AI processes crowd data instantly  
4. Gates automatically open/close  
5. Dashboard updates in real-time  
6. AI predicts crowd surges  

---

## 🛠 Setup Instructions
### 1. Install Dependencies

### 2. Run Edge Inference

### 4. Launch Frontend Dashboard  
Open `dashboard/frontend/index.html`  

---

## 🤝 Contributing  
Pull requests welcome!

---

## 📄 License  
MIT License  
