# 🏧 ATM Interface Using Java

A simple, console-based **ATM Interface application developed using Java**. This project simulates basic ATM operations, allowing users to log in using a username and PIN, withdraw money, deposit funds, transfer money to another user, and check their account balance.

The project demonstrates core Java programming concepts, including methods, conditional statements, loops, switch cases, user input handling, and Java Collections.

## ✨ Features

- **🔐 Login Authentication:** Log in using a username and PIN.
- **💸 Withdraw Money:** Withdraw money if sufficient balance is available.
- **💰 Deposit Money:** Deposit money into the account and update the balance.
- **💳 Money Transfer:** Transfer money to another user's account.
- **📊 Check Balance:** View the current account balance.
- **🚪 Exit:** Exit the application when finished.
- **📝 Transaction History:** Store login and transfer activity using an `ArrayList`.

## 🛠️ Technologies Used

- **Programming Language:** Java
- **Input Handling:** `Scanner`
- **Collections Framework:** `ArrayList`
- **Development Environment:** Any Java-compatible IDE or terminal
- **Version Control:** Git and GitHub

## 📋 Prerequisites

Before running the project, make sure you have:

- Java Development Kit (JDK) installed.
- A Java-compatible IDE, such as IntelliJ IDEA, Eclipse, or VS Code, or a terminal.
- Basic knowledge of running Java programs.

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
```

Replace `<YOUR_GITHUB_REPOSITORY_URL>` with your repository's actual URL.

### 2. Navigate to the Project Directory

```bash
cd <YOUR_PROJECT_DIRECTORY>
```

### 3. Compile the Java Program

If your Java file is named `ATM_INTERFACE2.java`, run:

```bash
javac ATM_INTERFACE2.java
```

### 4. Run the Application

```bash
java ATM_INTERFACE2
```

## 🔑 Login Credentials

The current implementation contains hardcoded login credentials.

| Field | Value |
|---|---|
| Username | Ashok |
| PIN | 3958 |

**Note:** The login logic checks whether the username contains `Ashok`, rather than requiring an exact username match. These credentials are for demonstration purposes only.

## 🖥️ Application Menu

After starting the application, you can choose from the following operations:

```text
ATM

Press 1 to Withdraw
Press 2 to Deposit
Press 3 to Transfer
Press 4 to Check Balance
Press 5 to EXIT

Choose the operation you want to perform:
```

### Example Operations

**1. Deposit Money**
- Enter the amount you want to deposit.
- The application updates the balance.
- A confirmation message displays the updated balance.

**2. Withdraw Money**
- Enter the amount you want to withdraw.
- The application checks whether sufficient funds are available.
- If the balance is sufficient, the withdrawal is completed.

**3. Transfer Money**
- Enter the transfer amount.
- Enter the recipient's username.
- The application displays a transaction confirmation.

**4. Check Balance**
- View the current account balance.

**5. Exit**
- Exit the ATM application.

## 📚 Java Concepts Demonstrated

This project provides hands-on experience with the following Java concepts:

- **Methods:** Separate methods for login and money transfer operations.
- **Conditional Statements:** `if-else` conditions for authentication and balance validation.
- **Loops:** A `while` loop to keep the ATM menu running.
- **Switch Statements:** A `switch` statement to handle user-selected operations.
- **Arrays and Collections:** `ArrayList` to store basic activity records.
- **User Input:** `Scanner` to read input from the console.
- **Variables and Operators:** Managing balances and performing arithmetic operations.

## ⚠️ Current Limitations

This is a beginner-level project created for learning and demonstration purposes.

- Account information and PINs are hardcoded.
- The initial account balance is set to zero.
- Account data is not stored permanently.
- Transaction history is stored only during program execution.
- The application does not connect to a real banking system.
- Input validation and transaction handling can be improved.

## 🔮 Future Improvements

Potential enhancements include:

- Add multiple user accounts.
- Implement a dedicated account class.
- Maintain separate account balances.
- Store transaction history with timestamps.
- Add secure authentication and PIN management.
- Validate negative deposit and withdrawal amounts.
- Improve exception handling and input validation.
- Store account information using a database.
- Add unit tests using JUnit.

## 👨‍💻 Author

**Ashok**

Developed as a Java programming project to practice core programming concepts and implement basic ATM functionality.

---

⭐ If you find this project useful for learning Java, consider giving the repository a star!
