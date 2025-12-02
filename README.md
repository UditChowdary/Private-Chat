Private Chats – Real-Time Messaging Web App

Private Chats is a lightweight real-time text messaging web application built using HTML, CSS, JavaScript, PHP, and MySQL.
It allows users to sign up, log in, view friends, and chat privately in a clean, simple UI.

🚀 Features
🔐 User System

Sign Up / Create account

Secure Login

Session-based authentication

💬 Private Chat System

One-to-one real-time messaging (AJAX-based)

Chat history saved in database

Friends list with last conversation preview

Conversations UI layout

🖥️ Interface

Login Page

Signup Page

Homepage Blueprint

Conversations section

Friends section

Last message preview

⚙️ Extra Functionality

Settings page

Logout

About Us section

Invite Friends (placeholder)

Text-only messages supported

Work in progress for future expansions

🛠️ Tech Stack

Frontend

HTML

CSS

JavaScript

Backend

PHP

MySQL (chatapp.sql)

Development Tools

Visual Studio Code

XAMPP / WAMP / LAMP for local server

📁 Project Structure
main_web_project/
│── index.php          # Homepage / redirect logic
│── login.php          # Login functionality
│── users.php          # Display list of users/friends
│── chat.php           # Chat screen + messaging logic
│── header.php         # Common UI header
│── style.css          # Application styling
│── javascript/        # JS scripts for updates and chat
│── php/               # Backend helper scripts
│── chatapp.sql        # Database schema
│── readme.md          # Original readme

🗄️ Database Setup

Create a MySQL database named chatapp.

Import chatapp.sql using phpMyAdmin.

Ensure database credentials in PHP match your local server settings.

▶️ How to Run

Copy the project folder into your server directory:

XAMPP → htdocs/

WAMP → www/

Start Apache and MySQL.

Visit:

http://localhost/main_web_project/


Create an account and start chatting inside Private Chats.

📌 Future Improvements

Support for media messages

Message read receipts

Online/offline indicators

Group chats

Modernized UI with animations

Push notifications

👨‍💻 Author

Udit Chowdary
Private Chats Project — 5th Semester
