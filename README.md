# 🤖 AI Social Media Automation Platform

A full-stack AI-powered social media automation platform built with the MERN Stack. Schedule posts, connect multiple social media accounts, and generate engaging content using AI — all from a single dashboard.

---

## 🚀 Live Demo

[![Live Demo](https://img.shields.io/badge/Live-Demo-red?style=for-the-badge)](https://ai-social-media-scheduler-six.vercel.app/)

---

## 📸 Screenshots

<img width="1278" height="677" alt="image" src="https://github.com/user-attachments/assets/cd6f89b2-a923-4fe9-8e22-1ebc16734edf" />

<img width="1293" height="663" alt="image" src="https://github.com/user-attachments/assets/e8a8162f-cc1a-4a05-a518-d1ed23bd8ba9" />



---

## ✨ Features

- 🔐 Authentication & User Management (JWT)
- 📱 Connect Multiple Social Media Accounts
- 🗓️ Schedule Posts Across Platforms
- 🤖 AI Powered Post & Image Generator
- 📊 Social Media Automation Dashboard
- 📡 MERN Stack Backend & REST APIs
- 💅 Responsive Admin Dashboard
- ☁️ Full Project Deployment

---

## 🛠️ Tech Stack

| Frontend | Backend | Database | APIs |
|----------|---------|----------|------|
| React JS | Node JS | MongoDB | OpenAI API |
| Tailwind CSS | Express JS | Mongoose | Zernio API |
| Vite | JWT Auth | | CodeRabbit |

---

## ⚙️ Getting Started

### Prerequisites
- Node.js v18+
- MongoDB URI
- OpenAI API Key
- Zernio API Key

### Installation

```bash
# Clone the repo
git clone https://github.com/iamrealkkd/AI-SOCIAL-MEDIA-SCHEDULER.git
cd AI-SOCIAL-MEDIA-SCHEDULER
```

```bash
# Install server dependencies
cd server
npm install
```

```bash
# Install client dependencies
cd ../client
npm install
```

### Environment Variables

**server/.env**
```env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_key
ZERNIO_API_KEY=your_zernio_key
```

**client/.env**
```env
VITE_API_URL=http://localhost:5000
```

### Run Locally

```bash
# Start server
cd server
npm run dev

# Start client (new terminal)
cd client
npm run dev
```

---

## 📁 Project Structure
```
AI-SOCIAL-MEDIA-SCHEDULER/
├── client/          # React frontend
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── api/
│   │   └── assets/
└── server/          # Node/Express backend
    ├── routes/
    ├── models/
    ├── controllers/
    └── middleware/
```
 
---
 
## 🙌 Acknowledgements
 
- [OpenAI](https://openai.com)
- [Zernio](https://zernio.com)
- [CodeRabbit](https://coderabbit.ai)
