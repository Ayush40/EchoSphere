# 🎙️ EchoSphere

> A lightweight WebRTC-based audio communication platform that allows users to connect in real-time across multiple rooms — no video, just pure voice clarity.

---

## 🌐 Features

- 🔊 Real-time peer-to-peer audio using WebRTC
- 🔒 Secure room-based architecture (no cross-talk)
- 🔄 Join/leave rooms dynamically
- 🚫 No media servers required — direct peer connections
- ⚡ Lightweight, low-latency voice communication
- 📱 Responsive UI (desktop & mobile)

---

## 🏗️ Tech Stack

### 💻 Frontend  
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="30" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="30" />
  <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" width="30" />
</p>

### 🖥️ Backend  
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="30" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="30" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/socketio/socketio-original.svg" width="30" />
</p>

### ⚙️ Tools & Infra  
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="30" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="30" />
</p>

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/Aysuh40/echosphere.git
cd echosphere
```

### 2. Install Dependencies

#### For Frontend

```bash
cd frontend
npm install
```

#### For Backend

```bash
cd backend
npm install
```

### 3. Run the Project

Open two terminal windows and run each service:

#### Terminal 1: Backend

```bash
cd backend
npm run dev
```

#### Terminal 2: Frontend

```bash
cd frontend
npm run dev
```

### 4. Open in Browser

Open your browser and navigate to:

```
http://localhost:5173
```

## 🛡️ Security

- Room names are validated and escaped
- No media storage or recording
- Peer connections are end-to-end (STUN/TURN optional)

## 🙌 Contributing

Pull Requests and suggestions are welcome!  
Please open issues for bugs, features, or improvements.
