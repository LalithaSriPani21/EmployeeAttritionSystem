# Employee Attrition Prediction and Management System

This project is a Flask-based web application designed to manage employee records and predict attrition risk using machine learning. It provides a user-friendly interface for HR departments to monitor employee details and make data-driven decisions.

## Features

- Authentication System: Admin and user login/registration with session management.
- Employee Management: Add, view, search, update, and delete employee records.
- Attrition Prediction: Input employee details to predict attrition risk using a trained ML model.
- Data Visualization: Graphical analysis of employee attributes like Age, Department, Gender, Job Role, etc.
- Chatbot Interface: Simple Q&A chatbot for HR-related queries.

## Technologies Used

- Frontend: HTML, CSS, Bootstrap
- Backend: Flask (Python)
- Database: SQLite
- Machine Learning: Scikit-learn
- Visualization: Matplotlib, Seaborn

## Project Structure

EmployeeAttritionSystem/
│
├── static/                  # CSS, images
├── templates/               # HTML templates
│   ├── login.html
│   ├── register.html
│   ├── home.html
│   ├── add_emp.html
│   ├── view_emp.html
│   ├── update_emp.html
│   ├── prediction.html
│   └── chatbot.html
│
├── model.pkl                # Trained ML model
├── app.py                   # Main Flask application
├── database.py              # DB operations
├── chatbot.py               # Simple chatbot logic
├── requirements.txt         # Required Python packages
└── README.md                # Project documentation

## Dataset Used

- Name: IBM HR Analytics Employee Attrition Dataset
- Source: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
- Contains features like Age, JobRole, MonthlyIncome, OverTime, etc.
- Used for training a machine learning model to predict employee attrition.

## Future Enhancements

- Add email notification features
- Upgrade chatbot with NLP capabilities
- Include admin dashboard for analytics
- Dockerize the entire application for easy deployment

## Developed By

LalithaSriPani Pothula
