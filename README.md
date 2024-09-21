# 📖 Snowy - Book Tracker

**Snowy** is a simple book tracking application that helps you manage your reading. Whether you're an avid reader or just want to keep track of your progress, Snowy allows you to log books, track the number of pages read, and write notes about the book.


## 🎯 Features

- 📚 **Track Books:** Add books to your personal list and keep track of your reading progress.
- ✏️ **Create Posts:** Share your thoughts and updates on books you're currently reading.
- 👤 **User Authentication:** Sign up and log in securely using Flask-Login and Flask-Bcrypt.
- 🎨 **Responsive Design:** Beautifully designed using HTML and CSS, providing a seamless experience across devices.
- 🖼️ **Profile Pictures:** Upload and manage your user profile image (powered by Pillow).


## 🛠️ Technologies

Snowy is built using the following technologies:

- **Flask** - Micro web framework for Python.
- **Flask-SQLAlchemy** - Database management using SQLAlchemy ORM.
- **Pillow** - Image processing for user profile pictures.
- **Flask-WTF** - Forms handling with security.
- **Flask-Login** - User session management.
- **Flask-Bcrypt** - Password hashing for secure user authentication.
- **HTML & CSS** - Frontend design for an intuitive user interface.


## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/KabirCampwala/Snowy.git
   cd snowy
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv snowyVenv
   
   # For Linux/macOS
   source snowyVenv/bin/activate

   # For Windows
   snowyVenv\Scripts\activate
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up the environment variable for Flask:

   
   ```bash
   On Linux/macOS:
   export FLASK_APP=run.py
   
   On Windows:
   set FLASK_APP=run.py
   ```
   
5. Run the application:

   ```bash
   flask run
   ```

Visit `http://127.0.0.1:5000/` to view the application.


## 📂 Project Structure

```
snowy/
│
├── snowy/                # Application package
│   ├── __init__.py       # App and extensions initialization
│   ├── routes.py         # Application routes
│   ├── models.py         # Database models (User, Post)
│   ├── forms.py          # Flask-WTF forms
│   ├── static/           # Static files (CSS, images)
│   └── templates/        # HTML templates
│
├── migrations/           # Database migration scripts
├── snowyVenv/            # Virtual environment
├── run.py                # Application entry point
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```


## 📸 Screenshots

### Signup Page
![image](https://github.com/user-attachments/assets/37dd44fd-e20c-4d0d-a34e-713c9036bcdd)

### Signin Page
![image](https://github.com/user-attachments/assets/58908d9b-9474-44f0-b6bb-e6d94f409375)

### Add New Post
![Add New Post](https://github.com/user-attachments/assets/c0d69db0-92c2-4c4c-95a3-78129f87ebb2)

### Posts Homepage
![Posts Homepage](https://github.com/user-attachments/assets/e3991ce2-836a-403a-abc6-3e8f2bdf83cb)


## 🖥️ Usage

- **Sign Up/Login:** Create an account to start tracking your books.
- **Track Progress:** Add books, update your current page, and add notes to keep track of your reading journey.
- **Share Updates:** Post updates about your reading experience.


With Snowy, keep track of your books and reading goals all in one place! 
Happy reading! 📚✨
