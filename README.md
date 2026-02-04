# 🏨 hotel-booking-platform

A full-stack Individual Hotel Booking System built using the MERN stack. This project provides an online room booking platform with role-based access for Users, Managers, and Admins. It automates hotel operations such as room management, bookings, and reporting while delivering a smooth user experience.

---

## 🚀 Features

### 👤 User
- Register & Login (JWT Authentication)
- View available rooms
- Book rooms
- View booking history
- Cancel bookings
- Update profile

### 🧑‍💼 Manager
- Login dashboard
- Add / Edit / Delete rooms
- Upload room images
- Approve or reject bookings
- Manage availability
- Check-in & Check-out guests

### 🛡 Admin
- Dashboard analytics
- Manage managers
- View all users
- View all bookings
- Generate revenue reports
- Block or delete accounts

---

## 🛠 Tech Stack

### Frontend
- React.js  
- HTML5  
- CSS3  
- Tailwind CSS  
- JavaScript  

### Backend
- Node.js  

### Database
- MongoDB  

### Tools
- GitHub  
- VS Code  
- Postman  

---

## 🔐 Security

- Password hashing
- JWT Authentication
- Role-based routing
- Protected APIs

---

## 📊 Advanced Features

- Cloud image upload
- Payment gateway integration
- PDF invoice generation
- Admin analytics charts
- Booking calendar
- WhatsApp notifications

---

## 🏗 Architecture

React Frontend → Node.js API → MongoDB Database  
JWT handles authentication  
Role middleware controls access

---

## 📁 Database Design

### User Collection
- name
- email
- password
- role

### Room Collection
- title
- price
- description
- images
- status

### Booking Collection
- userId
- roomId
- checkIn
- checkout
- Aadhaar card document
- status
- createdAt

---

## ⚙️ Installation

### 1. Clone Repository
```bash
git clone https://github.com/yourusername/mern-hotel-booking-system.git
```

### 2. Install Backend Dependencies
```bash
cd backend
npm install
```

### 3. Install Frontend Dependencies
```bash
cd frontend
npm install
```

---

## ▶ Run Project

### Backend
```bash
npm run dev
```

### Frontend
```bash
npm start
```
