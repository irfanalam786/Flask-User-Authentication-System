# 🔐 Flask User Authentication System

A secure **User Authentication System** built using **Flask**, implementing:

* User Registration (Signup)
* User Login
* Password Hashing
* Session-Based Authentication
* Protected Dashboard
* Secure Logout

This project demonstrates backend security fundamentals required in real-world web applications.

---

# 📌 Project Objective

The goal of this project is to implement a secure authentication system where:

* Users can create accounts
* Passwords are securely hashed
* Only authenticated users can access protected routes
* Sessions are properly managed
* Users can safely log out

This reflects real SaaS and enterprise-level authentication workflows.

---

# 🛠 Tech Stack

| Layer              | Technology                |
| ------------------ | ------------------------- |
| Backend            | Python, Flask             |
| Database           | SQLite                    |
| Security           | Werkzeug Password Hashing |
| Frontend           | HTML, CSS                 |
| Session Management | Flask Built-in Sessions   |

---

# 📂 Project Structure

```
flask_auth_project/
│
├── app.py
├── database.db
│
├── templates/
│   ├── register.html
│   ├── login.html
│   └── dashboard.html
│
└── static/
    └── style.css
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/flask-auth-project.git
cd flask-auth-project
```

## 2️⃣ Create Virtual Environment (Recommended)

```
python -m venv venv
```

Activate environment

**Windows**

```
venv\Scripts\activate
```

**Mac/Linux**

```
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```
pip install flask werkzeug
```

---

# ▶️ Run the Application

```
python app.py
```

Open your browser and go to:

```
http://127.0.0.1:5000/register
```

---

# 🔐 Authentication Flow

### 📝 Registration

* User enters username and password
* Password is hashed using `generate_password_hash`
* Data is stored securely in the SQLite database

### 🔑 Login

* User credentials are verified
* Password checked using `check_password_hash`
* Session is created after successful login

### 🛡 Protected Dashboard

* `/dashboard` is accessible only to logged-in users
* Unauthorized users are redirected to login

### 🚪 Logout

* Session is cleared
* User is redirected to login page

---

# 🧠 Security Concepts Implemented

* Password Hashing
* Session-Based Authentication
* Protected Routes
* Secure Logout
* Unique Username Validation

These are fundamental backend security practices used in production applications.

---

# 📸 Screenshots (For Submission)

Include screenshots of:

* Registration Page
* Login Page
* Dashboard Page

---

# 🎓 Learning Outcome

After completing this project, you will:

* Understand authentication systems
* Build secure web applications
* Implement login systems using Flask
* Prepare for backend development interviews

---

# 🚀 Future Improvements

* Role-Based Access Control (Admin/User)
* Email Verification
* Password Reset Feature
* JWT Authentication
* Deploy on Cloud Platforms

---

# 👨‍💻 Author

Your Name
IRFAN ALAM

---

# 📄 License

This project is created for educational and internship purposes.
