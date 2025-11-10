# 💬 Fullstack Chat App – Backend

This is the **backend** of the [Fullstack Chat App](https://github.com/vishnuboligili/chat-app), built using **Node.js**, **Express**, **MongoDB**,**Socket.IO**, and **Cloudinary**.  
It powers user authentication, media uploads, and secure communication for the chat frontend.

---

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/vishnuboligili/chat-app.git

```

### 2.  Go to backend folder and install dependencies
```bash
cd chat-app/backend
npm install
```
### 3.  Go to frontend  folder and install dependencies
```bash
cd ../frontend
npm install
```


### 4. Create a `.env` File
In the `backend` folder, create a file named `.env` and add the following environment variables:

```env
MONGODB_URI=mongodb+srv://vishnuboligili:vishnu123@cluster0.fu4g9x1.mongodb.net/
PORT=5001
JWT_SECRET=your_jwt_secret_here

CLOUDINARY_CLOUD_NAME=ditqhvlgla
CLOUDINARY_API_KEY=543156598537357
CLOUDINARY_API_SECRET=RQYhI5JrC0Rp3OW5CNiNevHY-Ko

NODE_ENV=development
```

## Run the Server

### Development Mode
```bash
npm run dev
```

### Production Mode
```bash
npm start
```

Once the server starts, visit:
```
http://localhost:5001/
```

If you see:
```
✅ Backend server is running successfully!
```
then your backend is working properly.


## 👥 Sample Users

| Role | Email | Password |
|------|--------|-----------|
| Admin | vishnuboligili@gmail.com | 12345678 |
| User  | harsha@gmail.com  | 12345678 |

*(You can use these credentials if seeded or register new users manually.)*

---

## 🧩 Tech Stack

- **Node.js** – Backend runtime  
- **Express.js** – Web framework  
- **MongoDB Atlas** – Database  
- **Mongoose** – ODM for MongoDB  
- **JWT Authentication** – Secure user sessions  
- **Cloudinary** – Image & media storage  
- **Socket.IO** – Real-time messaging and Live chat features.

---
