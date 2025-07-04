# Todo List

This is a secure and functional Flask web application built for users to manage their personal todo lists.  It provides core features such as user registration, login, logout, password recovery/reset, and a personalized todo list dashboard where users can add, update, or delete their tasks.  The application ensures data privacy by securing user credentials with password hashing and session-based authentication.


##  Setup & Installation Instructions

```bash
   cd Todo-list
```

 Create a Virtual Environment
```bash
   pip install Virtualenv
   Virtualenv env 
   Set-ExecutionPolicy Unrestricted (run on window powershell) 
   .\env\Scripts\activate.ps1
```

Install Dependencies
```bash
pip install Flask Flask-SQLAlchemy Flask-WTF email-validator
```

Run the Application
```bash
python app.py
```

App will be accessible at: `http://127.0.0.1:5000`


## Flask Version & Dependencies

```txt
Flask==3.1.1
Flask-SQLAlchemy==3.1.1
Flask-WTF==1.2.2
Werkzeug==3.1.3
email-validator==2.2.0
```

Install directly using pip.


## Screenshots

Below is a screenshot of the user dashboard displaying some todo items:
![Dashboard Screenshot](screenshots/screenshots/dashboard.png)


## Project Structure

```
intern_task/
├── app.py
├── models.py
├── templates/
│   ├── login.html
│   ├── register.html
│   ├── forgot_password.html
│   ├── reset_password.html
│   ├── dashboard.html
│   ├── update.html  
├── screenshots/
    ├── dashboard.png
└── db.sqlite3
└── README.md
```


## Authors

Created by Ayushi Singh for Internship Task Submission.


