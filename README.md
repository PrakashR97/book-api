# book-api
![image](https://user-images.githubusercontent.com/67256980/229653006-4ba7d38f-e0b6-4048-a680-a993f3d7c9f6.png)
![image](https://user-images.githubusercontent.com/67256980/229653040-c8e32de2-3caa-4759-9c01-bfd0685b4cff.png)
![image](https://user-images.githubusercontent.com/67256980/229653106-3ed30baa-490a-4dd2-93fb-91e3f9a96884.png)
![image](https://user-images.githubusercontent.com/67256980/229653139-5c5f990f-34df-40b7-97a6-4a35d25228c9.png)




📝 Table of Contents

About
Getting Started
Usage
API Endpoints
TODO
Contributing
Authors
Acknowledgments

🧐 About
This is a React-based book application that fetches book data from a JSON server API. The application allows users to perform CRUD (Create, Read, Update, Delete) operations on books. Users can view a list of books, add a new book, edit an existing book, and delete a book from the list.


🏁 Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites

Node.js
NPM
JSON server
Installing

Clone the repository
Install NPM packages
npm install
Start the JSON server
json-server --watch db.json --port 3004
Start the application
npm start
Open the application in a browser at http://localhost:3000
<!-- Usage -->
🎈 Usage
To use the application, simply navigate to the home page to view the list of books. Users can add a new book by clicking the "Add Book" button and filling out the form. To edit an existing book, click the "Edit" button next to the book you want to modify and update the form. To delete a book, click the "Delete" button next to the book you want to remove.


📡 API Endpoints

GET /books - Returns a list of all books in the database
GET /books/:id - Returns a specific book with the given ID
POST /books - Adds a new book to the database
PUT /books/:id - Updates a specific book with the given ID
DELETE /books/:id - Deletes a specific book with the given ID


TODO

Add support for search and filter functionality to find specific books
Implement client-side form validation for adding and editing books
Improve the user interface with better styling and layout
<!-- Contributing -->
🤝 Contributing
Contributions are welcome! Please feel free to submit a pull request.


👨‍💻 Authors
Prakash R

🙏 Acknowledgments
This project was built using React and JSON server. We would like to acknowledge the developers of these technologies and the community that supports them.
