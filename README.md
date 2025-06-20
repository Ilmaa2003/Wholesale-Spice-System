

# SPICE WORLD – Wholesale Spice Business Management System

**SPICE WORLD** is a custom-developed web application designed to streamline the operations of a wholesale spice distributor. The system supports customer management, product inventory, order processing, invoicing, and delivery coordination with both admin and customer interfaces.

![Wholesale Spice Screenshot](https://raw.githubusercontent.com/Ilmaa2003/Wholesale-Spice-System/main/Images/Screenshot%202025-06-18%20161107.png)

![Wholesale Spice Screenshot](https://raw.githubusercontent.com/Ilmaa2003/Wholesale-Spice-System/main/Images/Screenshot%202025-06-18%20161121.png)

![Wholesale Spice Screenshot](https://raw.githubusercontent.com/Ilmaa2003/Wholesale-Spice-System/main/Images/Screenshot%202025-06-18%20161139.png)

---

## Key Features

- **Invoice Management**  
  Automatically generate and download order invoices.

- **Email Notification System (PHP Mailer)**  
  - Password recovery via email  
  - Auto-responses for customer inquiries

- **Customer Location Access**  
  Integrated Google Maps API for delivery optimization using customer geolocation.

- **Secure Login System**  
  Role-based login access for administrators and customers.

- **User Account Control**  
  Registration, profile updates, and personalized customer dashboard.

- **Product and Order Management**  
  Track stock levels, view products, and manage customer orders.

- **Responsive Web Design**  
  Optimized layout for desktop and mobile users.

- **Search Engine Optimization (SEO)**  
  Structured and optimized for search engine visibility.

- **Administrative Dashboard**  
  Visual overview of orders, clients, and inventory statistics.

---

## Technology Stack

| Component         | Technology           |
|-------------------|----------------------|
| Frontend          | HTML, CSS, JavaScript|
| Backend           | PHP                  |
| Database          | Oracle (SQL Developer) |
| Email Integration | PHP Mailer           |
| Location Services | Google Maps API      |

---

## Installation and Setup

### Prerequisites

- [XAMPP](https://www.apachefriends.org/index.html) or WAMP (for running PHP)
- Oracle Database with SQL Developer
- PHP Mailer (available on [GitHub](https://github.com/PHPMailer/PHPMailer))

### Setup Instructions

1. **Download or Clone the Project**  
   Obtain the source code from your repository or zipped package.

2. **Move to Web Directory**  
   Copy the project folder into your local server path:
```

C:\xampp\htdocs\\

````

3. **Start Local Server**  
- Launch XAMPP and start the Apache service  
- Ensure Oracle Database is active and accessible

4. **Import Database Schema**  
- Open Oracle SQL Developer  
- Run the provided `.sql` file or manually set up tables as described in the report

5. **Configure Application**

- Edit Oracle connection in `config.php`:
  ```php
  $host = 'your_host';
  $port = 'your_port';
  $service_name = 'your_service_name';
  $username = 'your_db_username';
  $password = 'your_db_password';
  ```

- Configure SMTP in your mail scripts:
  ```php
  $mail->Host = 'smtp.example.com';
  $mail->Username = 'your_email@example.com';
  $mail->Password = 'your_email_password';
  ```

6. **Launch the Application**  
Open your browser and visit:


[http://localhost/Wholesale-Spice-System/](http://localhost/Wholesale-Spice-System/)

## Additional Notes

- Ensure that email SMTP credentials are valid. Use Gmail app-specific passwords or enable access for less secure apps if necessary.
- For details on database schema and system logic, refer to the project report included in the documentation.

---

## License

This application was developed for a private client and is not licensed for redistribution or commercial reuse outside the designated organization.



