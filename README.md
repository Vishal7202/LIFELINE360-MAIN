# LifeLine360 💉🩺

**LifeLine360** is a full-stack healthcare platform that brings together **patients**, **doctors**, **pharmacists**, **delivery partners**, and **admins** in a unified digital ecosystem. It allows users to book appointments, manage prescriptions, order medicines, and track deliveries — all in one seamless web app.

---

## 🌐 Live Demo

> *(Add your deployed link here — e.g., Netlify/Vercel/Render)*  
> 👉 [Visit LifeLine360](https://your-deployed-link.com)

---

## 🎯 Key Features

### 👨‍⚕️ Patient
- Book, reschedule or cancel appointments
- View medical history & prescriptions
- Order medicines with Razorpay payment
- Track delivery of medicine orders

### 👩‍⚕️ Doctor
- View and filter appointments by status/date
- Write prescriptions
- Track patient history

### 🛒 Pharmacist
- Manage medicine orders
- Update stock
- Handle billing and dispatch

### 🚚 Delivery Partner
- See assigned deliveries
- Mark order as delivered
- Track routes *(future enhancement)*

### 👨‍💼 Admin
- Dashboard for monitoring users and data
- Manage system-level activities
- Access full order & user reports

---

## 🛠️ Tech Stack

| Layer        | Tech                      |
| ------------ | ------------------------- |
| Frontend     | React.js, Tailwind CSS    |
| Backend      | Node.js, Express.js       |
| Database     | MongoDB (Mongoose)        |
| Payments     | Razorpay Integration      |
| Auth (Planned) | JWT / OAuth              |
| Deployment   | *(Add if deployed e.g., Vercel / Render)*

---

## 📂 Folder Structure

LifeLine360/
├── client/ # Frontend - React.js
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ └── App.js
├── server/ # Backend - Node.js + Express
│ ├── routes/
│ ├── models/
│ ├── controllers/
│ └── server.js
├── README.md
└── package.json
