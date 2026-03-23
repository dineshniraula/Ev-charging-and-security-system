#  Smart EV Charging Booking System with Intrusion Detection

##  Project Overview

This project develops a **web-based Electric Vehicle (EV) charging station booking system** integrated with a **machine learning-based Intrusion Detection System (IDS)** to enhance cybersecurity.

The system allows users to locate charging stations, book time slots, and securely manage their reservations while detecting suspicious or malicious activities in real time.

---

##  Objectives

* Develop a user-friendly EV charging booking platform
* Implement secure authentication and booking mechanisms
* Detect anomalous or malicious user behavior using machine learning
* Improve system reliability and cybersecurity awareness

---

##  Key Features

### 🔹 User Features

* User registration and login
* View available EV charging stations
* Book charging slots
* View booking history

### 🔹 Admin Features

* Add/manage charging stations
* Monitor bookings
* View flagged suspicious activities

### 🔹 Cybersecurity Features

* Intrusion detection using ML models
* Detection of abnormal user behavior
* Alerts for suspicious login or booking patterns

---

##  System Architecture

Frontend (HTML, CSS, JavaScript)
⬇
Backend (Node.js / Express)
⬇
Database (MySQL)
⬇
ML Module (Python - Scikit-learn)

---

## 🛠️ Technologies Used

| Layer            | Technology                           |
| ---------------- | ------------------------------------ |
| Frontend         | HTML, CSS, JavaScript                |
| Backend          | Node.js (Express)                    |
| Database         | MySQL                                |
| Machine Learning | Python (Scikit-learn, Pandas, NumPy) |
| Version Control  | Git & GitHub                         |

---

##  Project Structure

```
ev-charging-security-system/
│
├── frontend/        # UI components
├── backend/         # Server & APIs
├── database/        # SQL schema & scripts
├── ml-model/        # ML model & datasets
├── docs/            # Documentation & reports
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️ Clone Repository

```
git clone https://github.com/dineshniraula/ev-charging-security-system.git
cd ev-charging-security-system
```

### 2️ Backend Setup

```
cd backend
npm install
node server.js
```

### 3️ Database Setup

* Install XAMPP / MySQL
* Import `database/schema.sql`

### 4️ ML Model Setup

```
cd ml-model
pip install -r requirements.txt
jupyter notebook
```

---

##  Intrusion Detection Approach

The system uses **machine learning algorithms** (e.g., Isolation Forest) to:

* Monitor user activities
* Detect anomalies in booking patterns
* Identify suspicious login attempts

---

##  Success Criteria

* Functional booking system with end-to-end flow
* Secure authentication and data handling
* Intrusion detection accuracy ≥ 80%
* Clean and responsive UI
* Proper documentation and version control

---

##  Team Roles

| Member   | Responsibility              |
| -------- | --------------------------- |
| Dinesh  | Frontend Development        |
| Riya  | Backend Development         |
| Adarsha | Database Design             |
| siffat | Machine Learning & Security |

---

##  Project Timeline

* Week 1: Planning & Setup
* Week 2: Basic Development
* Week 3: Core Features
* Week 4: Integration
* Week 5: Security Implementation
* Week 6: Testing & Finalization

---

##  Future Enhancements

* Real-time charging slot availability
* Online payment integration
* Mobile application support
* Advanced AI-based threat detection
* GPS-based nearest station recommendations

---

##  License

This project is for academic purposes only.

---

##  Acknowledgements

* Open-source community
* Academic resources and datasets
* Machine learning libraries and documentation

---
