# Video Chat App (c218)

A WebRTC peer-to-peer video chat application with a shared room system, text chat, and mute/video controls, built with Node.js.

## Features
- Real-time video streaming via PeerJS / WebRTC
- Socket.io signaling for joining rooms and broadcasting chat messages
- Auto-generates a unique room URL on the home page (`/`)
- Text chat shown in a sidebar
- Bootstrap-based UI with mute, video toggle, and show-chat buttons

## Tech Stack
- Node.js
- Express 4
- EJS templating
- Socket.io 4
- PeerJS (`peer` server) + WebRTC
- Bootstrap 4 / jQuery

## Project Structure
```
c218/
├── server.js          # Express + Socket.io + PeerJS server
├── package.json
├── views/index.ejs    # room UI template
└── public/
    ├── script.js      # client-side video + chat logic
    └── style.css
```

## Installation
```bash
npm install
```

## Usage
```bash
npm start
```
Open `http://localhost:3030` — you will be redirected to a unique room, which you can share with others to video chat and message.