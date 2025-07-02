# 💬 Real-Time Chat Application

## Task-04 | ProDigy InfoTech Internship  
By **Comillas Negras**

A full-featured real-time chat application built using **WebSockets**, enabling users to communicate instantly through **public chat rooms** or **private conversations**. This system provides user registration, authentication, and real-time message updates, offering a seamless messaging experience.

---

## ✨ Visual Theme

> **Background**: Dark with Neon Lights & Blue Gradient  
> **Design Motifs**: Circles with Gradient | Subtle Stars Pattern  
> **Mood**: Futuristic, interactive, and immersive

---

## 💡 Features

- 👤 User Registration & Login
- 💬 Real-time Messaging via WebSockets (Socket.io)
- 🏠 Join Public Chat Rooms
- 🔒 Initiate Private Chats (1-on-1)
- 🟢 Presence Indicators (Online/Offline)
- 📚 Chat History (optional feature)
- 🔔 In-app Notifications
- 📁 Multimedia File Sharing (images, files, etc.)

---

## 🔧 Tech Stack

- **Frontend**: React.js / HTML5 + CSS3 + JavaScript
- **Backend**: Node.js + Express.js
- **WebSockets**: Socket.IO
- **Database**: MongoDB (for users and message history)
- **Authentication**: JWT / bcrypt
- **Styling**: Tailwind CSS / Material UI / Custom Neon Theme

---

## 🛠️ How to Run Locally

### 1. Clone the repository:

```bash
git clone https://github.com/yourusername/realtime-chat-app.git
2. Install dependencies:
bash
Copy
Edit
cd realtime-chat-app
npm install
3. Configure environment variables:
Create a .env file in the root:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
4. Start the application:
bash
Copy
Edit
npm run dev
Visit: http://localhost:5000 in your browser.
