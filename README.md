# MERN Stack Bookstore App

This is a full-stack web application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to manage a collection of books with CRUD (Create, Read, Update, Delete) operations.

## Features

- Add new books to the collection
- View a list of all books in the collection
- Update existing book details
- Delete books from the collection
- Search for books by id

## Technologies Used

- MongoDB: Database for storing book data
- Express.js: Backend framework for handling HTTP requests
- React.js: Frontend library for building user interfaces
- Node.js: JavaScript runtime environment for running server-side code
- Axios: HTTP client for making API requests
- Tailwind CSS: Frontend framework for responsive design

## Getting Started

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. cd backend and cd frontend. Install dependencies for both the frontent and backend by `npm install`:
4. Set up your MongoDB database and configure the connection string in `backend/config.js`.
5. Create .env file and write `MONGODB__PASSWORD = YOURPASSWORDHERE`.
6. Start the backend and frontend development servers by `npm run dev` for both:
7. Open your web browser and navigate to `http://localhost:5173` to view the app.

## API Endpoints

- GET /books: Retrieve all books
- GET /books/:id: Retrieve a specific book by ID
- POST /books: Add a new book to the collection
- PUT /books/:id: Update an existing book by ID
- DELETE /books/:id: Delete a book from the collection by ID

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have suggestions for improvements.
