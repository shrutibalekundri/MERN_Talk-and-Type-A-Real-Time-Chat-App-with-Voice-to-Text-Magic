# 💬 MERN Chat Application with Real-Time Messaging

<p align="center">
<img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb">
<img src="https://img.shields.io/badge/Express.js-Backend-000000?style=for-the-badge&logo=express">
<img src="https://img.shields.io/badge/React.js-Frontend-61DAFB?style=for-the-badge&logo=react">
<img src="https://img.shields.io/badge/Node.js-Runtime-339933?style=for-the-badge&logo=node.js">
<img src="https://img.shields.io/badge/Socket.IO-RealTime-010101?style=for-the-badge&logo=socketdotio">
</p>

---

# 📖 About the Project

The **MERN Chat Application** is a real-time communication platform built using the MERN stack. It enables secure one-to-one and group conversations with instant message delivery, online user status, file sharing, and JWT-based authentication, providing a seamless and interactive messaging experience.

---

# ✨ Key Features

- 💬 Real-Time One-to-One Messaging
- 👥 Group Chat Support
- 🟢 Live Online & Offline User Status
- 🔔 Instant Message Notifications
- 📎 Secure File Sharing
- 🔐 JWT Authentication & Protected Routes
- 🛠️ Admin Dashboard for User Management
- ⚡ Socket.IO Based Real-Time Communication
- 📱 Responsive User Interface

---

# 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Frontend | React.js, Redux Toolkit, Vite, CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Authentication | JWT, Bcrypt |
| Real-Time Communication | Socket.IO |
| API Testing | Postman |
| Version Control | Git & GitHub |

---

# 🏗️ Application Workflow

```text
User Login
     │
     ▼
JWT Authentication
     │
     ▼
Connect via Socket.IO
     │
     ▼
Send / Receive Messages
     │
     ├────────► Online Status Updates
     │
     ├────────► Group Conversations
     │
     ├────────► File Sharing
     │
     ▼
MongoDB Database
```

---

# 📂 Project Structure

```text
MERN_Chat_App/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── socket/
│   ├── middleware/
│   └── package.json
│
├── .gitignore
├── README.md
└── package-lock.json
```

---

# 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/yourusername/MERN_Chat_App.git
```

### Install Frontend

```bash
cd frontend
npm install
npm run dev
```

### Install Backend

```bash
cd ../server
npm install
npm start
```

---

# ⚙️ Environment Variables

Create a `.env` file inside the server folder and configure:

```env
MONGODB_URI=
JWT_SECRET=
PORT=
CLIENT_URL=
```

---

# 🔮 Future Enhancements

- 📞 Voice Calling
- 🎥 Video Calling
- 😊 Emoji & GIF Support
- 📱 Mobile Application
- 🌙 Dark & Light Themes
- 🔍 Advanced Chat Search
- ✍️ Message Editing & Deletion
- 🔔 Push Notifications

---

# 👩‍💻 My Contributions

- Designed and developed the complete MERN application.
- Implemented JWT-based authentication and authorization.
- Integrated Socket.IO for real-time messaging.
- Developed one-to-one and group chat functionality.
- Built file sharing and online status features.
- Designed responsive frontend and RESTful backend APIs.

---

# 📄 License

This project is developed for educational and learning purposes.

---

<p align="center">

⭐ If you found this project helpful, consider giving it a star!

**Connecting Conversations in Real Time. 💬🚀**

</p>
