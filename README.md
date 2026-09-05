# Musify Backend

Backend API for **Musify**, a music streaming web application that allows users to discover, upload, like, save songs for later, create playlists, and share music.

## 🌐 Live Demo

https://musifybaonguyxn.vercel.app/

The Musify application is deployed using **Vercel** for the frontend and **Render** for the backend.

### Deployment

- **Frontend:** Vercel
- **Backend:** Render
- **Database:** MongoDB Atlas
- **Media Storage:** Cloudinary

---

## 🚀 Features

- 🔐 User authentication with JWT
- 👤 User registration and login
- 🎵 Upload and manage songs
- 🖼️ Upload song thumbnails
- ☁️ Store media files using Cloudinary
- ❤️ Like / unlike songs
- ⏰ Add songs to Listen Later
- 📂 Create and manage playlists
- 🔎 Search songs
- 👨‍🎤 Artist / user profiles
- 🔗 Share songs and playlists
- 📄 Pagination for song lists
- 🗄️ MongoDB database
- 🛡️ Authentication middleware for protected APIs

---

## 🛠️ Technologies

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- Multer
- Cloudinary
- dotenv
- CORS

### Frontend

The backend is designed to work with the Musify React frontend.

- React
- React Router
- Axios
- Tailwind CSS

---

## 📁 Project Structure

```text
Sbortify-backend/
│
├── public/
│   └── temp/
│
├── src/
│   ├── controllers/
│   ├── db/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── index.js
│
├── .env
├── .gitignore
├── package.json
└── README.md
```
