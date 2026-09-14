# Job Tracker

## 📌 Project Description

**Job Tracker** is a web-based application developed using **Python, Django, HTML, CSS, and SQL** to help users efficiently manage and track their job applications in one place.

The application allows users to maintain a centralized record of jobs they have applied for and keep track of important information such as the company, job title, application status, applied date, and other relevant details.

The project is designed to simplify the job-search process by providing an organized and easy-to-use interface for managing multiple job applications.

## 🚀 Key Features

- Add new job applications
- View a list of all job applications
- Edit existing job information
- Delete job applications
- Track application status
- Sort job listings
- Store job-related information in a SQL database
- User-friendly Django-based web interface
- Dynamic data handling using Django views and templates

## 🛠️ Technologies Used

- **Python** – Backend programming
- **Django** – Web application framework
- **SQL / PostgreSQL** – Database management
- **HTML** – Page structure
- **CSS** – Styling and layout
- **Django Templates** – Dynamic web pages

## 📂 Project Structure

```text
JobTracker/
│
├── manage.py
├── db.sqlite3 / PostgreSQL Database
│
├── project/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── jobs/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── admin.py
│   └── templates/
│
└── static/
    ├── css/
    └── js/
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone <repository-url>
cd JobTracker
```

### 2. Create a Virtual Environment

```bash
python3 -m venv venv
```

Activate it:

**macOS/Linux:**

```bash
source venv/bin/activate
```

**Windows:**

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure the Database

Update the database configuration in `settings.py` according to your SQL/PostgreSQL setup.

Then run:

```bash
python3 manage.py makemigrations
python3 manage.py migrate
```

### 5. Create a Superuser

```bash
python3 manage.py createsuperuser
```

### 6. Start the Development Server

```bash
python3 manage.py runserver
```

Open the application in your browser at:

```text
http://127.0.0.1:8000/
```

## 🎯 Purpose of the Project

The main purpose of this project is to provide a simple and structured solution for managing job applications while also demonstrating practical implementation of:

- Django MVC/MVT architecture
- Database integration
- CRUD operations
- Django models and forms
- Class-Based Views
- URL routing
- Template rendering
- Sorting and filtering data

## 🔮 Future Improvements

Some possible improvements for future versions include:

- User authentication and registration
- Dashboard with application statistics
- Search and advanced filtering
- Job application reminders
- Interview tracking
- Resume management
- Email notifications
- Application status analytics
- REST API integration

## 👨‍💻 Author

Developed as a Django/Python web development project for managing and tracking job applications.
