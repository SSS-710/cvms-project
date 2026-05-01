# CVMS - Company Visitor Management System

A web-based **Visitor Management System** built using **PHP** and **MySQL** that streamlines visitor entry, tracking, and reporting with an admin dashboard and search functionality.

---

## 📋 Features

- **Admin Dashboard** — Quick overview of visitor stats: Today's, Yesterday's, Last 7 Days, and Total Visitors
- **New Visitor Registration** — Add visitors with full name, email, phone, address, whom to meet, department, and reason to meet
- **Manage Visitors** — View all registered visitors with contact details and edit options
- **Visitors Between Dates** — Filter and generate visitor reports by custom date range
- **Search Functionality** — Search visitors by name or mobile number in real time
- **Admin Profile Management** — Update admin name, email, and phone number
- **Change Password** — Secure password update for admin accounts
- **Forgot Password** — Password recovery support

---

## 🛠️ Tech Stack

| Layer      | Technology         |
|------------|--------------------|
| Frontend   | HTML, CSS, JavaScript |
| Backend    | PHP                |
| Database   | MySQL              |
| Fonts      | Poppins (Google Fonts) |

---

## 📁 Project Structure

```
CVMS/
├── css/                        # Stylesheets
├── fonts/poppins/              # Poppins font files
├── images/icon/                # Icons and image assets
├── includes/                   # PHP include files (DB config, header, footer)
├── js/                         # JavaScript files
├── vendor/                     # Third-party libraries
├── admin-profile.php           # Admin profile update page
├── bwdates-reports.php         # Visitor report by date range
├── bwdates-reports-details.php # Detailed report view
├── change-password.php         # Change admin password
├── dashboard.php               # Main dashboard with visitor stats
├── forgot-password.php         # Password recovery
├── index.php                   # Login page
├── logout.php                  # Session logout
└── ...                         # Other pages
```

---

## ⚙️ Installation & Setup

### Prerequisites

- PHP >= 7.x
- MySQL / MariaDB
- Apache or any PHP-compatible web server (e.g., XAMPP, WAMP, LAMP)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/cvms.git
   cd cvms
   ```

2. **Import the database**
   - Open **phpMyAdmin** or your MySQL client
   - Create a new database (e.g., `cvms_db`)
   - Import the provided `.sql` file

3. **Configure database connection**
   - Open `includes/config.php` (or your DB config file)
   - Update the credentials:
     ```php
     define('DB_HOST', 'localhost');
     define('DB_USER', 'your_username');
     define('DB_PASS', 'your_password');
     define('DB_NAME', 'cvms_db');
     ```

4. **Run the project**
   - Place the project folder in your server's root directory (e.g., `htdocs` for XAMPP)
   - Open your browser and navigate to:
     ```
     http://localhost/cvms/
     ```

5. **Login with default admin credentials**
   ```
   Username: admin
   Password: (your configured password)
   ```

---

## 📸 Screenshots

### Dashboard
![Dashboard](screenshots/dashboard.png)

### Add New Visitor
![New Visitor](screenshots/new-visitor.png)

### Manage Visitors
![Manage Visitors](screenshots/manage-visitors.png)

### Admin Profile
![Admin Profile](screenshots/admin-profile.png)

---

## 🔒 Security Notes

- Change the default admin password immediately after setup
- Ensure `includes/` directory is not publicly accessible
- Use HTTPS in production environments

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Shashank Singh Sikarwar**  
GitHub: [@SSS-710](https://github.com/SSS-710)

---

> CVMS © 2018. All rights reserved.<img width="1919" height="904" alt="Screenshot 2026-05-01 181320" src="https://github.com/user-attachments/assets/c6a78e03-8366-4275-9f25-c7b3298a20db" />
