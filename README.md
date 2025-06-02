# 💬 Real-Time Chat Application

A simple, real-time chat app built using **React**, **TypeScript**, and **Vite** on the frontend, with a **Node.js WebSocket** backend.

## 🚀 Features

- 🔐 Join or create chat rooms using a unique Room ID  
- 💬 Real-time messaging using WebSocket  
- 📱 Responsive and modern UI with Tailwind CSS  
- ⚡ Super-fast development with Vite

---

## 📁 Project Structure

```
chat-frontend/   # Frontend - React + Vite + TypeScript
chatbackend/     # Backend - Node.js + WebSocket (ws)
```

---

## ✅ Prerequisites

- Node.js (v18 or later)
- npm (v9+ recommended)

---

## 🛠️ Getting Started

### 🔧 Backend Setup

1. Open a terminal and navigate to the backend directory:

   ```bash
   cd chatbackend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the WebSocket server:

   If using TypeScript directly:

   ```bash
   npx ts-node src/index.ts
   ```

   Or, compile TypeScript and run:

   ```bash
   tsc && node dist/index.js
   ```

---

### 🎨 Frontend Setup

1. Open another terminal and navigate to the frontend directory:

   ```bash
   cd chat-frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser to access the app.

---

## 💡 Usage

- Enter a Room ID to join an existing room.
- Leave the input blank to create a new unique Room ID.
- Start chatting in real-time with others in the same room.

---

## 🧰 Built With

- **Frontend:** React, TypeScript, Vite, Tailwind CSS  
- **Backend:** Node.js, WebSocket (`ws` library)

---

## 📸 Screenshots

> *(Optional - Add screenshots or demo GIFs of the UI here)*

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

Built for fun and learning. Inspired by real-time communication tools like Discord and Slack 🎉
