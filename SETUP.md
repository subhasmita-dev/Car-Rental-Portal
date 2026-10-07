# Car Rental Portal - Setup Guide\

This guide explains how to run the Car Rental Portal locally using XAMPP.

# 1. Install XAMPP\

Install XAMPP on your Windows computer.
The project uses:

\- Apache\
\- MySQL\
\- PHP\
\- phpMyAdmin\

# 2. Start XAMPP\

Open the XAMPP Control Panel.

Start:

\- Apache
\- MySQL

Both services should show as running.

# 3. Place the Project

Copy the project folder into the XAMPP \`htdocs\` directory:\

\`\`\`text\
C:\xampp\htdocs\carrental



## 4. Create the Database

1. Open phpMyAdmin:
```
http://localhost/phpmyadmin
```

2. Create a new database named:
```
carrental
```

## 5. Import the Database

1. Select the `carrental` database in phpMyAdmin.
2. Open the **Import** tab.
3. Select the SQL file:
```
SQL File/carrental.sql
```

4. Click **Import** or **Go**.
5. Wait for the import to complete successfully.

## 6. Check Database Configuration

The database connection is configured in:
```
includes/config.php
```

Make sure the database name and MySQL settings match the local XAMPP configuration.

## 7. Run the Project

After starting Apache and MySQL, open a browser and visit:
```
http://localhost/carrental/
```

The Car Rental Portal homepage should appear.

## 8. Access the Admin Panel

The administrator panel can be accessed at:
```
http://localhost/carrental/admin/
```

## 9. Demo Login Credentials

### Customer
```
Email: test@gmail.com
Password: Test@123
```

### Administrator
```
Username: admin
Password: Test@12345
```

> These credentials are provided for the local/demo version of the project.

## 10. Troubleshooting

### Apache is not running

Make sure Apache is started from the XAMPP Control Panel.

### MySQL is not running

Start MySQL from the XAMPP Control Panel.

### Database connection error

Check that:

- MySQL is running.
- The database is named `carrental`.
- The SQL file has been imported.
- `includes/config.php` contains the correct database configuration.

### Website is not opening

Make sure the project is located at:
```
C:\xampp\htdocs\carrental
```

and Apache is running.

Then open:
```
http://localhost/carrental/
```

### Admin panel is not opening

Make sure you are using:
```
http://localhost/carrental/admin/
```

## 11. Stopping the Project

When finished:

1. Open the XAMPP Control Panel.
2. Stop Apache.
3. Stop MySQL.

The project files will remain in the `htdocs` folder.
