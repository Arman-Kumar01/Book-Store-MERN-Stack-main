# Book Store MERN Stack

A full-stack web application for managing a book store, built with the MERN stack (MongoDB, Express.js, React, Node.js).

## Features

- **CRUD Operations**: Create, read, update, and delete books.
- **Responsive UI**: Built with React, Vite, and Tailwind CSS for a modern, mobile-friendly interface.
- **Backend API**: RESTful API with Express.js and MongoDB for data persistence.
- **User Experience**: Includes loading spinners, notifications, and modal dialogs.

## Tech Stack

- **Frontend**: React, Vite, Tailwind CSS, Axios
- **Backend**: Node.js, Express.js, MongoDB, Mongoose
- **Other**: CORS for cross-origin requests

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/book-store-mern-stack.git
   cd book-store-mern-stack
   ```

2. **Install backend dependencies**:
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies**:
   ```bash
   cd ../frontend
   npm install
   ```

4. **Set up MongoDB**: Ensure MongoDB is running locally or update the connection string in `backend/config.js`.

5. **Start the backend**:
   ```bash
   cd backend
   npm run dev
   ```

6. **Start the frontend** (in a new terminal):
   ```bash
   cd frontend
   npm run dev
   ```

7. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Usage

- Navigate to the home page to view all books in table or card format.
- Use the "Add Book" button to create new books.
- Click on a book to view details, edit, or delete it.

## Project Structure

- `backend/`: Express.js server, models, routes, and database config.
- `frontend/`: React application with components and pages.

## License

ISC