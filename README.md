# 🎮 Tic-Tac-Toe

A real-time, two-player online Tic-Tac-Toe game built with **Node.js**, **Express**, and **Socket.IO**.  

> Challenge your friend to a classic game — online, instant, and sleek.

---

## 🌐 Telegram Contact

Telegram: [@isyrae](https://t.me/isyrae)

---

## 📸 Screenshots

![Landing](https://files.catbox.moe/w31epa.png)  
![Main Page](https://files.catbox.moe/p57s9v.png)  

---

## 🚀 Features

- 🆚 Real-time multiplayer — powered by WebSockets
- 🧠 Smart room pairing: share room code to play with friends
- 🎨 Modern responsive UI with sound and animations
- 🔒 HTTPS support for secure game sessions
- ⚙️ Easy to deploy on any VPS or Node-supported host

---

## 📦 Tech Stack

- **Frontend**: Vanilla JS, HTML5, CSS3
- **Backend**: Node.js, Express.js
- **Realtime Engine**: Socket.IO
- **Hosting**: Self-hosted on aaPanel + custom domain

---

## 🛠️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/isyrae/Tic-Tac-Toe.git
cd Tic-Tac-Toe
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the Game Server

```bash
node server.js
```

Or use `pm2` (recommended for production):

```bash
pm2 start server.js --name Tic-Tac-Toe
```

The game will run on `http://localhost:3000` by default.

---

## 🌍 Hosting with aaPanel (Optional)

If using [aaPanel](https://www.aapanel.com/):

- Set up reverse proxy from your domain (`yourdomain.com`) to `127.0.0.1:3000`
- Enable WebSocket support
- Add free SSL via Let's Encrypt for HTTPS

---

## 📁 Project Structure

```
Tic-Tac-Toe/
├── public/              # Static assets (HTML, CSS, JS, sounds)
├── server.js            # Express + Socket.IO game server
├── package.json
└── README.md
```

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

```
MIT License

Copyright (c) 2025 Rahul Mondal

Permission is hereby granted, free of charge, to any person obtaining a copy...
```

## 📬 Contact

Feel free to reach out for feedback, collaborations, or questions:

📧 hello.isyrae@gmail.com  
🌐 [https://isyrae.xyz](https://isyrae.xyz)

---

⭐ Star the repo if you like it — and enjoy playing Tic-Tac-Toe online!
