# 🎓 BYOD Classroom Management System

<p align="center">

![Node.js](https://img.shields.io/badge/Node.js-20.x-green?style=for-the-badge&logo=node.js)
![Express](https://img.shields.io/badge/Express.js-Backend-black?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?style=for-the-badge&logo=mongodb)
![Socket.IO](https://img.shields.io/badge/Socket.IO-Real_Time-black?style=for-the-badge&logo=socket.io)
![JWT](https://img.shields.io/badge/JWT-Authentication-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</p>

---

## 📖 About

**BYOD Classroom Management System** is a full-stack web application designed for **Bring Your Own Device (BYOD)** classrooms. It helps teachers monitor student productivity, communicate instantly, manage website access, and create a distraction-free learning environment using real-time technologies.

---

# ✨ Features

## 👨‍🏫 Teacher Dashboard

- Secure Login
- Real-Time Announcements
- Website Blocklist Management
- Monitor Student Activities
- Productivity Analytics
- Export Student Logs
- Classroom Management

---

## 👨‍🎓 Student Dashboard

- Secure Login
- Task Management
- Live Productivity Timer
- Receive Live Announcements
- Website Access Checker
- Activity History
- Personal Dashboard

---

## ⚡ Real-Time Communication

- Socket.IO Integration
- Instant Notifications
- Live Synchronization
- Classroom Broadcast System

---

## 🌐 Website Access Control

- Dynamic Website Blocklist
- Website Validation
- Focus Mode
- Teacher Controlled Access

---

## 🔒 Security

- JWT Authentication
- Password Hashing (bcrypt)
- Protected APIs
- HTTP-only Cookies
- Role Based Authorization

---

## 🛠 Tech Stack

### Frontend

- HTML5
- CSS3
- JavaScript (ES6)
- Vite
- Socket.IO Client

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- JWT
- bcrypt
- Cookie Parser
- dotenv

---

# 📂 Project Structure

```text
BYOD
│
├── backend
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── socket
│   ├── scripts
│   ├── utils
│   └── server.js
│
├── frontend
│   ├── public
│   ├── src
│   ├── assets
│   ├── components
│   ├── pages
│   └── services
│
└── README.md
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/<your-username>/BYOD.git
cd BYOD
```

---

# ⚙ Backend Setup

```bash
cd backend
npm install
```

Create `.env`

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
SESSION_SECRET=your_session_secret
```

(Optional)

```bash
node scripts/seed.js
```

Start Server

```bash
npm run dev
```

Runs on

```
http://localhost:3000
```

---

# 💻 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Runs on

```
http://localhost:5173
```

---

# 🔑 Demo Credentials

### Teacher

```
Email:
teacher@school.edu

Password:
teacher123
```

### Student

```
Email:
alice@school.edu

Password:
student123
```

---

# 📊 Application Workflow

```text
Teacher Login
      │
      ▼
Manage Students
      │
      ├── Send Live Announcement
      ├── Manage Website Blocklist
      ├── Monitor Student Logs
      └── Export Reports

Student Login
      │
      ▼
Create Task
      │
      ▼
Start Productivity Timer
      │
      ▼
Receive Live Announcement
      │
      ▼
Check Website Access
      │
      ▼
Activity Stored in MongoDB
```

---

# 📸 Screenshots

## 🔐 Login Page

<img width="911" src="https://github.com/user-attachments/assets/8c94ff54-526f-433b-89f6-6155de7a728a"/>

---

## 👨‍🏫 Teacher Dashboard

<img width="1836" src="https://github.com/user-attachments/assets/161053c4-536c-4095-a8fb-015d9ff04e43"/>

<img width="1915" src="https://github.com/user-attachments/assets/8af37130-f74f-4d9e-af37-019ead495c49"/>

<img width="1865" src="https://github.com/user-attachments/assets/3081f33c-611f-4762-ab02-e999d847b46b"/>

---

## 👨‍🎓 Student Dashboard

<img width="1901" src="https://github.com/user-attachments/assets/87fa268a-f43b-4fcc-b4dc-b650c2beb1be"/>


---

## ⏱ Productivity Timer

<img width="1916" src="https://github.com/user-attachments/assets/2b1afec9-5790-4276-8ac8-ee70bad680db"/>

---

## 🌐 Website Access Checker

<img width="605" src="https://github.com/user-attachments/assets/c7a70974-65ba-4500-afc8-44db0b334e3b"/>

---

## 📢 Live Announcement

<img width="1311" src="https://github.com/user-attachments/assets/74b30961-1eb2-4853-bab4-93736e86a7ee"/>

---

# 🚀 Future Enhancements

- AI-Based Productivity Analysis
- Attendance Management
- Assignment Submission
- Analytics Dashboard
- Email Notifications
- Mobile Responsive UI
- Dark / Light Theme
- Multi-Class Support

---

# 🤝 Contributing

```bash
git checkout -b feature-name
git commit -m "Added new feature"
git push origin feature-name
```

Create a Pull Request.

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Developers

### Mayank Peswani

### Prem Kumar Gupta

**B.Tech Computer Science & Engineering**

---

<div align="center">

## ⭐ If you found this project useful, don't forget to Star the Repository!

Made with ❤️ using Node.js, Express, MongoDB & Socket.IO

</div>
