Expense Tracker Web Application

A full-featured Expense Tracker web application built using Python and Streamlit.
The application allows users to securely manage income, expenses, budgets, and financial insights through an interactive dashboard with persistent database storage.

Key Features

Secure user authentication with encrypted passwords
Interactive dashboard showing total income and expenses
Expense and income management with categories
Budget creation and progress tracking
Data visualization with charts
Basic expense prediction module
CSV import/export support
Multi-database storage using SQLite
User-friendly Streamlit UI with sidebar navigation

 Application Modules
 
Dashboard – Overview of income, expenses, and budget progress
Your Income – Add and manage income entries
Your Expenses – Track expenses by category and date
Set Budgets – Define category-wise budgets
Manage Entries – Edit or delete financial records
Trash – Soft-deleted records management
Charts – Visual representation of financial data
Prediction – Basic expense prediction using historical data
Settings – Currency, email, and application preferences

Tech Stack (Used in This Project Only)
Python – Core backend logic
Streamlit – Web UI and application framework
SQLite – Database storage
Pandas – Data processing and analytics
NumPy – Numerical operations
Plotly Express – Interactive charts and graphs
bcrypt – Secure password hashing
SMTP (smtplib) – Email configuration support
CSV – Data import/export

Project Structure
Copy code

expense_tracker/

│
├── app.py        # Main Streamlit application

├── users.db               # User authentication database

├── expense.db             # Expense records

├── budget.db              # Budget data

├── finance.db             # Financial summaries

├── expenses.csv           # CSV export/import

├── receipts/              # Stored receipt files

├── .venv/                 # Virtual environment

└── README.md              # Project documentation

(Database files may vary based on runtime usage)

Security Implementation

Passwords are securely hashed using bcrypt

No plain-text credential storage
Session-based user authentication using Streamlit session state

Data & Analytics

SQLite databases for structured data storage
Pandas used for:
Expense aggregation
Budget calculations
Summary analytics
Plotly Express used for visual insights

How to Run the Project

Clone the repository
git clone https://github.com/your-username/expense-tracker.git

Install dependencies

pip install -r requirements.txt

Run the application

streamlit run app.py

Open in browser
http://localhost:8501

Project Objective

This project demonstrates:
Real-world Python application development
Secure authentication and database integration
Financial data tracking and visualization
Clean UI/UX design using Streamlit
Practical problem-solving with structured data

Future Enhancements

Advanced ML-based expense prediction
Monthly & yearly financial reports
Cloud database integration
Multi-currency support
Role-based user access

👤 Author
Udit

Python Developer | Software Engineering Student
