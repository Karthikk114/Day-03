# Day-03
Library system


Classes:

Book → stores title, author, and issued status.

User → stores user name and list of borrowed books.

Library → stores list of all books and provides methods to add, issue, return, and show books.

Main (LibraryManagement):

Uses a Scanner for menu-driven input.

Maintains a Map<String, User> to keep track of registered users.

Loop provides options:

Add Book

Show All Books

Register User

Issue Book

Return Book

Show Borrowed Books

Exit

Flow:

User can add books, register themselves, then issue/return books by typing their name and book title.

Library updates the book’s status (issued or available).

Each user can see which books they borrowed.
