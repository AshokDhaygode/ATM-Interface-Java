# 🏧 ATM Interface Using Java

A console-based ATM Interface application developed using Java. This project simulates basic ATM operations, including user authentication, cash withdrawal, deposits, money transfers, and balance inquiries.

## 🚀 Features

- 🔐 **Login Authentication** — Authenticate using a username and PIN.
- 💸 **Withdraw Money** — Withdraw funds when sufficient balance is available.
- 💰 **Deposit Money** — Deposit money and update the account balance.
- 💳 **Transfer Money** — Transfer funds to another recipient.
- 📊 **Check Balance** — View the current account balance.
- 🚪 **Exit** — Exit the application.
- 📝 **Transaction Activity** — Store basic login and transfer activity using Java's `ArrayList`.

## 🛠️ Technologies Used

- Java
- Scanner for user input
- ArrayList from the Java Collections Framework
- Git and GitHub

## 📋 Prerequisites

- Java Development Kit (JDK) installed.
- A terminal or Java IDE such as IntelliJ IDEA, Eclipse, or VS Code.

## ⚙️ Installation and Execution

### 1. Clone the Repository

```bash
git clone https://github.com/AshokDhaygode/ATM-Interface-Java.git
```

### 2. Navigate to the Project Directory

```bash
cd ATM-Interface-Java
```

### 3. Compile the Java Program

```bash
javac ATM_INTERFACE2.java
```

### 4. Run the Application

```bash
java ATM_INTERFACE2
```

## 🔑 Demo Login Credentials

The current implementation uses hardcoded login credentials.

| Field | Value |
|---|---|
| Username | Ashok |
| PIN | 3958 |

**Note:** These credentials are for demonstration purposes only. The application is a learning project and is not connected to a real banking system.

## 🖥️ Available Operations

After launching the application, you can select an operation from the ATM menu.

| Option | Operation |
|---|---|
| 1 | Withdraw Money |
| 2 | Deposit Money |
| 3 | Transfer Money |
| 4 | Check Balance |
| 5 | Exit |

## 📚 Java Concepts Practiced

This project demonstrates fundamental Java programming concepts:

- Methods and method calls
- Conditional statements (`if-else`)
- Loops (`while`)
- Switch statements
- User input using `Scanner`
- Collections using `ArrayList`
- Arithmetic and comparison operators

## 🔮 Future Enhancements

- Support multiple bank accounts.
- Implement proper account authentication.
- Add transaction history with timestamps.
- Improve input validation and exception handling.
- Store account data persistently using a database.
- Add unit tests using JUnit.
- Prevent invalid transactions and incorrect balance updates.

## ⚠️ Limitations

- The account balance resets to zero each time the application starts.
- Login credentials are hardcoded.
- Account information is not stored in a database.
- The application is intended for learning and demonstration purposes.

## 👨‍💻 Author

**Ashok Dhaygode**

GitHub: [AshokDhaygode](https://github.com/AshokDhaygode)

---

⭐ If you find this project useful for learning Java, consider giving the repository a star!
