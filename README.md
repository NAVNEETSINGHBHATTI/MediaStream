# 🎬 MediaStream – Video Streaming Backend

A fully-featured and production-ready backend for a YouTube-like video hosting platform, built using Node.js, Express.js, MongoDB, and Mongoose with complete authentication, media upload, engagement system, and user interaction features.

---

## 🚀 Features

- ✔ Secure User Authentication & Authorization (JWT based)
- ✔ Login / Signup with password hashing using bcrypt
- ✔ Access Token + Refresh Token implementation
- ✔ Upload videos and thumbnails using Multer + Cloudinary
- ✔ Like / Dislike videos
- ✔ Comment & Tweet on videos
- ✔ Subscribe / Unsubscribe channels
- ✔ Playlist Management
- ✔ Track Watch History & Views Count
- ✔ Advanced data querying using MongoDB Aggregation Pipeline
- ✔ Proper modeling of User, Video, Comment, Like, Subscription
- ✔ All APIs tested in Postman
- ✔ Protected routes with middleware
- ✔ Clean and scalable MVC architecture
- ✔ Strong error handling and validations

---

## 🔧 Tech Stack

| Layer            | Technology                    |
| ---------------- | ----------------------------- |
| Runtime          | Node.js                       |
| Framework        | Express.js                    |
| Database         | MongoDB                       |
| ORM              | Mongoose                      |
| Authentication   | JWT (Access & Refresh Tokens) |
| Password Hashing | bcrypt                        |
| File Uploads     | Multer                        |
| Cloud Storage    | Cloudinary                    |
| Testing          | Postman                       |

---

## 🔌 API Details

All REST APIs are fully tested in Postman.

**Collection includes:**

- Auth APIs
- Video APIs
- Comment APIs
- Subscription APIs
- Playlist APIs
- Like APIs
- Tweet APIs

---

## 📥 **Getting Started**

To run the project locally, you will need **Node.js** and **Git** installed on your machine.

### 🧰 Installation and Setup Instructions

1. Clone the repository

    ```bash
    git clone https://github.com/NAVNEETSINGHBHATTI/MediaStream.git
    
    cd MediaStream

2. Install dependencies

    ```bash
    npm install

3. Add environment variables

    ```bash
    cp .env.example .env

4. Start development server
    ```bash
    npm run dev

**Environment variables example:**

```bash    
MONGODB_URI=your_mongodb_connection_string
CORS_ORIGIN=*
ACCESS_TOKEN_SECRET=your_access_secret
ACCESS_TOKEN_EXPIRY= your_access_expiry
REFRESH_TOKEN_SECRET=your_refresh_secret
REFRESH_TOKEN_EXPIRY= your_refresh_expiry
CLOUDINARY_CLOUD_NAME=xxxx
CLOUDINARY_API_KEY=xxxx
CLOUDINARY_API_SECRET=xxxx   
