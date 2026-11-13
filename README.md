C++ Phonebook Application

A feature-rich, modular command-line Phonebook Application built in C++. Designed with clean separation of concerns, Object-Oriented Programming (OOP) principles, and file-handling persistence.

---

## 🚀 Features

* Add Contact: Store names, phone numbers, and email addresses.

* Search & Display: Quickly look up contacts by name or phone number.

* Delete & Update: Manage and modify existing records seamlessly.

* File Persistence:Automatically saves and loads contacts from a local data file so data isn't lost on exit.

* Modular Architecture:Clean separation of header files (`include/`) and source files (`src/`).

---

🛠️ Project Structure

cpp-phonebook-app/
├── include/
│   ├── Contact.h       # Contact class declaration
│   └── PhoneBook.h     # PhoneBook management class declaration
├── src/
│   ├── Contact.cpp     # Contact class methods
│   ├── PhoneBook.cpp   # PhoneBook logic & file I/O implementation
│   └── main.cpp        # Interactive CLI menu & entry point
├── .gitignore          # Excludes binaries and build artifacts
├── LICENSE             # MIT Open Source License
└── README.md           # Project documentation
