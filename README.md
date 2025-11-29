
# 🚀 Slacky — Realtime Chat App (MERN)

## 📖 Detailed Description

A modern Slack-style chat platform built for real-world collaboration.
Channels, direct messages, threads, reactions, video calls, polls, file sharing — all backed by production-grade infrastructure.

## ✨ Features

### 💬 Real-Time Chat

Smooth Slack-style messaging for active teams.

🟢 Create channels powered by Stream Chat

🟢 Reply-in-thread to keep topics clean

🟢 Emoji reactions on messages & replies

🟢 Pinned messages to highlight important updates

### 🧵 Conversational Depth

No more clutter or message chaos.

🟣 Thread-based replies to maintain context

🟣 Works across channels & DMs

🟣 Sub-discussions without disrupting the flow

### 📎 Smart File Sharing

Share everything without leaving the workspace.

📦 Upload images, PDFs, ZIPs & docs

📦 Inline previews for supported media

📦 Quick access to shared files per channel

### 🗳️ Powerful Polls

Let the team decide quickly & transparently.

📊 Multi-select options

📊 Anonymous voting

📊 Add user-generated poll choices

📊 Poll comments for discussion

### 👥 Direct Messages

Private communication — without friction.

💬 1–1 personal chats

💬 Small group DMs

💬 Lightweight, fast, persistent

💬 Real-time sync

### 🎥 Video Calls

Collaboration that feels human.

🎬 Built using Stream Video

🎬 Live emoji reactions in calls

🎬 Screen sharing — window or entire screen

🎬 Call recording for async teams

### 🔐 Authentication & Security

Enterprise ready from day one.

🔒 Clerk-powered authentication

🔒 Secure session + account management

🔒 Production-grade reliability


## Demo

https://slacky-frontend.vercel.app/auth



## 📸 Screenshots

### 🔐 Slacky - Auth Page
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-Auth%20Page.png" width="700"/>

### 💬 Slacky - Channel Chat
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-Channel%20Chat.png" width="700"/>

### 🗳️ Slacky - Create Poll Options
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-Create%20Poll%20Options.png" width="700"/>

### 🗳️ Slacky - Create Poll
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-Create%20Poll.png" width="700"/>

### ⏳ Slacky - Loading Page
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-Loading%20Page.png" width="700"/>

### 📢 Slacky - New Channel
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-New%20Channel.png" width="700"/>

### 👥 Slacky - Personal Chat
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-Personal%20Chat.png" width="700"/>

### 📌 Slacky - Pinned Message
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-Pinned%20Message.png" width="700"/>

### 📊 Slacky - Poll Result
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-Poll%20Result.png" width="700"/>

### 🧵 Slacky - Thread Reply
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-Thread%20Reply.png" width="700"/>

### ➕ Slacky - Create & Invite Channel
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-To%20Create%26Invite%20Channel.png" width="700"/>

### 🎥 Slacky - Video Call with Reactions
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-Video%20Call%20with%20Reaction.png" width="700"/>

### 🎥 Slacky - Video Call
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-Video%20Call.png" width="700"/>

### 🖥️ Slacky - Screen Share
<img src="https://raw.githubusercontent.com/Aniketpalve02/slacky-chatapp-mern/refs/heads/main/frontend/public/screenshots/Slacky-screen%20share.png" width="700"/>



## 🏗️ Tech Stack

### Frontend

| Technology                                                                                         | Description                      |
| -------------------------------------------------------------------------------------------------- | -------------------------------- |
| ![React](https://img.shields.io/badge/React-20232A?logo=react\&logoColor=61DAFB)                   | Component-based UI development   |
| ![Tailwind](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss\&logoColor=white)     | Utility-first responsive styling |
| ![TanStack](https://img.shields.io/badge/TanStack%20Query-FF4154?logo=reactquery\&logoColor=white) | Server state caching & data sync |


### Backend

| Technology                                                                               | Description                                |
| ---------------------------------------------------------------------------------------- | ------------------------------------------ |
| ![Node](https://img.shields.io/badge/Node.js-43853D?logo=node.js\&logoColor=white)       | JavaScript runtime for backend logic       |
| ![Express](https://img.shields.io/badge/Express.js-000000?logo=express\&logoColor=white) | Fast and minimalist web framework          |
| ![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248?logo=mongodb\&logoColor=white) | NoSQL database for chats, users & metadata |


### Infrastructure

| Technology                                                                             | Description                           |
| -------------------------------------------------------------------------------------- | ------------------------------------- |
| ![Stream](https://img.shields.io/badge/Stream-0060f4?logo=stream\&logoColor=white)     | Real-time chat & video infrastructure |
| ![Clerk](https://img.shields.io/badge/Clerk-F41759?logo=clerk\&logoColor=white)        | Production-grade authentication       |
| ![Inngest](https://img.shields.io/badge/Inngest-1C1C1C?logo=inngest\&logoColor=00D2FF) | Background jobs (auth ↔ DB sync)      |
| ![Sentry](https://img.shields.io/badge/Sentry-362D59?logo=sentry\&logoColor=white)     | Error monitoring & performance        |



## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

### Backend (/Backend)

```bash
PORT=5001
MONGO_URI=your_mongo_uri_here

NODE_ENV=development

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key_here
CLERK_SECRET_KEY=your_clerk_secret_key_here

STREAM_API_KEY=your_stream_api_key_here
STREAM_API_SECRET=your_stream_api_secret_here

SENTRY_DSN=your_sentry_dsn_here

INNGEST_EVENT_KEY=your_inngest_event_key_here
INNGEST_SIGNING_KEY=your_inngest_signing_key_here

CLIENT_URL=http://localhost:5173
```

### Frontend (/Frontend)

```bash
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key_here
VITE_STREAM_API_KEY=your_stream_api_key_here
VITE_SENTRY_DSN=your_sentry_dsn_here
VITE_API_BASE_URL=http://localhost:5001/api
```


## Installation

### 🔧 Run the Backend

```bash
cd backend
npm install
npm run dev
```

### 💻 Run the Frontend

```bash
cd frontend
npm install
npm run dev
```
    
