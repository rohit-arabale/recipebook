# 🍽️ recipebook

recipebook is a full-stack MERN application that allows users to create, share, discover, save, and discuss recipes. Users can manage their own recipes, interact with recipes from other users, and maintain a personalized collection of saved recipes.

---

## ✨ Features

### Authentication & User Management

* User Registration
* User Login & Logout
* JWT Authentication
* Protected Routes
* User Profile Management

### Recipe Management

* Create Recipes
* Edit Recipes
* Delete Recipes
* Public / Private Recipe Visibility
* View Individual Recipe Details

### Social Features

* Comment on Recipes
* Delete Own Comments
* Save Favorite Recipes
* View Saved Recipes
* Public User Profiles

### Modern Frontend

* React 18
* React Router
* React Query
* Axios
* Tailwind CSS
* Framer Motion
* Vite

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* bcrypt Password Hashing

---

## 🛠️ Tech Stack

### Frontend

* React
* Vite
* React Router DOM
* React Query
* Axios
* Tailwind CSS
* Framer Motion

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* bcryptjs

---

## 📁 Project Structure

```text
recipebook-main/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── seed.js
│
└── frontend/
    ├── src/
    │   ├── components/
    │   ├── context/
    │   ├── pages/
    │   ├── utils/
    │   └── App.jsx
    │
    └── vite.config.js
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/recipebook.git
cd recipebook
```

---

### 2. Backend Setup

Navigate to backend:

```bash
cd backend
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/recipebook
JWT_SECRET=your_secret_key
```

Start the backend server:

```bash
npm run dev
```

or

```bash
npm start
```

---

### 3. Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install
npm run dev
```

Frontend will run on:

```text
http://localhost:5173
```

Backend will run on:

```text
http://localhost:5000
```

---

## 🌱 Seed Sample Data

To populate the database with sample recipes:

```bash
cd backend
node seed.js
```

---

## 🔑 Environment Variables

### Backend

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/recipebook
JWT_SECRET=your_secret_key
```

### Frontend

```env
VITE_API_BASE_URL=http://localhost:5000/api
```

---

## 📡 API Endpoints

### Authentication

| Method | Endpoint           |
| ------ | ------------------ |
| POST   | /api/auth/register |
| POST   | /api/auth/login    |
| POST   | /api/auth/logout   |
| GET    | /api/auth/me       |
| PUT    | /api/auth/me       |

### Recipes

| Method | Endpoint                    |
| ------ | --------------------------- |
| GET    | /api/recipes                |
| GET    | /api/recipes/:id            |
| POST   | /api/recipes                |
| PUT    | /api/recipes/:id            |
| DELETE | /api/recipes/:id            |
| PATCH  | /api/recipes/:id/visibility |

### Comments

| Method | Endpoint                             |
| ------ | ------------------------------------ |
| POST   | /api/recipes/:id/comments            |
| DELETE | /api/recipes/:id/comments/:commentId |

### Saved Recipes

| Method | Endpoint                 |
| ------ | ------------------------ |
| POST   | /api/recipes/:id/save    |
| DELETE | /api/recipes/:id/save    |
| GET    | /api/recipes/users/saved |

---

## 🚀 Future Enhancements

* Recipe Image Uploads
* Recipe Categories
* Search & Filters
* Like System
* Recipe Ratings
* Follow Users
* Notifications
* Admin Dashboard
* Cloud Storage Integration
* Deployment Support

---

## 🧪 Learning Objectives

This project demonstrates:

* Full-Stack MERN Development
* Authentication with JWT
* REST API Design
* MongoDB Relationships
* React State Management
* Protected Routes
* CRUD Operations
* Modern UI Development

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed by Rohit Arabale.

Feel free to fork, improve, and contribute.
