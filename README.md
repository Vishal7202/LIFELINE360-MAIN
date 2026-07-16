# 💉 LifeLine360 – Smart Healthcare Management System

A modern, full-stack healthcare management platform built with the **MERN Stack**. LifeLine360 connects **Patients, Doctors, Pharmacists, Delivery Partners, and Administrators** on a single secure platform to simplify healthcare services such as appointment booking, prescription management, medicine ordering, and healthcare administration.

---

## 📖 Project Overview

LifeLine360 is designed to digitize healthcare services by providing an easy-to-use, secure, and scalable platform for healthcare providers and patients. The system follows a modular architecture with role-based access control, making it secure, maintainable, and easy to extend.

The platform enables users to book doctor appointments, consult doctors online, order medicines, book laboratory tests, access digital patient records, and manage healthcare services from anywhere.

LifeLine360 connects Patients, Doctors, Pharmacies, Laboratories, Delivery Partners, and Administrators on a single platform to provide a seamless healthcare experience.
---

# ✨ Features

## 👤 Patient Module

* Register and Login
* Book appointments with doctors
* Reschedule or cancel appointments
* View appointment history
* View prescriptions
* Access medical history
* Order medicines online
* Track medicine order status
* Update profile information

---

## 👨‍⚕️ Doctor Module

* Secure doctor login
* View daily appointments
* Accept or reject appointments
* Write digital prescriptions
* View complete patient history
* Manage consultation schedule

---

## 💊 Pharmacist Module

* View medicine orders
* Manage medicine inventory
* Update stock availability
* Process customer orders
* Generate billing information

---

## 🚚 Delivery Partner Module

* View assigned medicine deliveries
* Update delivery status
* Manage completed deliveries

> Planned Features

* Live location tracking
* Delivery notifications

---

## 👨‍💼 Admin Module

* Dashboard with analytics
* Manage users
* Manage doctors
* Manage pharmacists
* Monitor appointments
* View reports
* Manage medicine orders
* System monitoring

---

# 🔐 Authentication & Security

* JWT Authentication *(Planned / Implemented as applicable)*
* Role-Based Access Control (RBAC)
* Protected Routes
* Password Encryption
* Input Validation
* Secure REST APIs

---

# 🛠 Tech Stack

| Category         | Technology                                  |
| ---------------- | ------------------------------------------- |
| Frontend         | React.js                                    |
| Styling          | Tailwind CSS                                |
| Backend          | Node.js                                     |
| Framework        | Express.js                                  |
| Database         | MongoDB (Mongoose)                          |
| Authentication   | JWT *(Planned / Implemented)*               |
| API              | REST API                                    |
| State Management | React Hooks                                 |
| Version Control  | Git & GitHub                                |
| Deployment       | Vercel / Render *(Update after deployment)* |

---

# 📂 Project Structure

```text
LifeLine360/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── layouts/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── README.md
└── package.json
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/LifeLine360.git
```

```bash
cd LifeLine360
```

---

## Install Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## Install Backend

```bash
cd backend
npm install
npm start
```

---

# 🔑 Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLIENT_URL=http://localhost:5173
```

---

# 🌐 API Overview

### Authentication

* Register User
* Login User
* Logout

### Patient

* Book Appointment
* Cancel Appointment
* View Prescription
* View Medical History

### Doctor

* View Appointments
* Update Appointment
* Create Prescription

### Pharmacy

* Manage Orders
* Update Medicine Stock

### Admin

* Manage Users
* Manage Doctors
* View Reports

---
📸 Project Brochure
Front Brochure
<p align="center"> <img src="screenshots/brochure-front.png" alt="LifeLine360 Front Brochure" width="900"/> </p>
Back Brochure
<p align="center"> <img src="screenshots/brochure-back.png" alt="LifeLine360 Back Brochure" width="900"/> </p>

Note: Save your brochure images inside the screenshots/ folder as:

screenshots/brochure-front.png
screenshots/brochure-back.png
📸 Screenshots

# 📸 Screenshots

Add screenshots after deployment.

```
Home Page

Login Page

Patient Dashboard

Doctor Dashboard

Admin Dashboard

Medicine Store

Appointment Page
```

---

# 🚀 Future Enhancements

* Razorpay Payment Integration
* Video Consultation
* AI Symptom Checker
* Email Notifications
* SMS Notifications
* Medicine Recommendation
* Real-Time Chat
* Delivery Tracking
* Medical Report Upload
* Appointment Reminder
* Dark Mode
* PWA Support

---

# 📈 Project Highlights

* Full Stack MERN Application
* Modular Architecture
* RESTful APIs
* MongoDB Database
* Responsive Design
* Secure Authentication
* Role-Based Dashboards
* CRUD Operations
* Scalable Folder Structure
* Clean UI

---

# 🎯 Learning Outcomes

Through this project I gained hands-on experience in:

* React.js
* Node.js
* Express.js
* MongoDB
* REST API Development
* Component-Based Architecture
* CRUD Operations
* Authentication
* Git & GitHub
* Responsive UI Design

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch.
5. Create a Pull Request.

---

# 🐞 Known Limitations

* Online payment integration is pending.
* Real-time notifications are not implemented.
* Delivery tracking is under development.
* Video consultation feature is planned.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

## Vishal Kumar

**MERN Stack Developer**

### Skills

* React.js
* Node.js
* Express.js
* MongoDB
* JavaScript
* HTML5
* CSS3
* Tailwind CSS
* REST APIs
* Git & GitHub

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates further improvements.
