# 🚀 QuickAI

**QuickAI** is a full-stack AI-powered content creation platform built with the **PERN stack** and authenticated via **Clerk**. It allows users to generate, enhance, and optimize content using cutting-edge AI tools.

![QuickAI Banner](https://via.placeholder.com/1200x400?text=QuickAI+Platform+Banner)

## 🌐 Live Demo

**Local Dev**: `http://localhost:5173`  
> Production URL will be added soon.

---

## ✨ Features

- 🔐 **Clerk Authentication** – Seamless login/signup with secure session management
- 🧠 **AI Tools**:
  - ✍️ AI Article Writer
  - 📰 Blog Title Generator
  - 🖼️ AI Image Generator
  - ✂️ Background & Object Removal
  - 📄 Resume Reviewer
- 💾 **PostgreSQL Database** – Robust, scalable data storage
- ⚙️ **Express.js Backend** – Fast API endpoints
- ⚛️ **React Frontend** – Responsive, interactive UI with Vite

---

## 🛠️ Tech Stack

| Layer        | Tech Used               |
|--------------|--------------------------|
| Frontend     | React.js, Vite, TailwindCSS |
| Backend      | Node.js, Express.js      |
| Database     | PostgreSQL (via Prisma or pg) |
| Auth         | Clerk                    |
| Hosting/CI   | (Optional: Vercel/Render/Heroku) |

---

## 📁 Project Structure

```QuickAI/
├── client/ # React frontend (Vite + TailwindCSS)
│ ├── public/ # Static assets
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Page-level components/routes
│ │ ├── assets/ # Images, icons, styles
│ │ └── App.jsx # Root component
│ └── vite.config.js # Vite config
│
├── server/ # Backend (Node.js + Express)
│ ├── controllers/ # Route logic
│ ├── routes/ # API endpoints
│ ├── models/ # DB schemas
│ └── index.js # Server entry point
│
├── prisma/ # Prisma ORM (if used)
│ ├── schema.prisma
│ └── migrations/
│
├── .env # Environment variables
├── README.md # Project overview
└── package.json # Project metadata & scripts
```

---

## Set Up the Backend

-cd server
-npm install
-npm run dev

## Set Up the Frontend

-cd ../client
-npm install
-npm run dev


## Authentication via Clerk--

-Create a Clerk account
-Get your Clerk frontend & backend keys
-Add them to .env files in both /client and /server

---

## 📦 Environment Variables--

Create .env files in both /client and /server directories.

### /client/.env-

VITE_CLERK_PUBLISHABLE_KEY=your_publishable_key

### /server/.env-

CLERK_SECRET_KEY=your_clerk_secret_key
DATABASE_URL=postgres://username:password@localhost:5432/quickai

---

## 🤝 Contribution

Contributions are welcome!
Please open issues and submit pull requests for improvements.

---

## 🙋‍♂️ Author
Aman Kumar – GitHub