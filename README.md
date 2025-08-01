# 🎲 Game-Night Planning Application

Plan, organize, and enjoy game nights like never before! Game-Night is a web application built to simplify the process of creating and managing various types of game events — from board games to video games and RPGs.

---

## 📌 Project Overview

Game-Night helps users:
- Create and manage game night events
- Invite friends and track RSVPs
- Suggest games based on the group’s preferences
- Interact in real-time for a more engaging experience

---

## 📄 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/RudrakshDev/Game-Night.git

# Navigate to the project directory
cd Game-Night

cd server
npm install
npm start

cd ../client
npm install
npm run dev
```

---

## 📁 Environment Variables

Create a `.env` file inside the `server/` (backend) directory with the following variables:

```env
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
