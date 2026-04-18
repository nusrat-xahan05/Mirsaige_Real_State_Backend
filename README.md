# 🧩 Real Estate Blog Backend (Strapi)

## 📌 Project Overview

This is the backend service for the Real Estate Blog application, built using Strapi as a headless CMS. It provides RESTful APIs for managing blog posts, including creation, retrieval, and media handling. The backend is designed to be scalable, flexible, and easy to integrate with modern frontend frameworks.

---

## 🚀 Tech Stack

- Strapi (Headless CMS)
- Node.js
- PostgreSQL (Database)
- Cloudinary (Media Storage)
- Render (Deployment Platform)

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```
git clone "https://github.com/nusrat-xahan05/Mirsaige_Real_State_Backend"
cd Mirsaige_Real_State_Backend
```

### 2. Install dependencies

```
npm install
```

### 3. Create `.env`

```
DATABASE_CLIENT=postgres
DATABASE_URL=your_database_url
APP_KEYS=your_app_keys
API_TOKEN_SALT=your_api_token_salt
ADMIN_JWT_SECRET=your_admin_jwt_secret
JWT_SECRET=your_jwt_secret
```

- Credentials are not provided due to security purpose

### 4. Run development server

```
npm run develop
```

### 5. Build and start (production)

```
npm run build
npm run start
```

---

## 🌐 Live Links

- 🔗 Backend Live: https://mirsaige-real-state-backend.onrender.com
- 🔗 Frontend Live: https://mirsaige-real-state-frontend.vercel.app
- 🔗 Frontend Repo: https://github.com/nusrat-xahan05/Mirsaige_Real_State_Frontend

---

## ✨ Features Implemented

- **Content Management (Posts)**  
  Create, read, and manage blog posts via Strapi dashboard and API.

- **REST API Endpoints**  
  Auto-generated endpoints for fetching all posts and individual posts using filters (e.g., slug).

- **Image Upload Support**  
  Integrated media upload with Cloudinary for persistent storage.

- **Role-Based Permissions**  
  Configured public access for reading content and creating posts.

- **Deployment Ready**  
  Configured environment variables and database connection for production deployment on Render.

---

## 📌 Notes

This backend is designed to work seamlessly with a Next.js frontend and demonstrates a modern headless CMS architecture.
