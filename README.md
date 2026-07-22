# Temple Queue Management System using AI-Based Crowd Monitoring

An AI-powered web application that monitors temple queues in real time using Computer Vision. The system detects and tracks devotees from CCTV footage or uploaded videos, estimates waiting time, and provides administrators with live analytics through an interactive dashboard.

---

## 📌 Overview

Managing large crowds during festivals and peak hours is challenging for temples. This project automates queue monitoring by using AI-based person detection and tracking to estimate queue length, waiting time, and crowd status.

The system helps temple administrators make informed decisions and improve the overall darshan experience for devotees.

---

## ✨ Features

- 👥 Real-time person detection
- 🎥 Live CCTV and uploaded video support
- 📍 Multi-person tracking
- ⏱️ Queue waiting time estimation
- 📊 Live analytics dashboard
- 🚦 Queue status classification (Normal, Moderate, Heavy)
- 📈 Historical analytics
- 🔔 Admin announcement panel
- 📱 Responsive web interface

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap
- Chart.js

### Backend
- Python
- Flask

### AI & Computer Vision
- YOLOv8
- OpenCV
- DeepSORT

### Database
- SQLite / MongoDB (depending on configuration)

---

## 📂 Project Structure

```
mini-project/
│
├── app.py
├── requirements.txt
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── index.html
│   ├── dashboard.html
│   └── ...
│
├── models/
├── uploads/
├── output/
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/madhura-padaki/mini-project.git
```

### Navigate into the project

```bash
cd mini-project
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate the environment

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:5000
```

---

## 🚀 How It Works

1. Upload a video or connect a CCTV feed.
2. YOLOv8 detects people in each frame.
3. DeepSORT assigns unique IDs and tracks movement.
4. The system calculates:
   - Current queue count
   - Estimated waiting time
   - Crowd density
5. Dashboard displays analytics in real time.

---

## 📊 Dashboard Includes

- Total People in Queue
- Estimated Waiting Time
- Queue Status
- Detection Accuracy
- Live Video Feed
- Queue History
- Crowd Analytics
- Admin Controls

---

## 🎯 Future Enhancements

- Mobile application
- SMS notification system
- Temple slot booking
- Face recognition for VIP entry
- Cloud deployment
- Multi-camera support
- AI crowd prediction
- Voice announcements

---

## 📷 Screenshots

Add screenshots here.

Example:

```
screenshots/dashboard.png
screenshots/live_detection.png
screenshots/analytics.png
```

---

## 📈 Applications

- Temples
- Religious Events
- Pilgrimage Centers
- Public Crowd Management
- Smart City Projects

---

## 👩‍💻 Author

**Madhura Padaki**

GitHub: https://github.com/madhura-padaki

---

## 📄 License

This project is developed for educational and research purposes.

Feel free to use and modify it for learning.
