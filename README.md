SecureLoginMVC

A secure login system built using Python, Flask, and the Model-View-Controller (MVC) architecture. This project demonstrates secure authentication practices, role-based authorization, password hashing, session management, and protection against common web security vulnerabilities.

✨ Features

- 🔐 Secure user authentication
- 🗄️ SQLite database
- 🔑 Password hashing with Werkzeug
- 🛡️ SQL Injection protection using parameterized queries
- 👤 Role-based access control (Admin/User)
- 🍪 Secure session management
- 🎨 Responsive HTML/CSS interface
- 📂 MVC (Model-View-Controller) architecture
- 🚪 Logout functionality
- 📄 Security testing report included

---

📁 Project Structure

SecureLoginMVC/
│
├── app.py
├── config.py
├── create_db.py
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
│
├── controllers/
│   └── auth_controller.py
│
├── models/
│   ├── database.py
│   └── user_model.py
│
├── templates/
│   ├── login.html
│   └── dashboard.html
│
├── static/
│   └── style.css
│
├── database/
│   └── users.db
│
└── Security_Test_Report.md

---

Move into the project directory:

cd SecureLoginMVC

Install the required dependencies:

pip install -r requirements.txt

Create the database:

python create_db.py

Run the application:

python app.py

👥 Default Test Accounts

Administrator

Username: "admin"

Password: "Admin@123"

Standard User

Username: "student"

Password: "Student@123"

---

🔒 Security Features

- Password hashing (Werkzeug)
- Parameterized SQL queries
- Input validation
- Secure session handling
- Role-based authorization
- SQL Injection protection
- Plain-text password prevention
- Error handling
- Secure MVC design

---

🛠️ Technologies Used

- Python 3
- Flask
- SQLite3
- HTML5
- CSS3

---

📋 Security Review

This project demonstrates secure software development practices, including:

- Authentication
- Authorization
- Secure password storage
- Database security
- Input validation
- Session management
- Secure MVC architecture

---

📜 License

This project is licensed under the MIT License.
