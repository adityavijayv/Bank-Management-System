# Bank-Management-System

📌 Description

The Bank Management System is a fully functional banking application built using Java Swing and MySQL. It allows users to perform essential banking operations through a well-structured graphical user interface.

## 🎥 Demo  
Watch the project demo here: [Click to Watch]
(https://drive.google.com/file/d/1cKMnoiIoD5fp9hApk2fxRtCyfdrCR9-A/view?usp=sharing)


🚀 Features
	•	Deposit Money 💰 – Securely add funds to an account.
	•	Withdrawal 🏧 – Withdraw money safely.
	•	Balance Enquiry 📊 – Check your current account balance.
	•	Mini Statement 📝 – View recent transactions.
	•	User Authentication 🔐 – Secure login with a card number and PIN.

 🛠️ Technologies Used
	•	Java Swing – For the graphical user interface.
	•	MySQL – For database management.
	•	JCalendar – For date selection.

 📂 Installation Guide

Prerequisites

Before running the project, ensure you have:
✅ MySQL installed and running.
✅ IntelliJ IDEA (or any Java IDE like Eclipse/NetBeans).
✅ Java Development Kit (JDK 8+) installed.

Database Setup

1️⃣ Create Database:
Open MySQL Workbench and run:
CREATE DATABASE bankSystem;
use bankSystem;

2️⃣ Create Required Tables:
Execute the following queries one by one in MySQL Workbench:
create table signup(Form_no varchar(30), name varchar(30), father_name varchar(30), DOB varchar(30), gender varchar(30), email varchar(60), marital_status varchar(30),address varchar(60), city varchar(30), pincode varchar(30), state varchar(50));

create table signuptwo(Form_no varchar(30), religion varchar(30), category varchar(30), income varchar(30), education varchar(30), occupation varchar(60), pan_card varchar(30),adhaar_card varchar(30), sr_citizen varchar(30), acc_previous varchar(30));

create table signupthree(Form_no varchar(30), acc_type varchar(40), cardNo varchar(30), pin varchar(30), facilities varchar(200));

create table login(Form_no varchar(30), card_number varchar(50), pin varchar(30));

create table bank(pin varchar(30), date varchar(50), type varchar(30), amount varchar(30));


Running the Project

1️⃣ Open IntelliJ IDEA (or your preferred IDE).
2️⃣ Load the project files.
3️⃣ Ensure that JCalendar and MySQL Connector dependencies are added.
4️⃣ Run the login.java file to launch the application.


🎯 Future Improvements
	•	Implementing Admin Panel for managing users.
	•	Adding transaction filters (date-wise, type-wise).
	•	Enhancing security features (OTP-based authentication).

 👥 Contributing

Feel free to contribute to this project by suggesting improvements, reporting bugs, or adding new features.

📜 License

This project is for educational purposes. You are free to modify and enhance it.
