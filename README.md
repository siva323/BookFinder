# BookFinder
Created with CodeSandbox
Book Finder

Book Finder is a simple React application that lets you search for books by title using the Open Library API.
You can view details like book cover, title, author(s), and first published year.

🚀 Live Demo

👉 Click here to view on CodeSandbox

👉 CodeSandbox Source

🛠️ Features

🔍 Search books by title

📖 Displays book covers, authors, and publish year

⚡ Fast results using Open Library API

🎨 Clean responsive UI (custom CSS)

🛡️ Handles errors (no results, network issues)

📦 Tech Stack

React 19 (frontend framework)

CSS (custom styling)

Open Library API for book data

⚙️ Installation (Run Locally)

Clone or download the repository / ZIP file

Install dependencies:

npm install


Start development server:

npm start


Open http://localhost:3000
 in your browser 🚀

📂 Project Structure
src/
 ├── App.js       # Main React component
 ├── styles.css   # Custom CSS styles
 ├── index.js     # React entry point
public/
 └── index.html   # Base HTML file

🔗 API Reference

Open Library Search API

GET https://openlibrary.org/search.json?title={bookTitle}


Example:

https://openlibrary.org/search.json?title=harry+potter
