# 🚀 QuickChat - Modern Real-Time Messaging Platform

![QuickChat Banner](https://img.shields.io/badge/QuickChat-Messaging-blueviolet?style=for-the-badge&logo=appveyor)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

QuickChat is a full-stack, real-time messaging application designed for seamless communication. Built with the **MERN stack** (MongoDB, Express, React, Node.js) and powered by **Socket.io**, it offers a premium, responsive, and secure chatting experience.

---

## ✨ Key Features

- 💬 **Real-Time Communication**: Instant messaging powered by Socket.io for a lag-free experience.
- 🖼️ **Image Sharing**: Send memories instantly with Cloudinary-integrated image uploading.
- 🔐 **Robust Authentication**: Secure login and signup with JWT (JSON Web Tokens) and Bcrypt hashing.
- 🟢 **Live Status**: See who's online in real-time with active user tracking.
- 💌 **Smart Notifications**: Built-in unseen message counters and read receipts.
- 👤 **Custom Profiles**: Personalize your presence with editable profile pictures and details.
- 🎨 **Modern UI/UX**: A stunning, glassmorphic design built with **Tailwind CSS 4.0**.
- 📱 **Fully Responsive**: Optimized for desktop, tablet, and mobile screens.

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: [React.js](https://reactjs.org/) (v19)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (v4.0)
- **State Management**: React Context API
- **Routing**: React Router 7
- **Icons**: Lucide React
- **Notifications**: React Hot Toast
- **Build Tool**: Vite

### Backend
- **Environment**: [Node.js](https://nodejs.org/)
- **Framework**: [Express.js](https://expressjs.com/)
- **Real-time**: [Socket.io](https://socket.io/)
- **Database**: [MongoDB](https://www.mongodb.com/) (Mongoose ODM)
- **Media**: [Cloudinary](https://cloudinary.com/) (Cloud-based image storage)
- **Security**: JWT & Bcrypt.js

---

## 📸 Screenshots

| Sign Up |
| <img width="1919" height="871" alt="Screenshot 2026-04-06 144738" src="https://github.com/user-attachments/assets/72f6e566-cac0-4621-a4bd-ed89dd83df35" /> |

| Login |
| <img width="1356" height="635" alt="Screenshot 2026-04-06 144751" src="https://github.com/user-attachments/assets/9ddb5753-c70d-4099-a794-97c49cb9474e" /> |

| Chat Interface |
| <img width="1919" height="879" alt="Screenshot 2026-04-06 144654" src="https://github.com/user-attachments/assets/e6891576-c1f4-4794-8641-6e56caa4f9dc" /> |

| Edit Profile |
| <img width="1919" height="881" alt="Screenshot 2026-04-06 144709" src="https://github.com/user-attachments/assets/4f2a494a-e5ad-4acc-9b8e-225db1b71589" /> |

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- MongoDB Atlas Account
- Cloudinary Account

### 1. Clone the repository
```bash
git clone https://github.com/raihanzzz/QuickChat.git
cd QuickChat
```

### 2. Backend Setup
```bash
cd server
npm install
```
Create a `.env` file in the `server` directory:
```env
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
NODE_ENV=development
```
Start the server:
```bash
npm run server
```

### 3. Frontend Setup
```bash
cd ../client
npm install
```
Create a `.env` file in the `client` directory:
```env
VITE_API_URL=http://localhost:5000/api
```
Start the dev server:
```bash
npm run dev
```

---

## 📂 Project Structure

```text
QuickChat/
├── client/                # React Vite Frontend
│   ├── src/
│   │   ├── components/    # Reusable UI Components
│   │   ├── context/       # Auth & Message Contexts
│   │   ├── pages/         # Page Views
│   │   └── lib/           # Axios & Utility Helpers
├── server/                # Node.js Express Backend
│   ├── controllers/       # Business Logic
│   ├── models/            # MongoDB Schemas
│   ├── routes/            # API Endpoints
│   ├── lib/               # DB & Cloudinary Configs
│   └── server.js          # Entry Point & Socket Setup
└── README.md
```

---

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---


## 👨‍💻 Author

**Md Raihan**
- GitHub: https://github.com/raihanzzz
- LinkedIn: https://www.linkedin.com/in/md-raihan-9809592aa/

---

*⭐ If you like this project, please consider giving it a star!*
