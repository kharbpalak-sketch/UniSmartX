# 🎓 UniSmartX – Smart University Management System

A modern and scalable **frontend-based university management system** designed for **Bhagat Phool Singh Mahila Vishwavidyalaya (BPSMV)**.
It integrates **department management** and **hostel management** into a single smart platform.

---

## 📖 Description

UniSmartX is a smart UI-based system that simplifies university operations by providing structured workflows for students, faculty, hostel staff, and administrators.

The project demonstrates how a real-world university system can digitally manage:

* Academic operations
* Hostel processes
* Student services
* Administrative controls

---

## 🌐 Live Demo

👉 https://year-flow-hub.lovable.app/

## ✨ Screenshots

<img width="1917" height="866" alt="Screenshot 2026-04-09 145757" src="https://github.com/user-attachments/assets/d81801f6-42eb-4090-9658-6c90b1272014" />
<img width="1914" height="871" alt="Screenshot 2026-04-09 145852" src="https://github.com/user-attachments/assets/9176d5dc-09b2-48cf-96eb-008eac782eef" />
<img width="1911" height="852" alt="Screenshot 2026-04-09 150059" src="https://github.com/user-attachments/assets/b64a1b27-2bd5-4078-a7dd-462d597d3153" />
<img width="1600" height="722" alt="image" src="https://github.com/user-attachments/assets/52e2870e-8daf-4a33-b4a7-88c0738da0d1" />

---

## ✨ Key Features

### 🏫 Department Management

* Multiple departments (BCA, B.Tech, etc.)
* 📅 Timetable management/ Rescheduling Classes
* 📊 Attendance tracking
* 👩‍🏫 Faculty information
* 📝 Complaint system

---

### 🏠 Hostel Management

* 🛏️ Room & student records interface
* 📊 Hostel attendance
* 🍽️ Mess menu display
* 📝 Complaint system
* 🚪 Online leave application system

---

### 🔐 Smart Leave Approval System

* Face recognition (guardian verification concept)
* Parent approval (online consent)
* Warden approval (final decision)
* Real-time leave status tracking

---

### 📊 Student Dashboard

* 📅 Today’s classes
* 🗓️ Calendar view
* 📊 Attendance percentage
* 🔔 Notifications
* 📄 Leave status (approved / pending)

---

### 🛠️ Admin Control Panel

* 📢 Send announcements
* ➕ Add / Update / Delete data
* 🔄 Semester / yearly data reset
* 🍽️ Update hostel mess menu

---

## 🔄 System Flow
```
                        ┌───────────────────────┐
                        │      UniSmartX        │
                        │  (BPSMV University)   │
                        └─────────┬─────────────┘
                                  │
               ┌──────────────────┴──────────────────┐
               │                                     │
     ┌───────────────┐                   ┌────────────────┐
     │  Departments  │                   │    Hostels     │
     └──────┬────────┘                   └──────┬─────────┘
            │                                   │
   ┌────────┴────────┐                ┌─────────┴─────────┐
   │  Multiple Depts │                │  Multiple Hostel  │
   │ (BCA, BTech...) │                │  (H-1, 2,3,....)  │
   └────────┬────────┘                └─────────┬─────────┘
            │                                   │
   ┌────────┴─────────────┐          ┌──────────┴─────────────┐
   │ Department Operations │          │   Hostel Operations    │
   └────────┬─────────────┘          └──────────┬─────────────┘
            │                                   │
   ┌────────┼───────────────┐        ┌──────────┼──────────────┐
   │ • Attendance           │        │ • Attendance            │
   │ • Timetable            │        │ • Mess Menu             │
   │ • Faculty Info         │        │ • Complaints            │
   │ • Complaints           │        │ • Leave Application     │
   └────────────────────────┘        └──────────┬──────────────┘
                                               │
                                      ┌────────┴──────────┐
                                      │  Leave System     │
                                      └────────┬──────────┘
                                               │
                     ┌─────────────────────────┼─────────────────────────┐
                     │                         │                         │
         ┌──────────────────┐     ┌────────────────────┐     ┌────────────────────┐
         │ Face Recognition │     │   Parent Approval  │     │   Warden Approval  │
         │ (Guardian Verify)│     │  (Online Consent)  │     │   Final Approval   │
         └────────┬─────────┘     └────────┬───────────┘     └────────┬───────────┘
                  │                        │                          │
                  └───────────────┬────────┴──────────────┬───────────┘
                                  │
                         ┌────────▼────────┐
                         │ Leave Approved  │
                         └─────────────────┘


               ┌────────────────────────────────────────────┐
               │             Student Dashboard              │
               └────────────────────────────────────────────┘
               │ • Today's Classes                          │
               │ • Attendance %                             │
               │ • Notifications                            │
               │ • Leave Status                             │
               └────────────────────────────────────────────┘


               ┌────────────────────────────────────────────┐
               │           Admin Control Panel              │
               └────────────────────────────────────────────┘
               │ • Announcements                           │
               │ • Data Add / Update / Delete              │
               │ • Semester / Year Data Reset              │
               │ • Menu Updates                            │
               └────────────────────────────────────────────┘


               ┌────────────────────────────────────────────┐
               │        Multi-Language Support              │
               └────────────────────────────────────────────┘
               │ • English                                 │
               │ • Hindi                                   │
               └────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

* HTML
* React.js
* CSS
* JavaScript
* Backend (server / logic) → Node.js

---

## 📂 Project Structure

```
project/
│── index.html
│── style.css
│── script.js
│── assets/
│── README.md
```

## 📊 Use Cases

* University digital management systems
* Hostel automation systems
* Student service platforms
* UI/UX prototype for real-world applications

---

## 🚀 Future Enhancements

* 🔗 Backend integration (Node.js / Django)
* 🗄️ Database (MySQL / MongoDB)
* 🔐 Authentication system
* 📊 Real-time analytics dashboard
* 🤖 AI-based insights

---

## 📜 Note

This project is open-source and available for educational purposes.


