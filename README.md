# 🌐 Intern-Portal

A **Full Stack Job Portal Application** built with ReactJS, Express, NodeJS, and MongoDB.  
This platform connects **applicants** with **companies**, offering features like job postings, applications, and authentication.

---

## 📌 Features

### 👨‍💼 For Applicants
- Browse and search job postings
- Filter jobs by category
- View detailed job descriptions
- Apply to jobs and track application status

### 🏢 For Companies
- Create and manage company profiles
- Post new job openings
- View and manage applications

### 🔒 Authentication
- Secure user login and registration
- Session handling using JWT (JSON Web Tokens)
-----
### Images
![Image 1](https://github.com/user-attachments/assets/7cce39f9-5ffb-4f74-ad32-ab4f2f2dd1b7)
![Image 2](https://github.com/user-attachments/assets/051b6cef-fb4b-4746-8a34-b45427205e3a)
![Image 3](https://github.com/user-attachments/assets/9857bf74-8be8-4950-8e6a-5141d91ece43)
<img width="1919" height="767" alt="Image 4" src="https://github.com/user-attachments/assets/4408c82e-d964-4302-afaa-94414b44cc55" />
<img width="1358" height="453" alt="Image 5" src="https://github.com/user-attachments/assets/f0cb9295-ffd4-4395-b363-64c3ced29e82" />

---

## 🛠 Tech Stack

### ⚡ Frontend
- [React](https://react.dev/) (with [Vite](https://vitejs.dev/) bundler)
- [Tailwind CSS](https://tailwindcss.com/)
- [Axios](https://axios-http.com/) for API requests

### ⚙️ Backend
- [Node.js](https://nodejs.org/) & [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/) with [Mongoose](https://mongoosejs.com/) ODM
- [Cloudinary](https://cloudinary.com/) for media uploads

---
## 📂 Project Structure
jobportal/
│
├── backend/ # Express.js backend
│ ├── controllers/ # Business logic
│ ├── models/ # MongoDB models
│ ├── routes/ # API endpoints
│ ├── middlewares/ # Authentication & file handling
│ ├── utils/ # Helper functions (DB, Cloudinary)
│ ├── package.json # Backend dependencies
│ └── index.js # Server entry point
│
└── frontend/ # React frontend
├── src/
│ ├── components/ # UI components
│ └── assets/ # Images and static files
├── package.json # Frontend dependencies
└── vite.config.js # Vite configuration

## 🔧 Prerequisites

Before running the project, ensure you have:

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [MongoDB](https://www.mongodb.com/) (local or Atlas cluster)
- [Cloudinary](https://cloudinary.com/) account (for file uploads)


