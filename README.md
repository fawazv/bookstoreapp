# 📚 MERN Stack Bookstore App

[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)](https://react.dev/)  
[![Node.js](https://img.shields.io/badge/Node.js-18-339933?logo=node.js)](https://nodejs.org/)  
[![Express.js](https://img.shields.io/badge/Express.js-4-black?logo=express)](https://expressjs.com/)  
[![MongoDB](https://img.shields.io/badge/MongoDB-8-47A248?logo=mongodb)](https://www.mongodb.com/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

---

A full-stack **Bookstore application** built with the **MERN (MongoDB, Express.js, React.js, Node.js)** stack.  
This app allows users to manage a collection of books with complete **CRUD (Create, Read, Update, Delete)** functionality.  

---

## 🚀 Features

- ➕ Add new books to the collection  
- 📖 View all books in the collection  
- ✏️ Update existing book details  
- ❌ Delete books from the collection  
- 🔍 Search for books by ID  

---

## 🛠 Technologies Used

**Frontend (client):**  
- React.js  
- Vite  
- Axios  
- React Router DOM  
- Bootstrap  
- React Icons  
- Tailwind CSS  

**Backend (server):**  
- Node.js  
- Express.js  
- MongoDB with Mongoose  
- CORS  
- Dotenv  

---

## 📦 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/mern-bookstore.git
   cd mern-bookstore
   ```

2. **Install dependencies**  

   For backend:  
   ```bash
   cd backend
   npm install
   ```

   For frontend:  
   ```bash
   cd client
   npm install
   ```

3. **Set up environment variables**  
   In the **backend**, create a `.env` file and add:  

   ```env
   MONGODB_PASSWORD=your_password_here
   ```

   Update your MongoDB connection string in `backend/config.js`.  

4. **Run the development servers**  

   Start the backend:  
   ```bash
   cd backend
   npm run dev
   ```

   Start the frontend:  
   ```bash
   cd client
   npm run dev
   ```

5. Open [http://localhost:5173](http://localhost:5173) in your browser.  

---

## 🌐 API Endpoints

- `GET /books` → Retrieve all books  
- `GET /books/:id` → Retrieve a book by ID  
- `POST /books` → Add a new book  
- `PUT /books/:id` → Update an existing book  
- `DELETE /books/:id` → Delete a book  

---

## 📂 Project Structure

```
mern-bookstore/
├── backend/              # Express.js backend
│   ├── index.js          # Entry point
│   ├── models/           # Mongoose models
│   ├── routes/           # API routes
│   └── .env              # Environment variables
│
├── client/               # React frontend (Vite)
│   ├── src/              # React components & pages
│   ├── public/           # Static assets
│   └── vite.config.js    # Vite configuration
│
├── package.json
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome! 🎉  
Feel free to submit a pull request or open an issue if you find bugs or have suggestions.  

---

## 📜 License

This project is licensed under the **MIT License**.  

---

## 🙌 Acknowledgements

- [MongoDB](https://www.mongodb.com/)  
- [Express.js](https://expressjs.com/)  
- [React.js](https://react.dev/)  
- [Node.js](https://nodejs.org/)  
