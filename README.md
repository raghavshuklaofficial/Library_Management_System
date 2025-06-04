# 📚 Library Management System

This repository hosts a **Library Management System** built using **C++ and Qt Framework** 🌐, developed as part of our **Project-Based Learning (PBL)** for the *Operating Systems* course at **Graphic Era University** 🏫.

📖 The system provides a GUI-based platform for **managing books, students, and issue/return records** efficiently. It's designed to simulate real-world library workflows with features such as **book search**, **student record management**, and **borrowing tracking**.

> ✅ **Tested On:** Qt Creator 9.x+, MinGW 64-bit  
> 🪟 Built & run on Windows OS using Qt Widgets (no web or mobile targets yet)

---

## ⚙️ How to Build the Project

1. Clone the repository:
```bash
git clone https://github.com/raghavshuklaofficial/Library_Management_System.git
cd Library_Management_System
````

2. Open `Library_System.pro` in **Qt Creator** 📐.

3. Select a suitable **kit** (like `Desktop Qt 5.15.2 MinGW 64-bit`), then:

   * ✅ Build the project using the **hammer icon**
   * ▶️ Run using the **green play button**

---

## 🧩 Features Overview

| 📌 **Feature**           | 🔍 **Description**                                                          |
| ------------------------ | --------------------------------------------------------------------------- |
| 📖 Add/View Books        | Add new books, view existing records, and manage inventory                  |
| 👨‍🎓 Student Management | Register students, view profiles, track book issue/return status            |
| 🔄 Issue/Return Books    | Issue books to students and mark them returned with proper validations      |
| 🧾 Search Functionality  | Real-time search by book name, author, or student ID                        |
| 🖼️ Custom UI            | Styled with `QLabel`, `QPushButton`, and `QTableView` for modern experience |

---

## 📁 Project Structure

```plaintext
Library_Management_System/
├── addbook.cpp / .h / .ui       # Form and logic for adding books
├── addstudent.cpp / .h / .ui    # Form and logic for adding students
├── bookwidget.cpp / .h / .ui    # Main interface to manage books
├── issuebook.cpp / .h / .ui     # Handles issuing books
├── returnbook.cpp / .h / .ui    # Handles returning books
├── studentwidget.cpp / .h / .ui # Student-related info & interactions
├── main.cpp                     # Application entry point
├── Library_System.pro           # Qt project file
├── icons/                       # UI icons and image assets
├── database.db                  # SQLite database storing all data
└── README.md                    # Project documentation and setup guide
```

---

## 🧠 Technologies Used

| 🛠️ **Tech Stack**     | 🌟 **Details**                        |
| ---------------------- | ------------------------------------- |
| 💻 C++                 | Core logic & OOP structure            |
| 🖼️ Qt (Qt Widgets)    | UI layout, signals/slots, and forms   |
| 🗃️ SQLite (via QtSQL) | Lightweight DB for persistent storage |

---

## 💡 Possible Improvements

* 🌐 Add **user authentication** (admin vs user)
* 🔔 Include **due date reminders**
* 📊 Generate **monthly activity reports**
* 🌍 Port to **Web using Qt for WebAssembly** or **React + REST API**

---

## 👨‍💻 Author

**Raghav Shukla**
🔗 [GitHub Profile](https://github.com/raghavshuklaofficial)

---

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for more details.

---

📌 *An academic GUI-based system focused on core CRUD operations, event-driven design, and C++/Qt integration*

```
