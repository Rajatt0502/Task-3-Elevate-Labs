# Task-3-Elevate-Labs
Book API

A simple RESTful API built with Node.js and Express to manage a list of books stored in memory. This API demonstrates basic CRUD operations without using a database.

Features

GET /books – Retrieve all books

POST /books – Add a new book

PUT /books/:id – Update a book by ID

DELETE /books/:id – Delete a book by ID

Installation

Clone the repository or create a project folder.

Navigate to the folder in terminal and run:

npm init -y
npm install express


Create a file server.js and add the API code.

Running the Server
node server.js

The server runs at http://localhost:3000.
Testing

Use Postman or curl to test API endpoints.


<img width="1919" height="1020" alt="Screenshot 2025-09-25 212653" src="https://github.com/user-attachments/assets/187caa40-d5e8-4a83-ba1e-1146d998e6c0" />


<img width="1919" height="1019" alt="Screenshot 2025-09-25 212707" src="https://github.com/user-attachments/assets/0221b146-5083-4c24-a868-b14bb987d5a6" />

For Post: http://localhost:3000/books

<img width="1914" height="1026" alt="Screenshot 2025-09-25 212316" src="https://github.com/user-attachments/assets/70243df7-ad9a-43ff-9e6b-e9734acaaf02" />


For update: http://localhost:3000/books/1

<img width="1919" height="1020" alt="Screenshot 2025-09-25 212324" src="https://github.com/user-attachments/assets/3023511b-c57a-40d7-984a-7894c4016f78" />


For delete: http://localhost:3000/books/2

<img width="1919" height="1018" alt="Screenshot 2025-09-25 212330" src="https://github.com/user-attachments/assets/5331da9f-72c4-4eff-b399-77febd276a64" />




