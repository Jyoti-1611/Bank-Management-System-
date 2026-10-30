# 🏦 Bank Management System

A Python-based Bank Management System that provides basic banking operations through a command-line interface. The project uses Object-Oriented Programming (OOP) concepts and JSON file handling to manage customer accounts and banking transactions.

## 📌 Project Overview

The Bank Management System is designed to simplify basic banking operations by allowing users to create accounts, deposit and withdraw money, view account details, update personal information, and delete accounts.

Customer information and account balances are stored in a JSON file, ensuring that the data remains available even after the application is closed.

## ✨ Features

- Account Creation: Create a new bank account by providing personal details.
- Automatic Account Number Generation: Generate a random account number using letters, digits, and special characters.
- Money Deposit: Deposit money into an existing account.
- Money Withdrawal: Withdraw money after account verification and balance checking.
- View Account Details: Access customer information using account credentials.
- Update Account Details: Update name, email address, and PIN.
- Delete Account: Delete an existing bank account with confirmation.
- JSON Data Storage: Store and maintain customer records using JSON file handling.

## 🛠️ Technologies Used

- Python 3
- JSON
- Object-Oriented Programming (OOP)

### Python Concepts Implemented

- Classes and Objects
- Class Methods
- Encapsulation
- File Handling
- Exception Handling
- List Comprehensions
- Random Module
- Data Manipulation

## 📂 Project Structure

```text
Bank-Management-System-/
│
├── main.py        # Main application logic
├── data.json      # Customer and account information
└── README.md      # Project documentation
```

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/Jyoti-1611/Bank-Management-System-.git
```

### Step 2: Navigate to the Project Directory

```bash
cd Bank-Management-System-
```

### Step 3: Run the Application

Ensure Python 3 is installed on your system.

```bash
python main.py
```

No external libraries are required to run this project.

## 🚀 Application Menu

After executing the program, users can select from the following operations:

| Option | Operation |
|---|---|
| 1 | Create a Bank Account |
| 2 | Deposit Money |
| 3 | Withdraw Money |
| 4 | View Account Details |
| 5 | Update Account Details |
| 6 | Delete Account |

## 💾 Data Storage

The project uses a JSON file (`data.json`) to store customer information.

Each account contains:

- Customer Name
- Age
- Email Address
- PIN
- Account Number
- Account Balance

The application updates the JSON file whenever account information or transaction details are modified.

## 🔮 Future Enhancements

- Develop a graphical user interface (GUI).
- Add transaction history and account statements.
- Implement secure authentication and PIN encryption.
- Add fund transfer functionality.
- Integrate a database such as MySQL or PostgreSQL.
- Improve input validation and exception handling.

## 👩‍💻 Author

Jyoti Kumari

GitHub: [Jyoti-1611](https://github.com/Jyoti-1611)

---

⭐ If you find this project useful, don't forget to give the repository a star!
