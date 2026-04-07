# Pittu Music Player 🎵

A premium, high-fidelity music streaming application built with the MERN stack. Experience a "Sonic Galaxy" with a sleek neon-glassmorphic design and seamless playback.

## ✨ Features

- **Full-Length Playback**: High-quality audio streaming powered by `yt-dlp`.
- **Instant Discovery**: Search millions of tracks via the iTunes Search API.
- **Smart Loading**: Uses 30-second previews for instant playback while resolving high-fidelity streams in the background.
- **Personal Library**: Save your favorite tracks and access them anytime.
- **User Authentication**: Secure signup and login system.
- **Modern UI**: Immersive animations with Framer Motion and a responsive glassmorphic design.

## 🚀 Tech Stack

- **Frontend**: React.js, Vite, Framer Motion, Lucide Icons, CSS Modules.
- **Backend**: Node.js, Express.js.
- **Database**: MongoDB.
- **Tools**: yt-dlp, JWT (Authentication).

## 🛠️ Getting Started

### Prerequisites

- Node.js installed.
- MongoDB instance (local or Atlas).
- `yt-dlp` installed and in your system PATH.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pittu-Sharma/AI-Integrated-Music-Player.git
   cd AI-Integrated-Music-Player
   ```

2. **Backend Setup:**
   ```bash
   cd backend
   npm install
   ```
   Create a `.env` file in the `backend` folder:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_secret_key
   ```
   Start the backend:
   ```bash
   npm run dev
   ```

3. **Frontend Setup:**
   ```bash
   cd ../frontend
   npm install
   npm run dev
   ```

## 📜 License

This project is licensed under the ISC License.
