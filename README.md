# Library Project

## Overview

The Library Project is a straightforward Web application that's written in HTML, CSS, and JavaScript. It enables users to access a personal book library to add books to their collection, view book details, and track reading progress.

This project is an Odin Project JavaScript project. It is mainly to perform practice with DOM manipulation, event handling, arrays, constructors and objects on JavaScript.

## Features

You can add books using a form contained in a dialog.
- Show books dynamically as cards on the page.
- Save book information such as title, author, number of pages read and the total pages in a book.
Use crypto.randomUUID() to create a unique ID for each book.
- Take books out of library.
Record the status of a book – either read or unread.
- Clear the form when adding a new book.

## Technologies Used

- CSS – Defines how the application is presented.- JavaScript – Controls the application.
- CSS3 – Manages style, layout and responsiveness.
- JavaScript – Handles book data, user interaction and dynamic rendering.

## Project Structure

```text
Library/
├── index.html
├── style.css
├── script.js
└── README.md
```

## How It Works

The books are stored in an array of JavaScript named myLibrary. Every book is constructed with a constructor of the Book class that takes its title, author, number of pages, reading status, and a unique ID.

The function `addBookToLibrary()` is used to make new book objects and append them to the array. The `displayBooks()` function displays the books using dom manipulation.

The user can manage their collection through the form and buttons and interact with the application.

## What I Learned

In this project, I did the following:

- Using constructor functions to create objects.
- Array and Object Properties.
Use of unique IDs with the crypto.randomUUID() function.
Working with DOM using JavaScript.
- Performing click and submit actions.
- Using HTML forms and dialog boxes.
- Decoupling application data from its visuals.
A11y: Connect dom elements with java script objects using the data attributes.

## Getting Started

1. Clone this repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Unzip the project folder.

3. View index.html in your browser.

Click Add New Book to begin adding books to your library.

## Future Improvements

Use localStorage to store books, so that the collection isn't lost when the page is refreshed.
- Improve the interface with additional book management features.
- Add search and filtering functionality.

## Acknowledgements

This project was accomplished in the context of The Odin Project curriculum.

https://www.theodinproject.com/
