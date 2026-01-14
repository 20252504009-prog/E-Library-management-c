# 📚 E-Library Management System (C)

A simple **E-Library Management System** developed in **C language** that allows users to manage basic library operations such as adding books, viewing book details, listing all books, and checking the total number of books available.

This project is menu-driven and uses **structures, arrays, loops, and functions**, making it ideal for beginners learning C programming.

---

## 🚀 Features

- ➕ Add new book information  
- 🔍 Display details of a specific book  
- 📖 List all books available in the library  
- 📊 Show total number of books in the library  
- ❌ Exit the system safely  

---

## 🛠️ Concepts Used

- C Structures  
- Arrays  
- Functions  
- Loops (`for`, `do-while`)  
- Conditional statements (`if-else`)  
- String handling (`string.h`)  
- Menu-driven program design  

---

## 📂 Data Structure Used

```c
struct librarybooks {
    char bookname[50];
    char author[50];
    int pages;
    int price;
};
