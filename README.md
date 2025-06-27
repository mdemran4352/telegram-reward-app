# Telegram Reward Mini App

🎁 A simple Telegram Mini App where users can earn coins by watching videos.

## 🔥 Features
- Sign in with Google
- Watch videos and earn coins
- One coin per full video watch (daily limit optional)
- Coins saved in local storage
- Firebase Authentication
- Simple and mobile-friendly UI
- Telegram Web App compatible

## 🚀 Live Demo
👉 [https://mdemran4352.github.io/telegram-reward-app](https://mdemran4352.github.io/telegram-reward-app)

## ⚙️ How to Use
1. Click the **"Sign in with Google"** button
2. Watch any full video to earn 1 coin
3. Coins are stored per user (via localStorage and UID)

## 📂 Structure
- `index.html` – Main UI + Logic
- `videos.json` – List of reward videos (MP4 URL + title)
- `README.md` – Project description and guide

## 🧩 Customization
- You can edit `videos.json` to include your own hosted videos
- Replace `Monetag` code (if used) with your PID in `index.html`

## 🔐 Firebase Setup
- Make sure to enable **Google Sign-In** in Firebase Console
- Add your domain: `github.io` and `mdemran4352.github.io` to **authorized domains**
- Replace your Firebase config in `index.html`

---

✅ Built with ❤️ for Telegram Web Apps | Made by [Emran Hossain]
