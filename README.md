# Library management v1

A simple Node.js and Express app to manage books, with features to add, issue, return, and delete books. Uses **EJS** for dynamic views.

---

## Features
- View the list of books.
- Add a new book.
- Mark books as "Issued" or "Available."
- Delete books from the collection.

---

## Usage
1. Run the app using `node app.js`.
2. Open your browser and navigate to `http://localhost:3000`.

---

## Installation
     
```bash
npm install 
```

---

## Routes
- **GET `/`**: View all books.
- **POST `/`**: Add a book.
- **POST `/issue`**: Issue a book.
- **POST `/return`**: Return a book.
- **POST `/delete`**: Delete a book.

---

## Dependencies
- **Express**
- **Body-parser**
- **EJS**
     ```bash
     npm install express body-parser ejs
     ```

---
     
     

