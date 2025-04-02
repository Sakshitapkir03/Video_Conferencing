# Video Conferencing App

A simple video conferencing web application built with [insert tech stack here].

## 🚀 Features
- Real-time video and audio chat
- Screen sharing
- Chat messaging
- Easy room creation and joining

## 🛠️ Tech Stack
- Node.js
- Express
- WebRTC
- Socket.IO

Video_Conferencing/
├── 📁 public/                # Static assets served to the client
│   ├── 📁 css/               # CSS stylesheets
│   ├── 📁 js/                # Frontend JavaScript
│   ├── 📁 images/            # Any image assets
│   └── index.html           # Main client-facing HTML page

├── 📁 src/                   # Server-side code
│   ├── 📁 routes/            # Express route handlers
│   ├── 📁 controllers/       # Business logic / route controller functions
│   ├── 📁 utils/             # Utility/helper functions
│   ├── server.js            # Entry point of the backend server

├── 📁 sockets/               # WebSocket (Socket.IO) logic
│   └── socketHandler.js

├── 📁 config/                # Config files (env, database, etc.)
│   └── config.js

├── 📁 tests/                 # Test cases (unit, integration, etc.)

├── .env                     # Environment variables (not committed)
├── .gitignore               # Files/folders Git should ignore
├── README.md                # Project description and documentation
├── package.json             # Node.js project file with dependencies
├── package-lock.json        # Exact versions of installed dependencies

## 📦 Installation

```bash
git clone https://github.com/Sakshitapkir03/Video_Conferencing.git
cd Video_Conferencing
npm install
npm start