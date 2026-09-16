Student Attendance Management System

📌 Project Overview

The Student Attendance Management System is a CRUD-based web application developed as part of a college software development activity.

The application helps manage student records and attendance digitally. It provides functionality to Create, Read, Update, and Delete (CRUD) student information through a web-based interface.

🎯 Objectives

- To develop a complete CRUD-based web application.
- To manage student details digitally.
- To provide a simple and user-friendly interface.
- To implement frontend, backend, REST API, and database integration.
- To perform data validation and basic application testing.

🛠️ Technologies Used

Frontend

- React.js
- HTML
- CSS
- JavaScript

Backend

- Python
- Django
- Django REST Framework

Database

- SQLite

Development Tools

- Visual Studio Code
- Git
- GitHub

✨ Features

- Add new student records
- View student records
- Update student information
- Delete student records
- Search and manage student data
- REST API integration
- Database storage using SQLite
- Form validation
- Responsive web interface

🏗️ Project Structure

student-attendance-management/
│
├── backend/
│   ├── config/
│   ├── attendance/
│   ├── manage.py
│   ├── requirements.txt
│   └── .env.example
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── README.md
├── .gitignore
└── LICENSE

🔄 CRUD Operations

Operation| Description
Create| Add a new student
Read| View student information
Update| Modify existing student details
Delete| Remove a student record

🔌 REST API

The backend is implemented using Django REST Framework to provide API endpoints for communication between the frontend and backend.

The API is responsible for:

- Receiving requests from the frontend
- Validating data
- Performing CRUD operations
- Communicating with the SQLite database
- Returning responses to the frontend

🗄️ Database

The project uses SQLite as the database.

Student information is stored and managed through the Django backend and can be accessed through the REST API.

▶️ How to Run the Project

1. Clone the Repository

git clone https://github.com/nithishthirumoorthy07-tech/student-attendance-management22.git

2. Backend Setup

Open the backend folder:

cd backend

Create a virtual environment:

python -m venv venv

Activate the virtual environment.

Windows:

venv\Scripts\activate

Install the required packages:

pip install -r requirements.txt

Run database migrations:

python manage.py migrate

Start the Django development server:

python manage.py runserver

3. Frontend Setup

Open a new terminal and navigate to the frontend folder:

cd frontend

Install dependencies:

npm install

Start the frontend:

npm run dev

The application can then be opened using the local URL displayed by the frontend development server.

🧪 Testing

The application was checked for basic CRUD functionality:

- Student creation
- Student data retrieval
- Student data modification
- Student deletion
- Form validation
- Frontend and backend communication
- Database operations

📚 College Activity

Activity: Complete CRUD-Based Web Application Development

Project: Student Attendance Management System

This project demonstrates the implementation of a complete web application using a React frontend, Django REST Framework backend, REST API communication, and SQLite database.

👨‍💻 Developer

Nithish Thirumoorthy

Electronics and Communication Engineering (ECE)

V.S.B. Engineering College, Karur

📄 License

This project is created for educational and academic purposes.
