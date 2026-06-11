# Gym Management System

![PHP](https://img.shields.io/badge/PHP-8.x-blue)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange)
![Bootstrap](https://img.shields.io/badge/Bootstrap-4.x-purple)


## Overview

Gym Management System is a web-based application developed using PHP and MySQL to simplify the management of gym operations. The system provides an easy-to-use administrative interface for managing gyms, members, trainers, and payment records.

The project was developed to demonstrate database-driven web application development using PHP, MySQL, Bootstrap, and CRUD operations.

---

## Features

### Gym Management

* Add new gyms
* View gym information
* Update gym details
* Delete gyms
* Search gyms

### Member Management

* Add new members
* View member records
* Update member information
* Delete members
* Search members

### Trainer Management

* Add trainers
* View trainer information
* Update trainer records
* Delete trainers
* Search trainers

### Payment Management

* Record member payments
* View payment history
* Update payment information
* Delete payment records
* Search payments

### Authentication

* Secure login system
* Session-based authentication
* Logout functionality

---

## Technology Stack

### Frontend

* HTML5
* CSS3
* Bootstrap 4
* Font Awesome

### Backend

* PHP

### Database

* MySQL

### Development Environment

* XAMPP / WAMP

---

## Project Structure

```text
Gym-Management-Website/
│
├── add_gym.php
├── add_member.php
├── add_trainer.php
├── add_payment.php
│
├── manage_gym.php
├── manage_member.php
├── manage_trainer.php
├── manage_payment.php
│
├── update_gym.php
├── update_member.php
├── update_trainer.php
├── update_payment.php
│
├── delete_gym.php
├── delete_member.php
├── delete_trainer.php
├── delete_payment.php
│
├── gym_search.php
├── member_search.php
├── trainer_search.php
├── payment_search.php
│
├── auth.php
├── db.php
├── index.php
├── home.php
├── logout.php
│
├── gym.sql
└── style.css
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/shahbaaz771/Gym-Management-Website.git
```

### 2. Move Project to XAMPP

Copy the project folder into:

```text
xampp/htdocs/
```

### 3. Start Apache and MySQL

Open XAMPP Control Panel and start:

* Apache
* MySQL

### 4. Create Database

Open:

```text
http://localhost/phpmyadmin
```

Create a database named:

```sql
gym
```

### 5. Import Database

Import the provided file:

```text
gym.sql
```

### 6. Run the Application

Open:

```text
http://localhost/Gym-Management-Website
```

---

## Screenshots

You can add screenshots here:

### Login Page

```text
screenshots/login.png
```

### Dashboard

```text
screenshots/dashboard.png
```

### Member Management

```text
screenshots/members.png
```

### Payment Management

```text
screenshots/payments.png
```

---

## Learning Objectives

This project demonstrates:

* PHP CRUD Operations
* Database Integration with MySQL
* Session Management
* Form Handling
* Search Functionality
* Bootstrap-Based UI Design
* Web Application Development Fundamentals

---

## Future Improvements

* Member attendance tracking
* Subscription plan management
* Email notifications
* QR code member check-in
* Responsive mobile interface
* Dashboard analytics and reports

---

## Author

**Shahbaaz Ahmed Sadiq**

GitHub:
https://github.com/shahbaaz771

