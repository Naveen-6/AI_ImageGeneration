
# 🧠 AI Image Generator with DALL·E

![License](https://img.shields.io/badge/license-MIT-green.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
![Deploy on Vercel](https://vercel.com/button)
![Deploy on Render](https://img.shields.io/badge/Backend-Render-blue)

A full-stack MERN application that allows users to generate images using OpenAI's DALL·E API, share them with the community, and download their creations. Built with modern tools like React, Node.js, Express, MongoDB, and Tailwind CSS.

---
## 🌐 Live Demo

- **Frontend:** https://ai-image-generation-frontend-rho.vercel.app/
- **Backend:** https://ai-imagegeneration-backend.onrender.com/
- 

## 🌐 Live Demo

[![Frontend](https://img.shields.io/badge/Frontend-Live-green?style=for-the-badge)](https://ai-image-generation-frontend-rho.vercel.app/)
[![Backend](https://img.shields.io/badge/Backend-API-blue?style=for-the-badge)](https://ai-imagegeneration-backend.onrender.com/)

---


## 🚀 Features

- 🔥 Generate high-quality images using the OpenAI DALL·E API
- 📤 Share your creations with a global community
- 📥 Download images securely
- 🧠 Surprise Me feature for random prompts
- 📱 Mobile responsive design
- ☁️ Cloudinary integration for media hosting
- ⚙️ Fully deployed with Vercel (frontend) and Render (backend)
- 🔍 Search posts by name or prompt

---

## 🛠 Tech Stack

**Frontend:**
- React
- Vite
- Tailwind CSS

**Backend:**
- Node.js
- Express.js
- MongoDB (Atlas)
- OpenAI API (DALL·E)
- Cloudinary (Image Hosting)

---

## 📦 Installation

### 📁 Clone the Project

```bash
git clone https://github.com/Naveen-6/AI_ImageGeneration.git
cd ImageGeneration-AI
```

### 🔧 Backend Setup

```bash
cd BackEnd
npm install
```

Create a `.env` file and add:

```env
MONGODB_URL=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Start the server:

```bash
npm start
```

---

### 💻 Frontend Setup

```bash
cd FrontEnd
npm install
npm run dev
```

---

## 🚀 Deployment

### Deploy Backend on Render

1. Go to [https://render.com](https://render.com)
2. Create a new Web Service
3. Connect your GitHub repository
4. Set build command: `npm install`
5. Set start command: `npm run dev` or `node index.js`
6. Add environment variables from your `.env` file

### Deploy Frontend on Vercel

1. Go to [https://vercel.com](https://vercel.com)
2. Import your GitHub repo
3. In "Project Settings", add the backend URL to `.env` as:

```env
VITE_BACKEND_URL=https://your-render-backend-url.com
```

4. Deploy!

---

## ✅ To-Do / Improvements

- Add user authentication
- Create a like/comment system for posts
- Multi-image generation support

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---



## 👨‍💻 Author

**Naveen Sai**  


