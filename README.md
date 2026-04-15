# Simple Library Management System

My 7th Project. A simple and lightweight Library Management System built with Python. This project serves as an introduction to Object-Oriented Programming (OOP) concepts, modeling real-world interactions between books and a library.

## 💡 Description
This project focuses on the foundational mechanics of OOP. It utilizes two main classes:
- `Book`: Represents individual books with attributes like title, author, and availability status.
- `Library`: Acts as a container to manage a collection of `Book` objects, allowing users to add books, display the catalog, and search for specific titles.

## 🚀 Features
- **Add Books:** Add new book instances to the library's catalog.
- **Search Catalog:** Find specific books by their title.
- **Borrow/Return Mechanism:** Check out books (changes availability to `False`) and return them (changes availability to `True`).
- **Display Inventory:** Print out the details of all books currently held in the library.

## 🧠 What I Learned
Through building this project, I strengthened my understanding of core Python and OOP concepts:
- **Classes and Objects:** Creating blueprints (`class`) and instantiating unique objects from them.
- **The `__init__` Method:** Initializing object attributes upon creation.
- **Class Interactions:** Managing objects of one class (`Book`) inside another class (`Library`) using lists.
- **State Management:** Tracking and updating the internal state of objects (e.g., toggling the `available` boolean).
- **Methods:** Defining functions inside classes to perform specific actions on the object's data.

## 🔮 Future Improvements
While the current version is a solid foundational model, here are some features planned for future iterations:
- **Interactive Command Line Interface (CLI):** Allow users to input commands directly in the terminal to add, borrow, or return books dynamically.
- **Input Validation:** Prevent duplicate books from being added and handle searches for non-existent books gracefully.
- **Data Persistence:** Integrate file handling (e.g., JSON or CSV) so the library's inventory is saved and loaded every time the program runs.
- **Advanced Searching:** Add the ability to search by author or filter by availability.

## 💻 Usage
To run this project, simply execute the script in your Python environment:
```bash
python main.py
