Library Management System
A simple Java console application that simulates a library management system. This program allows users to add books, display available books, issue books, and return books. It serves as a beginner-friendly project for learning Java and understanding basic object-oriented programming concepts.

Features
Add Book: Adds a new book with a title, author, and ISBN to the library.
Display Books: Shows a list of all books in the library with their details (title, author, ISBN, and issue status).
Issue Book: Allows a book to be issued to a user by its ISBN if it is available.
Return Book: Allows a previously issued book to be returned by its ISBN.
Getting Started
Prerequisites
Java Development Kit (JDK) installed on your computer.
A text editor or IDE (e.g., VS Code, IntelliJ IDEA, Eclipse) to write and run the code.
Installation
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/library-management-system.git
cd library-management-system
Compile the main Java file:
bash
Copy code
javac LibraryManagementSystem.java
Run the program:
bash
Copy code
java LibraryManagementSystem
Usage
When you run the program, you will see a menu with several options:

Add Book: Enter the title, author, and ISBN to add a new book to the library.
Display Books: View all books currently in the library, with information on each book.
Issue Book: Enter the ISBN of the book you want to issue. If the book is available, it will be marked as issued.
Return Book: Enter the ISBN of a previously issued book to return it to the library.
Exit: Close the program.
Here’s an example of how to use the application:

plaintext
Copy code
Library Management System:
1. Add Book
2. Display Books
3. Issue Book
4. Return Book
5. Exit
Choose an option: 1

Enter book title: Java Programming
Enter book author: John Doe
Enter book ISBN: 1234567890
Book added successfully.
Project Structure
Book: Represents a book in the library with properties such as title, author, ISBN, and issue status.
Library: Manages the collection of books, with functions to add, issue, return, and display books.
LibraryManagementSystem: The main class with a menu-driven interface to interact with the library system.
Contributing
Contributions are welcome! If you have suggestions for improvements or find bugs, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.












