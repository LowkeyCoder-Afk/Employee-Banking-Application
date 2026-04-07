# 🏦 Employee Banking Application

A **console-based banking system** built using **Core Java & JDBC**, designed to simulate real-world banking operations like account management, transactions, and history tracking.

---

## 🚀 Features

* 👤 Create Bank Account
* 💰 Deposit Money
* 💸 Withdraw Money
* 📊 Check Account Balance
* 📜 View Transaction History
* 🔐 Secure database interaction using JDBC
* ⚙️ Transaction management for data consistency

---

## 🛠️ Tech Stack

* **Language:** Java
* **Database:** MySQL
* **Connectivity:** JDBC (PreparedStatement)
* **Concepts Used:**

  * OOP (Object-Oriented Programming)
  * Exception Handling
  * Modular Design
  * Transaction Management

---

## 📂 Project Structure

```
EmployeeBankingApp/
│── src/
│   ├── Main.java
│   ├── Account.java
│   ├── BankService.java
│   ├── DatabaseConnection.java
│── sql/
│   └── schema.sql
│── README.md
```

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/employee-banking-app.git
```

---

### 2️⃣ Setup Database

* Open MySQL
* Create database:

```sql
CREATE DATABASE banking_app;
```

* Run your `schema.sql` file

---

### 3️⃣ Configure Database Connection

Update credentials in:

```java
DatabaseConnection.java
```

```java
String url = "jdbc:mysql://localhost:3306/banking_app";
String user = "root";
String password = "your_password";
```

---

### 4️⃣ Run the Application

Compile and run:

```bash
javac Main.java
java Main
```

---

## 📸 Sample Flow

```
1. Create Account  
2. Deposit Money  
3. Withdraw Money  
4. Check Balance  
5. View Transactions  
```

---

## 💡 Key Highlights

* Clean separation of concerns (Service Layer design)
* Secure queries using PreparedStatement
* Real-world banking logic implementation
* Easy to extend (can add GUI / Web version)

---

## 🚀 Future Improvements

* Add Login Authentication (JWT / User Login)
* Convert to Spring Boot REST API
* Add Frontend (React)
* Implement Role-based Access (Admin/User)

---

## 📬 Contact

* 📧 Email: [ikshitabhatnagar16@gmail.com](mailto:ikshitabhatnagar16@gmail.com)
* 🐙 GitHub: https://github.com/LowkeyCoder-Afk
* 💼 LinkedIn: https://linkedin.com/in/ikshita-bhatnagar-744ba1221

---

## ⭐ Show Your Support

If you like this project, don’t forget to ⭐ the repository!

---

### 👩‍💻 Developed by Ikchhita Bhatnagar
