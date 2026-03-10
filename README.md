# 📚 Library Management System using DSA

## About This Project
This is a simple console-based Python project built for my Data Structures and Algorithms (DSA). Instead of using a database, this system uses core data structures to manage books, track waiting lists, and handle book returns in a library.

It is a great beginner project to understand how pointers, nodes, and LIFO/FIFO concepts work in real life!

## Data Structures Used
* **Singly Linked List:** Used as the main inventory to store all the books. It allows the library to add as many books as needed dynamically.
* **Queue (FIFO):** Used for the waiting list. If a student wants a book that is already issued, they wait in a queue. The first person to ask gets the book first when it is returned.
* **Stack (LIFO):** Used to track recently returned books. Just like a physical pile of books on a librarian's desk, the last book returned is at the top of the pile.
* **Linear Search:** Used to traverse the linked list to easily find a book by its Title or ID.

## Features
* **Add Book:** Add new books to the library inventory.
* **Display Books:** Show a list of all currently available books.
* **Search Book:** Find out if a specific book exists and if it is available or issued.
* **Issue Book:** Give a book to a student, or put the student on a waitlist if the book is taken.
* **Return Book:** Take a book back, add it to the returned pile (Stack), and alert the next student in line (Queue).

## How to Run
1. Make sure you have Python installed on your computer.
2. Download or clone this repository.
3. Open your terminal or command prompt.
4. Run the file using the command: `python library_system.py`

## Technologies Used
* Python 3
