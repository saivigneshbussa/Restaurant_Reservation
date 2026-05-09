# Restaurant Reservation System

A full-stack restaurant reservation web application built using PHP and MySQL. This project allows users to browse restaurants, make reservations, and manage bookings through a clean and responsive interface.

---

## Features

- User registration and login
- Restaurant listing and details
- Table reservation system
- Reservation management
- Admin dashboard for managing restaurants and bookings
- Responsive user interface
- Database-driven architecture

---

## Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap

### Backend
- PHP
- MySQL

### Server Environment
- XAMPP / Apache

---

## Project Structure

```bash
Restaurant_Reservation/
│
├── admin/               # Admin dashboard and management
├── assets/              # CSS, JavaScript, images
├── config/              # Database configuration files
├── includes/            # Reusable PHP components
├── database/            # SQL database files
├── index.php            # Home page
├── login.php            # User login page
├── register.php         # User registration page
├── reservation.php      # Reservation functionality
└── README.md
```

---

## Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/saivigneshbussa/Restaurant_Reservation.git
```

### 2. Move the Project to XAMPP htdocs Folder

```bash
htdocs/Restaurant_Reservation
```

### 3. Create Database

Open phpMyAdmin and create a new database.

Example:

```sql
restaurant_reservation
```

### 4. Import Database

Import the SQL file available inside the project directory.

### 5. Configure Database Connection

Update database credentials inside:

```bash
config/db.php
```

Example configuration:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "restaurant_reservation";
```

### 6. Run the Application

Open browser and visit:

```bash
http://localhost/Restaurant_Reservation
```

---

## Core Functionalities

### User Module
- Register and login securely
- View restaurant details
- Reserve tables online
- Manage reservation details

### Admin Module
- Manage restaurants
- View reservations
- Control booking records
- Manage application data

---

## Future Improvements

- Online payment integration
- Email and SMS notifications
- QR-based reservation system
- Live table availability tracking
- Mobile application support
- AI-based restaurant recommendations

---

## Learning Outcomes

This project helped in understanding:

- Full-stack web development
- CRUD operations
- Authentication and session handling
- Database integration using PHP and MySQL
- Responsive web design
- Backend logic implementation

---

## Author

### Sai Vignesh Bussa

- GitHub: https://github.com/saivigneshbussa

---

## Repository Link

https://github.com/saivigneshbussa/Restaurant_Reservation

---

## License

This project is developed for educational and learning purposes.

