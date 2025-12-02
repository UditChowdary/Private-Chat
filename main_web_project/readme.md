# Chat Application (PHP + MySQL + JS)

This is a simple web-based chat application built using PHP, MySQL, JavaScript, HTML, and CSS. The system allows users to register, log in, and chat in real-time with others.

## Features

- User authentication (signup/login)
- Real-time chat functionality
- User status (online/offline)
- Search for users
- Responsive design

## Project Structure

- `index.php` - Homepage/login page
- `signup.php`, `login.php` - User authentication pages
- `chat.php` - Main chat interface
- `header.php`, `users.php` - Shared UI and user list
- `style.css` - Styling
- `/javascript/` - JS files for chat interaction and UI behavior
- `/php/` - Backend scripts for login, signup, and chat logic
- `chatapp.sql` - SQL file to create the database and tables

## Setup Instructions

1. Clone or extract this project folder.
2. Import `chatapp.sql` into your MySQL server to create the required database and tables.
3. Update the database connection details in `/php/config.php`.
4. Place the project folder in your web server root (e.g., `htdocs` if using XAMPP).
5. Open your browser and go to `http://localhost/main_web_project`.

## Technologies Used

- PHP
- MySQL
- JavaScript
- HTML/CSS

## How to Use

1. Sign up with your details.
2. Log in with your credentials.
3. Start chatting with other registered users in real time.


