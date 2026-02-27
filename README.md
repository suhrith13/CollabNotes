# CollabNotes — Real-time Collaborative Notes App

A recruiter-ready full-stack portfolio project demonstrating WebSockets, React, Node.js & MongoDB.

## 🚀 Deploy to GitHub Pages (Free) — Step by Step

### Step 1: Create a GitHub Repo
1. Go to github.com → New Repository
2. Name it `collab-notes`
3. Set it to **Public**
4. Click "Create repository"

### Step 2: Upload these files
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/collab-notes.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under "Source", select **Deploy from a branch**
3. Choose `main` branch → `/ (root)` folder
4. Click **Save**
5. Wait ~60 seconds → your site is live at:
   `https://YOUR_USERNAME.github.io/collab-notes/`

### Step 4 (Optional): Deploy Real Backend
For a real working backend with actual WebSockets:
- **Backend**: Deploy Node.js server to [Render.com](https://render.com) (free)
- **Database**: Create free cluster at [MongoDB Atlas](https://mongodb.com/atlas)
- **Update** the frontend's socket URL to point to your Render backend

---

## 📁 File Structure (This Portfolio Demo)
```
collab-notes/
├── index.html      ← Tech stack explainer + how it works
├── app.html        ← The interactive app demo
└── README.md       ← This file
```

## 🛠 Full Stack Architecture (Real Implementation)
```
frontend/           ← React + Tailwind + Quill.js
backend/
  ├── server.js     ← Express + Socket.IO
  ├── routes/
  │   ├── auth.js   ← JWT login/signup
  │   └── notes.js  ← CRUD API
  └── models/
      ├── User.js   ← Mongoose schema
      └── Note.js   ← Mongoose schema
```

## 💡 Resume Tip
Add to your resume:
> **CollabNotes** — Real-time collaborative notes app. Built with React, Node.js, Socket.IO & MongoDB. Live at [your-link] — open in two tabs to see real-time sync.
