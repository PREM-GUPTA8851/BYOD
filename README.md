# 🎓 BYOD Classroom Management System

A modern **Bring Your Own Device (BYOD)** classroom management system that enables teachers to monitor student productivity, communicate in real time, and create a focused learning environment through secure authentication, activity tracking, and website access control.

---

## ✨ Features

### 👨‍🏫 Teacher Dashboard
- Secure Login & Authentication
- Real-Time Announcements
- Website Blocklist Management
- Student Productivity Monitoring
- Activity Log Viewer
- Export Student Reports
- Classroom Management

### 👨‍🎓 Student Dashboard
- Secure Login
- Task Management
- Live Productivity Timer
- Real-Time Announcements
- Website Access Checker
- Activity History
- Personal Dashboard

### ⚡ Real-Time Communication
- Socket.IO Integration
- Instant Announcements
- Live Updates
- Fast Synchronization

### 📊 Productivity Tracking
- Start/Stop Task Timer
- Time Tracking
- Activity Logging
- Timestamp Recording
- Student Performance Monitoring

### 🌐 Website Access Control
- Teacher Managed Blocklist
- Website Validation
- Secure Browsing
- Focus Mode

### 🔒 Security
- JWT Authentication
- Password Hashing (bcrypt)
- HTTP-only Cookies
- Protected Routes
- Role-Based Access Control

---

# 🛠️ Tech Stack

## Frontend

- Vite
- HTML5
- CSS3
- JavaScript (ES6+)
- Socket.IO Client

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- JWT Authentication
- bcrypt
- Cookie Parser
- dotenv

---

# 📂 Project Structure

```text
BYOD/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── scripts/
│   ├── socket/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│   ├── vite.config.js
│   └── package.json
│
└── README.md
```

---

# 🚀 Getting Started

## 1. Clone Repository

```bash
git clone https://github.com/your-username/BYOD.git
cd BYOD
```

---

# ⚙ Backend Setup

Move to backend

```bash
cd backend
```

Install dependencies

```bash
npm install
```

Create a `.env` file

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
SESSION_SECRET=your_session_secret
```

(Optional)

Seed Demo Data

```bash
node scripts/seed.js
```

Start Backend

```bash
npm run dev
```

Backend runs at

```
http://localhost:3000
```

---

# 💻 Frontend Setup

Move to frontend

```bash
cd frontend
```

Install dependencies

```bash
npm install
```

Run project

```bash
npm run dev
```

Frontend runs at

```
http://localhost:5173
```

---

# 🔑 Demo Credentials

### Teacher

```text
Email    : teacher@school.edu
Password : teacher123
```

### Student

```text
Email    : alice@school.edu
Password : student123
```

> Available after running the seed script.

---

# 📊 Application Workflow

```text
Teacher Login
      │
      ▼
Manage Students
      │
      ├────────► Send Live Announcement
      │
      ├────────► Block Websites
      │
      ├────────► View Student Logs
      │
      └────────► Export Reports


Student Login
      │
      ▼
Create Tasks
      │
      ▼
Start Productivity Timer
      │
      ▼
Receive Live Announcements
      │
      ▼
Check Website Accessibility
      │
      ▼
Activity Stored in Database
```

---

# 📸 Screenshots

Add your project screenshots here.

```
screenshots/

├── Login.png
├── TeacherDashboard.png
├── StudentDashboard.png
├── Productivity.png
└── WebsiteChecker.png
```

---

# 🚀 Future Enhancements

- AI-based Productivity Analysis
- Attendance Management
- Assignment Submission
- Classroom Analytics
- Email Notifications
- Mobile Responsive Design
- Dark/Light Theme
- Multi-Class Support

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository

2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Developer
**Mayank Peswani**
**Prem Kumar Gupta**

B.Tech CSE Student

Passionate about Full Stack Development, Data Structures & Algorithms, and Software Engineering.

---

## ⭐ If you like this project, don't forget to Star the repository!
