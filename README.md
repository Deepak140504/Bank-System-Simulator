# 🏦 ATM Simulator System

A Java Swing and MySQL-based desktop application that simulates real-world ATM banking operations. This project enables users to create bank accounts, securely log in using a generated card number and PIN, and perform essential banking transactions such as deposits, withdrawals, balance enquiries, mini statements, fast cash withdrawals, and PIN changes.

---

## 📌 Overview

The **ATM Simulator System** is developed using **Java**, **Java Swing**, **JDBC**, and **MySQL**. It provides a user-friendly graphical interface that demonstrates how ATM software works while showcasing Java GUI development, database connectivity, and object-oriented programming concepts.

This project is intended for educational purposes and helps learners understand the implementation of a desktop banking application using Java technologies.

---

## ✨ Features

- 👤 User Registration (Multi-step Signup)
- 💳 Automatic Card Number Generation
- 🔐 Secure Login using Card Number & PIN
- 💰 Deposit Money
- 💸 Withdraw Money
- ⚡ Fast Cash Withdrawal
- 📊 Balance Enquiry
- 📄 Mini Statement
- 🔄 PIN Change
- 🗄️ MySQL Database Integration
- 🖥️ Interactive Java Swing GUI

---

## 🛠️ Technologies Used

- Java
- Java Swing
- JDBC
- MySQL
- Eclipse IDE / NetBeans
- JCalendar
- MySQL Connector/J

---

## 📂 Project Structure

```
ATM-Simulator-System
│
├── src
│   ├── Login.java
│   ├── Signup.java
│   ├── Signup2.java
│   ├── Signup3.java
│   ├── Transactions.java
│   ├── Deposit.java
│   ├── Withdrawl.java
│   ├── FastCash.java
│   ├── BalanceEquiry.java
│   ├── MiniStatement.java
│   ├── Pin.java
│   └── Conn.java
│
├── icons/
├── README.md
└── bankmanagementsystem.sql
```

---

## 📋 Modules

| Module | Description |
|---------|-------------|
| **Login.java** | Authenticates users using Card Number and PIN |
| **Signup.java** | Collects personal information |
| **Signup2.java** | Collects additional user details |
| **Signup3.java** | Generates Card Number and PIN |
| **Transactions.java** | Main ATM dashboard |
| **Deposit.java** | Handles deposit transactions |
| **Withdrawl.java** | Handles cash withdrawals |
| **FastCash.java** | Provides predefined withdrawal amounts |
| **BalanceEquiry.java** | Displays current account balance |
| **MiniStatement.java** | Displays transaction history |
| **Pin.java** | Updates user PIN |
| **Conn.java** | Establishes JDBC database connection |

---

## 🗄️ Database

**Database Name**

```sql
bankmanagementsystem
```

### Tables Used

- signup
- signup2
- signup3
- login
- bank

---

## ⚙️ Application Workflow

1. User registers by completing the signup process.
2. System automatically generates a unique Card Number and PIN.
3. User logs in using the generated credentials.
4. ATM dashboard is displayed.
5. User performs banking operations such as:
   - Deposit
   - Withdraw
   - Fast Cash
   - Balance Enquiry
   - Mini Statement
   - PIN Change
6. All account and transaction details are stored in the MySQL database.

---

## 📷 Application Screens

- Login Screen
- Signup Form
- ATM Dashboard
- Deposit Window
- Withdraw Window
- Fast Cash
- Balance Enquiry
- Mini Statement
- PIN Change

> **Note:** Add screenshots inside a `screenshots/` folder and update this section with images.

---

## 🚀 How to Run

### Prerequisites

- Java JDK 8 or above
- Eclipse IDE / NetBeans
- MySQL Server
- MySQL Connector/J
- JCalendar Library

### Steps

1. Clone the repository.

```bash
git clone https://github.com/your-username/ATM-Simulator-System.git
```

2. Import the project into Eclipse or NetBeans.

3. Create the MySQL database.

```sql
CREATE DATABASE bankmanagementsystem;
```

4. Import the provided SQL file.

5. Update database credentials in `Conn.java`.

6. Add the required JAR files:
   - mysql-connector-j.jar
   - jcalendar.jar

7. Run `Login.java`.

---

## 🎯 Learning Outcomes

This project demonstrates:

- Object-Oriented Programming (OOP)
- Java Swing GUI Development
- Event Handling
- JDBC Connectivity
- SQL CRUD Operations
- Multi-window Navigation
- Database-driven Desktop Applications

---

## 📌 Future Enhancements

- Password Encryption
- OTP Verification
- Email Notifications
- Transaction Receipts (PDF)
- Account Transfer
- Interest Calculation
- Admin Dashboard
- User Profile Management
- Improved UI Design
- Responsive Layout

---

## ⚠️ Disclaimer

This project is developed **for educational purposes only**. It is not intended for real-world banking applications and does not implement production-level security features such as encrypted PIN storage, secure authentication mechanisms, or advanced input validation.

---

## 👨‍💻 Author

**Deepak P**

If you found this project helpful, consider giving it a ⭐ on GitHub.
