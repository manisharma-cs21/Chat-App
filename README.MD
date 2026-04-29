# 💬 Real-Time Chat Application (Socket.IO)

A scalable real-time chat application built using **Node.js, Express, MongoDB, and Socket.IO**.
This project focuses on **backend architecture, real-time communication, and secure user interactions**.

---

## 🚀 Features

* 🔐 **JWT Authentication**

  * Secure login & registration system
  * Token-based session management

* 💬 **Real-Time Messaging**

  * Instant bidirectional communication using Socket.IO
  * Messages delivered in real-time without refresh

* 🟢 **Online/Offline Status**

  * Track active users dynamically

* ✍️ **Typing Indicators**

  * Shows when a user is typing

* 🖼️ **Media Uploads**

  * Integrated **Cloudinary** for image/file sharing

* ⚙️ **Scalable Backend**

  * Modular architecture
  * Environment-based configuration using `.env`

---

## 🧩 Tech Stack

* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Mongoose)
* **Real-Time Engine:** Socket.IO
* **Authentication:** JWT
* **Media Storage:** Cloudinary

---

## 📂 Project Structure

```
chat-app/
├── controllers/
├── models/
├── routes/
├── sockets/
├── middleware/
├── config/
├── .env.example
└── server.js

---

## ▶️ Run Locally

```bash
# Clone the repo
git clone <your-repo-link>

# Go to backend folder
cd backend

# Install dependencies
npm install

# Start server
npm run dev
```

---

## 🌐 Future Improvements

* Group chat support
* Message read receipts
* Push notifications
* Better UI/UX

---

## 📌 Note

> This project primarily focuses on **backend architecture and real-time communication systems** rather than UI design.

---

⭐ If you found this project useful, consider giving it a star!
