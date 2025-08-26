# 🏨 Hotel Management System (Java + MySQL)

A simple **Hotel Reservation Management System** built with **Java (JDBC)** and **MySQL**.
This project demonstrates how to perform basic **CRUD operations** (Create, Read, Update, Delete) using a MySQL database with JDBC in Java.

---

## ✨ Features

* 📌 Reserve a room
* 📌 View all reservations
* 📌 Get room numbers by guest name
* 📌 Update reservation details
* 📌 Delete a reservation

---

## 🚀 Technologies Used

* **Java** (JDBC)
* **MySQL**
* **MySQL Connector/J** (`com.mysql.cj.jdbc.Driver`)

---

## ⚡ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/prince0710/HotelManagementSystem.git
```

### 2. Open in IDE

Import the project into **IntelliJ IDEA** or **Eclipse**.

### 3. Configure Database

Run the following SQL commands in MySQL:

```sql
CREATE DATABASE hotel_db;
USE hotel_db;

CREATE TABLE reservations (
  reservation_id INT AUTO_INCREMENT PRIMARY KEY,
  guest_name VARCHAR(100) NOT NULL,
  room_number INT NOT NULL,
  contact_number VARCHAR(20) NOT NULL
);
```

### 4. Configure Database Properties

Update `db.properties` with your MySQL credentials:

```properties
url=jdbc:mysql://localhost:3306/hotel_db
user=root
password=your_password
```

### 5. Run the Project

Execute `HotelReservationSystem.java` to start the program.

---

## 🎯 Example Usage

1. Run the application
2. Choose an option from the menu:

   * Add a new reservation
   * View all reservations
   * Update a reservation
   * Delete a reservation

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repo
2. Create a new branch (`feature-branch`)
3. Commit your changes
4. Push and create a Pull Request






