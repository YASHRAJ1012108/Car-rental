# 🚗 Online Car Rental System

## 📋 Project Overview

The Online Car Rental System is a comprehensive web-based application designed to facilitate car rental services. This project provides a complete digital platform for customers to browse available vehicles, make reservations, and manage their rental bookings online. The system offers an intuitive user interface with modern web technologies to ensure a seamless car rental experience.

This project demonstrates practical implementation of web development concepts including user authentication, database management, booking systems, and responsive design principles suitable for modern car rental business operations.

## 📁 Repository Structure

```
Car-rental/
├── Online-Car-Rental.zip     # Complete project archive (5 MB)
└── README.md                 # Project documentation
```

### 📦 Online-Car-Rental.zip Contents

The project archive contains the complete car rental web application with the following typical structure:

```
Online-Car-Rental/
├── index.html                # Main homepage
├── css/                      # Stylesheets directory
│   ├── style.css            # Main stylesheet
│   └── bootstrap.css        # Bootstrap framework
├── js/                       # JavaScript files
│   ├── script.js            # Main functionality
│   └── jquery.js            # jQuery library
├── images/                   # Image assets
│   ├── cars/                # Car images
│   ├── logo.png             # Application logo
│   └── backgrounds/         # Background images
├── pages/                    # Additional HTML pages
│   ├── booking.html         # Booking form
│   ├── login.html           # User authentication
│   ├── registration.html    # User registration
│   ├── cars.html            # Car listings
│   └── contact.html         # Contact information
├── php/                      # Backend PHP files
│   ├── config.php           # Database configuration
│   ├── booking.php          # Booking processing
│   └── auth.php             # Authentication handling
└── database/                 # Database files
    └── car_rental.sql       # Database schema
```

## 🚀 Setup and Installation

### Prerequisites

- **Web Server**: Apache/Nginx or XAMPP/WAMP for local development
- **PHP**: Version 7.4 or higher
- **MySQL**: Version 5.7 or higher
- **Modern Web Browser**: Chrome, Firefox, Safari, or Edge

### Installation Steps

#### Step 1: Download and Extract

1. **Clone the Repository**
   ```bash
   git clone https://github.com/YASHRAJ1012108/Car-rental.git
   cd Car-rental
   ```

2. **Extract the Project Archive**
   ```bash
   # Download Online-Car-Rental.zip from the repository
   unzip Online-Car-Rental.zip
   ```

3. **Move to Web Server Directory**
   ```bash
   # For XAMPP (Windows)
   move Online-Car-Rental C:/xampp/htdocs/
   
   # For XAMPP (Linux/Mac)
   mv Online-Car-Rental /opt/lampp/htdocs/
   
   # For WAMP
   move Online-Car-Rental C:/wamp64/www/
   ```

#### Step 2: Database Setup

1. **Start MySQL Server**
   - Start XAMPP/WAMP control panel
   - Start Apache and MySQL services

2. **Create Database**
   ```sql
   -- Access phpMyAdmin (http://localhost/phpmyadmin)
   CREATE DATABASE car_rental;
   USE car_rental;
   
   -- Import the SQL file from database/car_rental.sql
   ```

3. **Configure Database Connection**
   ```php
   // Edit php/config.php with your database credentials
   <?php
   $servername = "localhost";
   $username = "root";
   $password = "";
   $dbname = "car_rental";
   ?>
   ```

#### Step 3: Launch Application

1. **Access the Application**
   ```
   http://localhost/Online-Car-Rental/
   ```

2. **Default Login Credentials** (if provided)
   ```
   Admin: admin@carental.com / admin123
   User: user@example.com / user123
   ```

## 🛠️ Technology Stack

### Frontend Technologies
- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Advanced styling with responsive design
- **JavaScript**: Interactive functionality and DOM manipulation
- **Bootstrap**: Responsive CSS framework
- **jQuery**: JavaScript library for enhanced interactions

### Backend Technologies
- **PHP**: Server-side scripting and business logic
- **MySQL**: Relational database management
- **Apache**: Web server for hosting

### Key Features
- **Responsive Design**: Mobile-first approach with cross-device compatibility
- **User Authentication**: Secure login and registration system
- **Car Booking System**: Complete reservation management
- **Database Integration**: MySQL for data persistence
- **Admin Panel**: Administrative interface for management
- **Search & Filter**: Advanced car search functionality

## 🎯 Features

### User Features
- 🔐 **User Registration & Login**: Secure authentication system
- 🚗 **Car Browsing**: View available cars with detailed information
- 📅 **Booking System**: Reserve cars for specific dates
- 💳 **Payment Integration**: Secure payment processing
- 📱 **Responsive Design**: Works on all devices
- 🔍 **Search & Filter**: Find cars by type, price, location

### Admin Features
- 📊 **Dashboard**: Overview of bookings and revenue
- 🚙 **Car Management**: Add, edit, delete vehicle listings
- 👥 **User Management**: Manage customer accounts
- 📈 **Booking Reports**: Track rental statistics
- ⚙️ **System Settings**: Configure application parameters

## 📱 Usage Guide

1. **Homepage**: Browse featured cars and special offers
2. **Car Listings**: View all available vehicles with specifications
3. **Booking Process**: Select dates, choose car, complete reservation
4. **User Account**: Manage profile and view booking history
5. **Admin Panel**: Administrative functions for system management

## 🔧 Configuration

### Database Configuration
```php
// php/config.php
$host = 'localhost';
$dbname = 'car_rental';
$username = 'root';
$password = '';
```

### Application Settings
- Modify `css/style.css` for custom styling
- Update `js/script.js` for additional functionality
- Configure `php/config.php` for database settings

## 📄 Database Schema

The system includes tables for:
- **users**: Customer account information
- **cars**: Vehicle inventory and specifications
- **bookings**: Rental reservations and status
- **admin**: Administrative user accounts
- **payments**: Transaction records

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/YASHRAJ1012108/Car-rental/issues).

## 👨‍💻 Author & Credits

**YASHRAJ1012108**
- GitHub Profile: [@YASHRAJ1012108](https://github.com/YASHRAJ1012108)
- Repository: [Car-rental](https://github.com/YASHRAJ1012108/Car-rental)
- Portfolio: Multiple web development projects

### Project Details
- **Repository Name**: Car-rental
- **Visibility**: Public
- **Archive Size**: 5 MB
- **Last Updated**: July 2025
- **License**: Open Source

## 🌟 Key Highlights

- ✅ **Complete Car Rental Solution**: Full-featured booking system
- ✅ **Modern Web Technologies**: HTML5, CSS3, PHP, MySQL
- ✅ **Responsive Design**: Mobile-friendly interface
- ✅ **Database Integration**: Robust data management
- ✅ **User Authentication**: Secure login system
- ✅ **Admin Panel**: Comprehensive management interface
- ✅ **Ready to Deploy**: Complete project package

## 📞 Support

For support and queries:
- Create an issue in the repository
- Contact the developer through GitHub

## 📄 License

This project is open source and available under the standard repository terms. All code and assets are provided for educational and demonstration purposes.

---

**Built with ❤️ by [YASHRAJ1012108](https://github.com/YASHRAJ1012108)**

Copyright © 2025 Online Car Rental System. All rights reserved.
