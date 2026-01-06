Core Java Banking Application
Project Description
This is a console-based Banking Application developed using Core Java.
The project follows a layered architecture and demonstrates strong usage of OOP concepts, custom exceptions, enums, and repository-service pattern.

It simulates real-world banking operations such as account creation, deposits, withdrawals, transfers, and transaction management.

Features:-

      -Create bank accounts

      -Deposit money

      -Withdraw money

      -Transfer money between accounts

      -View account details

      -Handle transactions using enums

      -Proper validation and error handling using custom exceptions

Project Structure
src/
 ├── app
 │   └── Main.java
 │
 ├── domain
 │   ├── Account.java
 │   ├── Customer.java
 │   ├── Transaction.java
 │   └── Type.java
 │
 ├── repository
 │   ├── AccountRepository.java
 │   ├── CustomerRepository.java
 │   └── TransactionRepository.java
 │
 ├── service
 │   └── BankService.java
 │
 ├── service.impl
 │   └── BankServiceImpl.java
 │
 ├── exceptions
 │   ├── AccountNotFoundException.java
 │   ├── InsufficientFundsException.java
 │   └── ValidationException.java

Core Java Concepts Used....

    Object-Oriented Programming (OOP)

      -Encapsulation

      -Abstraction

      -Inheritance

      -Polymorphism

      -Collections Framework

      -Custom Exception Handling

      -Enums for transaction types

      -Layered architecture (Controller → Service → Repository)

Technologies Used:-

      -Java (Core Java)

      -Eclipse IDE

      -Git & GitHub

How to Run the Project

  1.Clone the repository:
        git clone https://github.com/satish2021-0/java-banking-application.git
        
  2.Open the project in Eclipse

  3.Navigate to:
        src/app/Main.java
    
4.Right-click → Run as → Java Application

Sample Output
    1) Open Account
    2) Deposit
    3) Withdraw
    4) Transfer
    5) Account Statement
    6) List Accounts
    7) Search Accounts by Customer Name
    0) Exit

Future Enhancements:-
      -Add JDBC for database persistence
      -Convert to Spring Boot REST API
      -Add authentication and authorization
      -Add logging and unit testing

If you like this project
Don’t forget to ⭐ star the repository!
