# 🍳 RecipeBook

A modern full-stack MERN application for creating, sharing, discovering, and saving recipes.

RecipeBook allows food enthusiasts to publish recipes, interact with other users, save favorite dishes, and manage their personal recipe collection through a clean and responsive interface.

---

## ✨ Features

### 🔐 Authentication

* User Registration
* User Login & Logout
* JWT Authentication
* Protected Routes

### 🍽️ Recipe Management

* Create Recipes
* Edit Recipes
* Delete Recipes
* Public & Private Recipe Visibility
* View Detailed Recipe Information

### ❤️ User Interaction

* Save Favorite Recipes
* View Saved Recipes
* Comment on Recipes
* Delete Own Comments

### 👤 User Profiles

* View Public Profiles
* Browse User Recipes
* Manage Personal Content

### 🎨 Modern UI

* Responsive Design
* Tailwind CSS Styling
* Smooth Animations with Framer Motion
* Fast Performance with Vite

---

## 🛠️ Tech Stack

### Frontend

* React.js
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
* JWT Authentication
* bcryptjs

---

## 📂 Project Structure

```text
recipebook/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── utils/
│   │   └── App.jsx
│   │
│   └── vite.config.js
│
├── README.md
└── .gitignore
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/rohit-arabale/recipebook.git
cd recipebook
```

### Backend Setup

```bash
cd backend
npm install
```

Create `.env`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run backend:

```bash
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Application:

```text
Frontend: http://localhost:5173
Backend : http://localhost:5000
```

---

## 🔑 Environment Variables

### Backend

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Frontend

```env
VITE_API_BASE_URL=http://localhost:5000/api
```

---

## 📡 API Features

### Authentication

* Register User
* Login User
* Logout User
* Get Current User

### Recipes

* Create Recipe
* Read Recipes
* Update Recipe
* Delete Recipe
* Toggle Visibility

### Comments

* Add Comment
* Delete Comment

### Favorites

* Save Recipe
* Remove Saved Recipe
* View Saved Recipes

---

## 🌟 Future Improvements

* Recipe Image Uploads
* Categories & Tags
* Advanced Search & Filters
* Recipe Ratings
* Like System
* Follow Users
* Notifications
* Admin Dashboard
* Cloud Storage Integration

---

## 🎯 Learning Outcomes

This project demonstrates:

* Full-Stack MERN Development
* REST API Design
* Authentication & Authorization
* MongoDB Data Modeling
* CRUD Operations
* State Management
* Responsive UI Development
* Modern Frontend Architecture

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Rohit Arabale

Built with React, Node.js, Express, MongoDB, and Tailwind CSS.
