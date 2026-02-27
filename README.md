# CollabNotes — Real-time Collaborative Notes App

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
