# 🚀 create-e2e-saas

<div align="center">

**A production-ready CLI to instantly scaffold a full-stack MERN authentication system with JWT, OTP, and Email verification.**

[![npm version](https://img.shields.io/npm/v/create-e2e-saas)](https://www.npmjs.com/package/create-e2e-saas)
[![npm downloads](https://img.shields.io/npm/dt/create-e2e-saas.svg)](https://www.npmjs.com/package/create-e2e-saas)
[![React](https://img.shields.io/badge/React-19-blue)](https://reactjs.org/)
[![Tailwind](https://img.shields.io/badge/TailwindCSS-4-cyan)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

[Features](#-key-features) • [Architecture](#-architecture--modules) • [Quick Start](#-quick-start) • [Tech Stack](#-tech-stack)

</div>

---

## 📸 Project Media

![App Screenshot](assets/screenshot.png)

*(Add screenshots of the CLI running and the generated frontend here)*

[Watch Demo Video](assets/demo.mp4)

---

## 💡 Why This Exists

Tired of rebuilding authentication systems every time you start a new SaaS or hackathon project? `create-e2e-saas` gives you a **ready-to-run full-stack Auth system** completely configured and styled in seconds. No setup, no boilerplate, just ship.

Perfect for:
⚙️ **Rapid SaaS development**
🚀 **Hackathons & quick prototypes**
🤖 **Giving AI tools (Cursor / Copilot) a solid project foundation**

---

## 🎯 Key Features

✅ **One-Command Scaffolding** - Run `npx create-e2e-saas <project-name>` and you are done.  
✅ **JWT Authentication** - Secure, stateless, HTTP-only JWT session management.  
✅ **Email & OTP Verification** - Built-in flow for verifying users via Nodemailer & SMTP.  
✅ **Password Reset** - Fully implemented "Forgot Password" functionality.  
✅ **Modern UI/UX** - Pre-configured with **Tailwind CSS 4** and **Shadcn/UI**.  
✅ **Latest React Features** - Uses **React 19**, Vite, and **React Router 7**.  
✅ **Secure Backend** - Express API protected with Bcryptjs, Rate Limiting, and clean modular routes.  
✅ **Pre-Configured Scripts** - `npm run dev` handles both client and server effortlessly.

---

## 🏗 Architecture & Modules

When you run the CLI, it generates the following clean, scalable folder structure:

```
my-app/
├── client/           # Modern React Frontend
│   ├── src/
│   │   ├── components/  # Reusable Shadcn/UI components
│   │   ├── pages/       # Login, Register, Verify, Dashboard
│   │   ├── context/     # Global auth state
│   │   └── utils/       # API clients and helpers
│   └── package.json     # Vite, React 19, Tailwind 4
│
└── server/           # Node.js + Express Backend
    ├── controllers/  # Auth, User handlers
    ├── models/       # Mongoose User schemas
    ├── middleware/   # JWT verification, validators
    ├── routes/       # API endpoints
    └── package.json  # Express, Mongoose, Nodemailer
```

---

## 🚀 Quick Start

You can generate a new full-stack project instantly without installing anything globally:

### 1. Scaffold the Project
```bash
npx create-e2e-saas my-auth-app
```

### 2. Navigate to your project
```bash
cd my-auth-app
```

### 3. Install Dependencies
```bash
cd server && npm install
cd ../client && npm install
```

### 4. Configure Environment Variables
In the `server` directory, duplicate the `.env.example` to `.env` and fill in your database and SMTP details:
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_key
SMTP_USER=your_email@example.com
SMTP_PASS=your_email_password
```

### 5. Start Development
```bash
cd server && npm run dev
cd ../client && npm start
```

Your full MERN Auth app is now running locally! 🚀

---

## 🧠 Tech Stack

**Frontend Framework & UI:**
- React 19 + Vite
- Tailwind CSS 4
- Shadcn/UI + Lucide React
- React Router 7
- Recharts (for dashboards)

**Backend & Database:**
- Node.js + Express.js 4
- MongoDB + Mongoose

**Security & Auth:**
- JSON Web Tokens (JWT)
- Bcryptjs (Password Hashing)
- Nodemailer (SMTP for OTPs)

**CLI Tools:**
- Chalk (Terminal Styling)
- Ora (Terminal Spinners)

---

## 🤝 Contribute

Want to improve it? Contributions are open!
- 💅 Better UI / Dashboards
- 💳 Payment / Subscription Integration
- 🔑 Social Logins (Google, GitHub, etc.)
- 🎨 Tailwind / MUI themes

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request 🙌

---

## 🌍 Links

📦 **npm**: [npmjs.com/package/create-e2e-saas](https://www.npmjs.com/package/create-e2e-saas)  
💻 **GitHub**: [github.com/Sameer-Bagul/create-e2e-saas](https://github.com/Sameer-Bagul/create-e2e-saas)  
📫 **Contact**: [sameerbagul2004@gmail.com](mailto:sameerbagul2004@gmail.com)

---

## 🪪 License

MIT © 2026 [Sameer Bagul](mailto:sameerbagul2004@gmail.com)
