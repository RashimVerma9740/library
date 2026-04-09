# library
Library Management System

Project Purpose
This project is a Python-based software system designed to modernize the operations of a local library. It replaces manual record-keeping with a digital, interactive system that tracks book inventory, user registrations, and borrowing records. The goal is to improve data accuracy and administrative efficiency within the organization.

Key Features
Book Management: Add, update, and search for books within the library catalog.

User Management: Register new library members and manage their borrowing history.

Transaction Tracking: Record borrowing and returning events in real-time.

Data Persistence: All records are saved to and loaded from CSV files, ensuring data is kept after the program closes.

Error Handling: Built-in validation to handle invalid user inputs and missing data files.

Project Structure
The program is organized into multiple modules to ensure readability and modularity:

main.py: The entry point of the application containing the interactive menu.

models.py: Contains the class definitions for Book, Member, and Transaction.

database_manager.py: Handles all File I/O operations (reading/writing CSV files).

books.csv & members.csv: Data storage files.

Installation and Execution
Prerequisites
Python 3.x installed on your system.

Steps to Run
Clone the Repository:

Bash

git clone : https://github.com/RashimVerma9740/library
Navigate to the Directory:

Run the Application:

Bash

python main.py
Example Usage
Upon running the program, a menu will appear:

Add Book: Enter the title, author, and ISBN to update the catalog.

Search: Look up books by title or availability status.

Borrow/Return: Input the Member ID and Book ISBN to process a transaction.
