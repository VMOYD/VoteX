
# VoteX

A simple web-based **Voting System** built using **PHP, MySQL, HTML, CSS, and JavaScript**. This system allows students to sign up, log in, and cast their votes while providing an admin dashboard for managing candidates and viewing results.

## 📌 Features

- **User Registration & Login** (Student & Admin)
- **OTP Verification** for secure login
- **Voting System** with candidate selection
- **Admin Dashboard** to manage candidates and results
- **Result Display** showing real-time voting statistics
- **Secure Authentication** and session handling

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Server:** XAMPP (Apache & MySQL)

## 📂 Project Structure

```
D:.
│── index.html (Landing Page)
│── Student_SignUP.php (User Registration)
│── Student_Login.php (User Login)
│── OTP_Verification.php (OTP Authentication)
│── voting.php (Voting Page)
│── vote.php (Vote Processing)
│── result.php (Results Page)
│── Admin_Login.php (Admin Login)
│── Admin_Dashboard.php (Admin Panel)
│── Add_Candidate.php (Add Candidate)
│── Connect.php (Database Connection)
│── voting_database.sql (Voting Data)
│── contact.php (Contact Page)
│── logout.php (Logout Functionality)
│── README.md (This File)
│
└─── dashboard/
    ├─── faq.html
    ├─── howto.html
    ├─── images/
    └─── docs/
```

## 🚀 Setup Instructions

1. **Download & Install XAMPP**

   - [Download XAMPP](https://www.apachefriends.org/download.html)
   - Start **Apache** and **MySQL** from XAMPP Control Panel

2. **Clone or Download the Project**

   ```sh
   git clone https://github.com/vmoy/votex
   ```

3. **Move Files to XAMPP htdocs**

   - Copy the project folder to `C:\xampp\htdocs\`

4. **Import the Database**

   - Open **phpMyAdmin** (`http://localhost/phpmyadmin/`)
   - Create a new database: `voting_system`
   - Import `voting_database.sql`

5. **Configure Database Connection**

   - Open `Connect.php` and update the credentials:

   ```php
   $conn = mysqli_connect("localhost", "root", "", "voting_system");
   ```

6. **Run the Project**

   - Open browser and go to:
     ```
     http://localhost/voting-system/
     ```

## 🎯 Usage

- **Students**: Register, verify OTP, log in, and vote.
- **Admin**: Log in to manage candidates and view results.

## 🤝 Contributing

Feel free to fork the repository, raise issues, or submit pull requests.

## 📜 License

This project is open-source under the **MIT License**.

