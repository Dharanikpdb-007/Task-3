# Task-3


# 📚 Library Management System (Java OOP Project)

## 🔰 Objective
This is a beginner-level Java project using **Object-Oriented Programming (OOP)** to manage a simple library system. It supports adding books and users, issuing and returning books, and viewing available books.

## 🛠️ Tools Used
- Language: **Java**
- IDE: **VS Code** or any Java IDE
- Terminal or Command Prompt

## 📦 Features
- Add new books and users
- Issue a book to a user
- Return a book
- View list of all books (with issue status)
- Input validation for user ID

## 📂 Project Structure

```
LibraryManagementSystem.java
```

Contains all the classes:
- `Book`
- `User`
- `Library`
- `LibraryManagementSystem` (main method)

## ▶️ How to Compile and Run

Open terminal and navigate to the folder containing `LibraryManagementSystem.java`:

```bash
javac LibraryManagementSystem.java
java LibraryManagementSystem
```

## 💻 Sample Screenshots

📌 Add Book & User  
```
--- Library Menu ---
1. Add Book
2. Add User
...
Choose option: 1
Enter book title: Java Basics
Enter author name: John
Book added successfully.
```

<br>

📌 Enter Invalid User ID  
```
Choose option: 2
Enter user name: Alice
Enter user ID (number): abc
Enter a valid ID number.
Enter user ID (number): 123
User added successfully.
```

<br>

📌 View All Books  
```
Available Books:
Title: Java Basics, Author: John, Issued: false
```

## 📷 Screenshot Markdown :

![Library output]()

Make sure your screenshots are saved in a `screenshots/` folder.

