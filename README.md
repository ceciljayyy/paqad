# 📍 Paqad – GPS-Based Attendance Tracking System

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![Platform](https://img.shields.io/badge/Platform-PWA-blue)
![Frontend](https://img.shields.io/badge/Frontend-Next.js%20%7C%20TypeScript-purple)
![Backend](https://img.shields.io/badge/Backend-Express.js%20%7C%20PostgreSQL-green)
![Tracking](https://img.shields.io/badge/Tracking-GPS%20%7C%20Geofencing-red)

**Paqad** is a modern, GPS-powered attendance tracking system designed for accuracy, flexibility, and cross-industry use.  
It leverages **geofencing** to ensure check-ins occur only at approved locations and times, while offering manual and biometric backup options.  
Built for accessibility, **Paqad** is deployed as a **Progressive Web App (PWA)** for seamless use across devices.

---

## ✨ Features

- 📍 **GPS & Geofencing** – Restrict check-ins to predefined locations and configurable radii.  
- ⏱ **Real-Time Attendance** – Instant status updates for managers and staff.  
- 📊 **Role-Based Dashboards** – Custom interfaces for admins, managers, and employees.  
- 🖐 **Biometric & Manual Check-ins** – Backup methods for when GPS isn’t available.  
- 📅 **Meeting & Event Scheduling** – Set fixed locations via address, map selection, or current position.  
- 🔔 **Notifications** – Alerts for missed check-ins and late arrivals.  
- 📜 **Attendance History** – Employees can review past check-ins.  

---

## 🛠 Tech Stack

| Layer        | Technology |
|--------------|------------|
| **Frontend** | Next.js, TypeScript, Material-UI |
| **Backend**  | Express.js, Node.js |
| **Database** | PostgreSQL + PostGIS |
| **Auth**     | Email + Password (Custom) & Google Sign-In |
| **Deployment** | Progressive Web App (PWA) |
| **Security** | Helmet.js |
| **Logging**  | Morgan |

---

## 📦 Installation

```bash
# Clone repository
git clone https://github.com/your-username/paqad.git
cd paqad

# Install dependencies
npm install

# Start development server
npm run dev

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.

