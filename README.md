# BOC Restaurant POS System

https://ayvan6.github.io/BOC-Resturant-POS-system/

**Developed by: ARYANRAJ MALEPU**

BOC Restaurant POS System is a Python-based Point of Sale (POS) application designed to simplify and manage essential restaurant operations. The system provides functionality for restaurant order management, billing, database operations, and transaction handling through an easy-to-use application interface.

## 📌 Project Description

The BOC Restaurant POS System is designed to provide a practical digital solution for restaurant management. It helps manage customer orders, calculate bills, maintain restaurant data, and perform database-related operations.

The project combines Python application logic with a local SQLite database and supporting web technologies.

## 🛠️ Technologies Used

* **Python** – Core application development
* **Tkinter** – Graphical User Interface
* **SQLite** – Local database management
* **HTML** – Web/interface components
* **CSS** – Styling and presentation

## ✨ Key Features

* Restaurant Point of Sale system
* Order management
* Billing and bill calculation
* Menu and item handling
* Database management
* Transaction data storage
* User-friendly graphical interface
* Local SQLite database
* Python-based restaurant management functionality

## 📂 Project Structure

```text
BOC-Resturant-POS-system/
│
├── boc.py
├── billing.py
├── database.py
├── boc.db
├── index.html
└── README.md
```

### File Description

| File          | Description                                   |
| ------------- | --------------------------------------------- |
| `boc.py`      | Main Python application and POS functionality |
| `billing.py`  | Billing and bill-processing functionality     |
| `database.py` | Database-related operations                   |
| `boc.db`      | SQLite database containing project data       |
| `index.html`  | HTML interface/component                      |
| `README.md`   | Project documentation                         |

## ⚙️ Requirements

Before running the project, make sure Python 3 is installed.

Check your Python version:

```bash
python3 --version
```

For Linux systems, install Tkinter if it is not already installed:

```bash
sudo apt update
sudo apt install python3-tk
```

## 🚀 How to Run on Linux

### 1. Clone the Repository

```bash
git clone https://github.com/ayvan6/BOC-Resturant-POS-system.git
```

### 2. Open the Project Directory

```bash
cd BOC-Resturant-POS-system
```

### 3. Run the Main Application

```bash
python3 boc.py
```

If your Linux system uses `python` instead:

```bash
python boc.py
```

## 🗄️ Database

The project includes a local SQLite database:

```text
boc.db
```

The database is used by the Python application for storing and managing application data. The `database.py` file provides the database-related functionality.

No separate MySQL server is required for the included SQLite database.

## 🧾 Billing Module

The `billing.py` file provides the billing-related functionality of the POS system. It is used as part of the restaurant billing and transaction workflow.

## 🌐 HTML Component

The project also contains:

```text
index.html
```

This file provides the HTML component of the project and can be opened in a web browser when required:

```bash
xdg-open index.html
```

## 🔧 Troubleshooting

### Tkinter Not Found

If you receive an error related to Tkinter:

```text
ModuleNotFoundError: No module named 'tkinter'
```

Install it using:

```bash
sudo apt update
sudo apt install python3-tk
```

Then run:

```bash
python3 boc.py
```

### Permission Issues

If you encounter permission problems, you can check the project permissions using:

```bash
ls -la
```

## 🎯 Project Objective

The main objective of the BOC Restaurant POS System is to demonstrate how software can be used to automate common restaurant operations such as order handling, billing, and data management.

The project also demonstrates practical implementation of Python GUI programming, database connectivity, and modular application development.

## 👨‍💻 Developer

**ARYANRAJ MALEPU**

BOC Restaurant POS System

## 📜 License

This project is intended for educational and development purposes.
