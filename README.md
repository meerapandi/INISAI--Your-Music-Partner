# 🎵 Inisai Music Web App + Secure Login

This is a full-stack music web app named **Inisai**, featuring a **secure login system** powered by PHP and XAMPP, and a music front-end hosted at [inisai-bymeera.netlify.app](https://inisai-bymeera.netlify.app).

## WATCH THE DEMO VIDEO!!!

[![Watch the video](https://img.youtube.com/vi/4JNOBmIAaAI/hqdefault.jpg)](https://youtu.be/4JNOBmIAaAI?si=2D4Q4OftdvtMAfHo)


---

## 🛡️ Secure Login System

The login system is built using:
- HTML, CSS, JavaScript (Frontend)
- PHP (Backend with XAMPP)
- OTP verification
- Password recovery
- Registration & email-based verification using SendMail

📁 Path: `login/`

---

## 🎶 Inisai Music App (Frontend)

The music app is built using:
- React + Vite
- TailwindCSS
- Responsive UI
- Smooth navigation

📁 Root React Project: `./src`, `index.html`, etc.

Hosted live at 👉 [inisai-bymeera.netlify.app](https://inisai-bymeera.netlify.app)

---

## 🚀 How to Run Locally

### 1. Run Login Module (PHP)
1. Copy the `login/` folder into your XAMPP `htdocs/`
2. Start Apache in XAMPP
3. Visit: `http://localhost/login/`

### 2. Run Inisai Music App (React)
```bash
npm install
npm run dev

📁 Project Structure
inisai-music-app/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── context/
│   ├── login/           # Login Module files
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── netlify.toml
├── package.json
├── tailwind.config.js
├── postcss.config.js
└── vite.config.js

**login Module files**
login/
├── .hintrc
├── forgot.html
├── forgot.php
├── index.html  <-- Login page
├── login.php
├── register.html
├── register.php
├── script.js
├── style.css
├── styles.css
├── verify_otp.html
├── verify_otp.php
├── verify_otp2.html
├── verify_otp2.php
├── image/
   ├── button.jpg
   ├── button2.jpg
   └── mainbg.jpg


🌐 Live Hosting
Only the front-end is hosted:

🔗 https://inisai-bymeera.netlify.app

Login and redirection work locally via PHP (XAMPP).

Inisai Music Web App with Secure Login
This project combines a secure PHP-based login and registration system with a React-powered music streaming web app. Users log in through a local XAMPP-hosted module featuring OTP verification and password recovery. Upon successful login, they are redirected to the hosted Inisai music interface at inisai-bymeera.netlify.app. Designed with user security and sleek UI in mind, it offers both frontend creativity and backend authentication.
