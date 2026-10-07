# Car Rental Portal

A web-based Car Rental Management System developed using PHP and MySQL. The system allows customers to browse available cars, check vehicle details, make rental bookings, and manage their bookings. An administrator can manage vehicles, brands, bookings, users, and other website information through an admin panel.

## Project Overview

The Car Rental Portal provides an online platform for managing car rental operations.

The system has two main modules:

### Customer Module
- User registration and login
- Browse available vehicles
- Search and filter cars
- View vehicle details
- Check vehicle availability
- Book a vehicle
- View booking history
- Manage user profile
- Contact the rental service

### Admin Module
- Admin login
- Dashboard
- Add and manage vehicles
- Manage vehicle brands
- Manage customer bookings
- Manage registered users
- Manage testimonials
- Manage contact information
- Manage website pages and content
- Manage subscribers
- Change admin password

## Technologies Used

### Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript
- jQuery

### Backend
- PHP

### Database
- MySQL

### Development Environment
- XAMPP
- Apache
- phpMyAdmin
- Visual Studio Code

## Main Features

- User authentication
- Admin authentication and authorization
- Vehicle listing and search
- Vehicle availability checking
- Online vehicle booking
- Booking management
- User profile management
- Dynamic website content
- Admin dashboard
- MySQL database integration
- Responsive web interface

## Database

The project uses a MySQL database named:

`carrental`

Important database tables include:

- `admin`
- `tblusers`
- `tblvehicles`
- `tblbrands`
- `tblbooking`
- `tblcontactusinfo`
- `tblcontactusquery`
- `tblpages`
- `tblsubscribers`
- `tbltestimonial`

The database SQL file is available in:

`SQL File/carrental.sql`

## Project Structure

```text
carrental/
│
├── admin/                 # Admin panel
├── assets/                # CSS, JavaScript and images
├── includes/              # Common PHP files and database configuration
├── SQL File/              # Database SQL file
│
├── index.php              # Homepage
├── login.php              # User login
├── signup.php             # User registration
├── car-listing.php        # Vehicle listing
├── vehical-details.php    # Vehicle details
├── check-availability.php # Vehicle availability
├── my-booking.php         # User bookings
├── profile.php            # User profile
├── contact-us.php         # Contact page
└── README.md              # Project documentation

## Requirements

Before running the project, make sure you have:

- XAMPP
- PHP
- MySQL
- A web browser
- Visual Studio Code (recommended)