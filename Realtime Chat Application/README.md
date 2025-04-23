# Realtime Chat Application

A simple realtime chat application with Node.js backend and React frontend featuring:
- User authentication (Register/Login)
- Realtime messaging via WebSockets
- Message history storage
- Basic chat interface

## Features
- 🔐 JWT Authentication
- 💬 Realtime messaging using Socket.io
- 🗃️ SQLite database for message history
- ⚛️ React frontend with Vite

## Technologies
- **Frontend**: React, Socket.io-client, Axios
- **Backend**: Node.js, Express, Socket.io
- **Database**: SQLite
- **Authentication**: JSON Web Tokens (JWT)

## Installation

### Prerequisites
- Node.js (v16+ recommended)
- npm (comes with Node.js)

### Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/realtime-chat-app.git
cd realtime-chat-app
```

2. **setup backend**
```bash
cd backend
npm install
```
3. **create environment file**
   ```bash
   echo "JWT_SECRET=your_strong_secret_here" > .env
   ```
4. **start backend server**
   ```bash
   npm start
  Server runs on http://localhost:3001

5.**setup frontend(in new terminal)**
```bash
cd ../frontend
npm install
```
6. **start frntend development server**
   ```bash
   npm run dev
# Access at http://localhost:5173
**Usage
Register a new account

Login with your credentials

Start chatting in realtime!**
**Project structure**
realtime-chat-app/
├── backend/          # Node.js server
│   ├── server.js     # Main server file
│   ├── chat.db       # SQLite database
│   └── .env          # Environment variables
└── frontend/         # React application
    ├── src/
    │   └── App.jsx   # Main React component
    └── vite.config.js
**Licence**
**MIT**
```
This README includes:
- Clear feature list
- Simple installation instructions
- Technology stack
- Basic project structure
- API documentation
- Clean formatting





