Passport Automation System

📌 Project Overview

The Passport Automation System is a full-stack web application designed to simplify and digitize the passport application process. It allows users to apply for passports, track application status, and enables administrators to verify and manage applications efficiently.

This system reduces manual effort, improves processing speed, and ensures secure handling of applicant data.

Features

User Module

* User Registration & Login (Authentication secured)
* Apply for Passport
* View Application Details
* Track Application Status (Pending / Approved / Rejected)
* Input validation and form handling

Admin Module

* Admin Login
* View all applications
* Verify user details
* Update application status
* Manage applicant records

Security Features

* Authentication-based access control
* Restricted page navigation without login
* Data validation and error handling

Tech Stack

Frontend

* HTML
* CSS
* JavaScript

Backend

* Node.js
* Express.js

Database

* MongoDB

Project Structure


Passport-Automation-System/
│
├── user/
│   ├── UserHomePage.html
│   ├── UserViewDetails.html
│   ├── userlogin.html
│   └── styles/
│
├── admin/
│   ├── AdminHomepage.html
│   ├── Adminlogin.html
│   └── verification.html
│
├── backend/
    ├── server.js
    ├── middleware.js

Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/JaiKrishna1065/passport-automation-system.git
cd passport-automation-system


2️⃣ Install backend dependencies

```
npm install
```

3️⃣ Run the server

```
node server.js
```

4️⃣ Open frontend

* Open HTML files in browser
  OR
* Use Live Server in VS Code


🔄 Workflow

1. User registers and logs in
2. User applies for passport
3. Application stored in database with **"Pending" status**
4. Admin reviews and verifies application
5. Admin updates status (Approved / Rejected)
6. User can track updated status

🎯 Key Highlights

* Full-stack implementation
* Real-world problem solving
* Authentication & authorization
* Database integration
* Clean UI with structured workflow

📜 License

This project is for educational purposes.

👨‍💻 Author

* GitHub: https://github.com/JaiKrishna1065
