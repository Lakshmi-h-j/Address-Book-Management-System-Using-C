Address Book Management System in C

1. Introduction

The Address Book Management System is a menu-driven application developed using the C programming language. It helps users manage contact information, including names, mobile numbers, and email addresses. The project demonstrates fundamental C programming concepts through practical contact management operations.

2. Objectives

Develop a simple and user-friendly contact management application.

Implement Create, Read, Update, and Delete (CRUD) operations.

Organize contact information using structures and arrays.

Apply functions, pointers, and string handling in a real-world application.

Validate user inputs and manage contact records efficiently.

3. Features of Address Book

Create Contact: Add a new contact with a name, mobile number, and email address.

List Contacts: Display all stored contacts.

Search Contact: Search for contacts using supported fields such as name, mobile number, or email address.

Edit Contact: Modify existing contact details.

Delete Contact: Remove an existing contact.

Input Validation: Check contact information according to the program's validation rules.

Duplicate Handling: Handle duplicate contact entries according to the implemented logic.

Save and Load: Store and retrieve contact records if file handling is implemented.

4. System Requirements

Hardware Requirements

Computer or laptop

Minimum 2 GB RAM recommended

Basic storage space for source files and contact data

Software Requirements

Operating System: Windows or Linux

C Compiler: GCC or another compatible C compiler

Code Editor: Visual Studio Code or any text editor

Terminal or command prompt

5. Project Structure

Address-Book-Management-System-in-C/
│
├── main.c
├── address_book.h
├── address_book.c
├── README.md
└── .gitignore

Note: This is an example structure. Replace the filenames with your actual project files. If your project contains only one C source file, list only that file along with README.md and .gitignore.

6. How to Run

Step 1: Clone the Repository

git clone https://github.com/YOUR-USERNAME/Address-Book-Management-System-in-C.git

Replace YOUR-USERNAME with your GitHub username.

Step 2: Navigate to the Project Folder

cd Address-Book-Management-System-in-C

Step 3: Compile the Program

For a single source file named main.c:

gcc main.c -o addressbook

For a project with multiple source files, compile the required files together. For example:

gcc main.c address_book.c -o addressbook

Use the filenames present in your repository.

Step 4: Execute the Program

On Linux or Ubuntu:

./addressbook

On Windows using GCC:

addressbook.exe

7. How It Works

The program displays a menu of contact management operations.

The user selects an operation.

The program accepts the required contact information.

The selected operation is performed on the contact records.

The result is displayed to the user.

The menu is displayed again until the user chooses to exit.

Contact data is stored in memory while the program runs. Data remains available after restarting only if saving and loading through file handling are implemented.

8. Sample Input

The following is an illustrative example of adding a contact:

Enter your choice: 1
Enter name: Rahul
Enter mobile number: 9876543210
Enter email ID: rahul@example.com

The menu option and prompts may differ in your actual program.

9. Sample Output

Contact added successfully!

Name: Rahul
Mobile Number: 9876543210
Email ID: rahul@example.com

This is an example of the expected output. Replace it with the actual output from your program if the wording or format differs.

10. Future Enhancements

Add a dynamic memory allocation approach for managing larger contact lists.

Improve input validation and error handling.

Implement sorting and advanced search functionality.

Add persistent storage using files or a database.

Develop a graphical user interface.

Add automated test cases for contact management operations.

11. Author

Lakshmi HJ

GitHub: https://github.com/YOUR-USERNAME

LinkedIn: Add your LinkedIn profile URL here

12. Learning Outcomes

Improved understanding of C programming fundamentals.

Practical experience with structures, arrays, pointers, and functions.

Experience implementing CRUD operations.

Better understanding of string handling and input validation.

Hands-on experience documenting and maintaining a software project.
