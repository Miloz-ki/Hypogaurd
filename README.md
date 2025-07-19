# HypoGaurd
# 🚑 HypoGuard — Intelligent Health Emergency Alert System

HypoGuard is an innovative web-based emergency alert system designed to monitor vital health signs and provide rapid response support for individuals—particularly elderly or diabetic patients who are at risk of sudden health deterioration. It automates emergency detection, alerts caregivers, and maintains real-time emergency logs, all while being user-friendly and accessible.

---

## 🔍 Project Overview

**HypoGuard** acts as a digital safeguard for individuals vulnerable to critical health events such as hypoglycemia, low blood pressure, or cardiac anomalies. It can operate in **manual** or **simulated sensor input** mode to check vitals like heart rate, blood pressure, and blood sugar. If abnormal readings are detected, the system:

- Sounds an emergency siren and voice alert
- Shares the user’s live location
- Notifies caregivers instantly via **EmailJS**
- Logs the emergency with timestamp in **Firebase Firestore**

This system is ideal for home-alone patients, elderly individuals, or those requiring constant remote monitoring.

---

## 🧠 Mental Health Significance

While HypoGuard is primarily a physical health alert system, its impact on **mental well-being** is significant:

- 💬 **Peace of mind** for users living alone — knowing they are constantly monitored reduces anxiety.
- 👨‍👩‍👧 **Caregiver confidence** — remote family or healthcare providers receive instant updates.
- 🧘 **Stress reduction** — users don’t need to panic during emergencies; the system takes over.
- 🤖 **Future potential** — features like mood tracking, loneliness detection, or AI voice assistance can further support mental health and combat isolation.

---

## ⚙️ Key Features

| Feature                        | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| ✅ Vitals Monitoring           | Heart rate, blood pressure, and sugar levels checked manually/simulated    |
| 🔁 Recheck Confirmation       | 10-second delay before emergency alert to avoid false positives             |
| 📣 Voice & Siren Alert        | Plays an emergency siren and spoken message for the user                    |
| 🗺️ Geolocation Sharing       | Sends user's current location to caregivers                                |
| 📩 Caregiver Notification     | Real-time alert via **EmailJS**                                            |
| 🔐 Firebase Auth              | Login/signup system to track logs per user                                 |
| 📜 Emergency Log History      | View all previous emergency alerts with timestamps and reasons             |
| 🕒 Timestamp Sorting          | Recent emergencies appear first in log                                     |
| 🛠️ Manual/Simulated Mode     | Supports both real sensor data and manual input                            |
| 🔄 Auto-refresh Ready         | Capable of extending for continuous monitoring                             |

---

## 🧱 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Firebase Firestore (NoSQL DB) + Firebase Authentication
- **Third-Party Integration**: EmailJS (email notifications)
- **Geolocation**: HTML5 Geolocation API
- **Audio**: Custom siren and speech synthesis for alerts

---
