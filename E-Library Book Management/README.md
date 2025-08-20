📚 E-Library Book Management (Python)
A simple E-Library Book Management System implemented in Python.
This project demonstrates how to borrow, return, search, and undo actions using linked lists and stacks.

📌 Overview
The E-Library system maintains an inventory of books stored in a linked list.
Users can borrow and return books, and each action is recorded in a stack to support undo functionality.
Books can also be searched or filtered by title or author.

✨ Features
➕ Add Books – Insert new books into the library inventory.
📖 Display Books – View all books with their availability status.
📕 Borrow Books – Borrow a book if it is available.
📗 Return Books – Return a borrowed book.
↩️ Undo Last Action – Undo the last borrow/return action using a stack.
🔍 Search/Filter – Search books by title or author.
🛠 Data Structures Used
Linked List (Self-referential Structure)

Each book is stored as a node (BookNode) with:
title
author
available (availability status)
next (pointer to next book node)
Stack (Python list)

Used for undo functionality.
Stores recent borrow/return actions and allows reverting them.
▶️ How It Runs
Clone this repository:
git clone https://github.com/your-username/elibrary-book-management.git
cd elibrary-book-management
