# 📝 To-Do List App

This is a simple web-based To-Do List application built using:
- **HTML**, **CSS**, and **JavaScript** for the frontend
- **Python Flask** for the backend
- **MySQL** for the database

## 🚀 Features

- Add new tasks
- Mark tasks as complete or pending
- Delete tasks
- Store tasks in a MySQL database
- Simple, clean UI

## 🛠️ Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: Python (Flask)
- Database: MySQL
- IDEs: VS Code (for UI), MySQL Workbench

## Setup the virtual environment
- python -m venv venv
- source venv/bin/activate  # On Windows: .\venv\Scripts\activate

## Install dependencies
- pip insiall -r requirements.txt

## Setup MySQL database
CREATE DATABASE todo_db;

USE todo_db;

CREATE TABLE tasks (
    id INT AUTO_INCREMENT PRIMARY KEY,
    task_name VARCHAR(255) NOT NULL,
    task_status BOOLEAN DEFAULT FALSE
);

## Run the Flask app
- python app.py

## Open the browser
- http://127.0.0.1:5000/

![image](https://github.com/user-attachments/assets/81e591fd-eaa2-464c-8f27-24ed8540129b)



