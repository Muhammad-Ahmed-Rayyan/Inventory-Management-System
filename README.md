<div align="center">

# 🛒 INVENTORY-MANAGEMENT-SYSTEM

*Manage products, stock, and customer purchases efficiently with a console-based linked list system.*

![last commit](https://img.shields.io/github/last-commit/Muhammad-Ahmed-Rayyan/Inventory-Management-System)
![cpp](https://img.shields.io/badge/C++-100%25-blue)
![languages](https://img.shields.io/github/languages/count/Muhammad-Ahmed-Rayyan/Inventory-Management-System)

<br>

Built with the tools and technologies:

![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=c%2B%2B&logoColor=white)
![Console](https://img.shields.io/badge/Console-Application-grey)

</div>

---

## 🚀 Overview

**Inventory-Management-System** is a C++ console application that simulates a departmental store (**SZABIST Mart**) allowing both vendor and customer operations.  
It is built entirely from scratch using linked lists for dynamic management of categories, products, and a shopping cart.

---

## ✨ Features

- **🗂️ Vendor Portal**
  - Create new product categories
  - Add, update, or remove products
  - Manage stock levels and pricing

- **🛍️ Customer Portal**
  - Browse categories and products
  - Add or remove items from the cart
  - Generate a detailed bill with tax

- **📝 Bill Output**
  - Generates a `bill.txt` file summarizing purchases, tax, and total.

---

## 🏗️ Project Structure

| File            | Description                                      |
|-----------------|--------------------------------------------------|
| `vendor.c++`    | Main driver file, menus for vendor & customer    |
| `categories.c++`| Linked list implementation for product catalog   |
| `cart.c++`      | Linked list implementation for shopping cart     |
| `bill.txt`      | Sample output bill after customer checkout       |

---

## 📋 Concepts Utilized

- **Class and Objects:** Building blocks of the program, encapsulating data and functionality.
- **Constructors:** Initialization of valid values for data members when objects are created.
- **Function Overloading:** Multiple functions with the same name but different parameters.
- **Encapsulation:** Wrapping up data and functions into a single unit.
- **Polymorphism:** The ability of an entity to have various forms.
- **Singly Linked List:** Collection of nodes linked together, used for dynamic data storage.
- **File Handling:** Mechanism to store program output in a file.

---

## ⚙️ Compilation & Running

Use `g++` (or any C++ compiler) to compile:

```bash
# Compile the program
g++ vendor.c++ -o inventory

# Run the program
./inventory
```

---

## 📝 Credits

- Developed with pure C++ and linked lists.
- Licensed under MIT.
    [![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)
---
