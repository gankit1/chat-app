# Chat Room Application

A real-time chat application built with React, Node.js, Express, and Socket.io.

## 🚀 Features
- Join chat rooms with unique names
- Real-time messaging using Socket.io
- Shows active users in the room
- Lightweight and responsive UI

## 🛠️ Tech Stack
- **Frontend:** React, React Router, Tailwind CSS
- **Backend:** Node.js, Express, Socket.io
- **Package Manager:** Yarn / NPM

## 📦 Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/gankit1/chat-room.git
cd chat-room
```

### 2️⃣ Install Dependencies
#### For Client:
```sh
cd client
yarn install
```
#### For Server:
```sh
cd server
yarn install
```

## ▶️ Running the Application

### 1️⃣ Start the Server
```sh
cd server
yarn start
```

### 2️⃣ Start the Client
```sh
cd client
yarn start
```

## 🌐 Usage
1. Open `http://localhost:3000`
2. Enter a **username** and **room name** to join a chat
3. Start messaging in real-time

## 🔧 Troubleshooting
**Error: `error:0308010C:digital envelope routines::unsupported`?**  
Run the command below before starting the client:
```sh
export NODE_OPTIONS=--openssl-legacy-provider
```
Or add this to `package.json` scripts:
```json
"scripts": {
  "start": "export NODE_OPTIONS=--openssl-legacy-provider && react-scripts start"
}
```

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

