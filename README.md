# 💬 Real-Time Chat Application

A full-stack real-time chat application built using the MERN stack and Socket.io. This project enables users to communicate instantly through a sleek, responsive interface with features like user authentication and persistent chat history.

## 🚀 Features

- 🔒 User Authentication (Login/Register)
- 💬 Real-time messaging with Socket.io
- 📱 Responsive and mobile-friendly UI
- 🕒 Timestamps and typing indicators
- 🗂️ Chat history persistence using MongoDB
- 🧑‍🤝‍🧑 One-on-one and/or group chat support *(if applicable)*

## 🛠️ Tech Stack

- **Frontend**: React.js, Shadcn UI, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Real-time Engine**: Socket.io
- **Database**: MongoDB (with Mongoose)
- **Authentication**: JWT (JSON Web Tokens)

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/realtime-chat-app.git
cd realtime-chat-app

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install

# Start the development servers
npm run dev  # or use separate terminals for client and server
