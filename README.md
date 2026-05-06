# 🦷 SmileCare Dental Appointment System (Premium)

<p align="center">
  <b>🚀 SaaS-Ready Doctor Appointment Booking System</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-HTML%2FCSS%2FJS-blue">
  <img src="https://img.shields.io/badge/Backend-Google%20Apps%20Script-green">
  <img src="https://img.shields.io/badge/Database-Google%20Sheets-orange">
  <img src="https://img.shields.io/badge/Calendar-Google%20Calendar-red">
  <img src="https://img.shields.io/badge/Status-Production%20Ready-success">
</p>

---

# 🚀 Overview

A **complete doctor-based appointment booking system** with:

✔ Real-time slot availability  
✔ Google Calendar blocking  
✔ WhatsApp confirmation  
✔ Zero backend infrastructure cost  

---

# 🧠 Architecture

```
Frontend (index.html)
        ↓
Google Apps Script (API)
        ↓
Google Calendar (Doctor Availability)
        ↓
Google Sheets (Data Storage)
        ↓
WhatsApp (User Notification)
```

---

# 🎯 Key Features

## 👨‍⚕️ Doctor-Based Booking
- Each service mapped to doctor
- Doctor availability controls booking

## 📅 Smart Slot Engine
- Real-time calendar validation
- Prevents duplicate booking
- Auto-blocks booked slots

## ⛔ Smart Restrictions
- No past booking
- Max 10-day booking window
- Sunday holiday logic

## 📊 Data Storage
- Google Sheets acts as database
- Stores full appointment history

## 📩 Notifications
- Doctor email notification
- WhatsApp confirmation for patient

---

# 📸 Screenshots (Add Your Images)

### 🏠 Homepage
![Homepage](https://via.placeholder.com/800x400)

### 📅 Appointment Booking
![Booking](https://via.placeholder.com/800x400)

### 📱 Mobile View
![Mobile](https://via.placeholder.com/400x700)

---

# ⚙️ Setup Guide

## 1. Google Sheet

Create:
```
Appointments
```

Columns:
```
Appointment ID | Timestamp | Name | Phone | Category | Doctor | Date | Time | Status | Event ID
```

---

## 2. Apps Script

Update:

```javascript
const SHEET_ID = "YOUR_SHEET_ID"
```

Deploy:

```
Execute as: Me
Access: Anyone
```

---

## 3. Connect Frontend

```javascript
const SCRIPT_URL = "YOUR_WEB_APP_URL"
```

---

## 4. Google Calendar

Share doctor calendars with:

```
Apps Script owner email
Permission: Make changes
```

---

# 🔄 Flow

```
User selects date
 → System loads doctors
 → User selects category
 → Slots fetched from calendar
 → Booking confirmed
 → Calendar updated
 → WhatsApp triggered
```

---

# 🧩 SaaS Expansion Ready

This project can be extended to:

- Multi-clinic platform
- Doctor dashboards
- Online payments
- Admin analytics
- Subscription model

---

# ⚠️ Limitations

- WhatsApp manual send
- No login/authentication
- Google account dependency

---

# ⭐ Support

If you like this project:

- ⭐ Star this repo
- 🚀 Use it for your startup
- 🔥 Build SaaS on top

---

# 💡 One Line

```
A complete real-time doctor appointment system powered by Google ecosystem.
```
