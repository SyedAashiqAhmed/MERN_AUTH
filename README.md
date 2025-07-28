# MERN Login/Register App

## 📽️ Demo Video
## 📽️ Demo Video

[▶️ Click here to watch the demo video](https://drive.google.com/file/d/1j8fPl8uYG5caT8UZa2tQLFcnAYmEW6B5/view)



A full-stack authentication app using MongoDB, Express, React, and Node.js.

## Features
- User registration and login
- JWT authentication
- MongoDB Atlas database
- React frontend with Vite

---

## Prerequisites
- Node.js (v14+ recommended)
- npm
- MongoDB Atlas account

---

## Getting Started

### 1. Clone the repository
```sh
git clone https://github.com/your-username/mern-login-register-main.git
cd mern-login-register-main
```

### 2. Backend Setup
```sh
cd backend
npm install
```

#### Create a `.env` file in the `backend` folder:
```
PORT=5000
JWT_SECRET=your_jwt_secret
MONGO_URI=your_mongodb_connection_string
```

#### Start the backend server:
```sh
npm start
# or
node server.js
```

---

### 3. Frontend Setup
```sh
cd ../frontend
npm install
npm run dev
```

The frontend will run on [http://localhost:5173](http://localhost:5173) by default.

---

## Folder Structure
```
mern-login-register-main/
  backend/      # Express API & MongoDB models
  frontend/     # React app (Vite)
```

---

## API Endpoints
- `POST /api/users/register` — Register a new user
- `POST /api/users/login` — Login
- `GET /api/users/me` — Get current user (requires JWT)

---

## License
MIT 
