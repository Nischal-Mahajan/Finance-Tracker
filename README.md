# Personal-FInance-Tracker


A web-based personal finance management application built with Python and Flask. It allows users to manage their profiles, maintain bank account information, and track financial transactions through a simple and organized interface.

## Overview

Managing personal finances requires keeping track of bank accounts and everyday transactions. Personal Finance Tracker provides a centralized platform where users can manage their financial information and maintain transaction records.

The application uses Flask for backend development, SQLite for database management, and Flask-SQLAlchemy for database interactions.

## Features

### User Authentication
- User registration and login.
- Secure password hashing using Flask-Bcrypt.
- Session management using Flask-Login.
- Protected routes for authenticated users.
- User logout functionality.

### Profile Management
- View personal profile information.
- Update name, email, and mobile number.
- Manage individual user information.

### Bank Account Management
- Add bank account details.
- View registered bank accounts.
- Store bank name, account number, account holder name, and IFSC code.
- Delete bank account records.

### Transaction Management
- Add financial transactions.
- Categorize transactions.
- Record transaction amounts and descriptions.
- View transaction history.
- Edit and delete transactions.
- Maintain user-specific transaction records.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| SQLite | Database |
| Flask-SQLAlchemy | Database ORM |
| Flask-Bcrypt | Password hashing |
| Flask-Login | User authentication and session management |
| HTML5 | Frontend structure |
| CSS3 | Styling |
| JavaScript | Frontend functionality |

## Project Structure

```text
Finance-Tracker/
│
├── app.py
├── models.py
├── requirements.txt
├── app.db
│
├── templates/
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   ├── login.html
│   ├── register.html
│   ├── profile.html
│   ├── edit_profile.html
│   ├── showbank.html
│   ├── addingbankaccount.html
│   ├── financetracker.html
│   └── update.html
│
└── static/
    ├── css/
    ├── js/
    └── images/
```

## Installation and Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Nischal-Mahajan/Finance-Tracker.git
```

### 2. Navigate to the Project Directory

```bash
cd Finance-Tracker
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

For Windows:

```bash
venv\Scripts\activate
```

For macOS/Linux:

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Application

```bash
python app.py
```

### 7. Open in Browser

Visit:

```text
http://127.0.0.1:5000/
```

## Database

The application uses SQLite as its database and Flask-SQLAlchemy as its ORM.

The database manages the following entities:

- **User:** Stores user registration and profile information.
- **Bank:** Stores bank account details associated with users.
- **Transaction:** Stores financial transaction records associated with users.

Database tables are initialized through SQLAlchemy.

## Future Improvements

- Expense analytics and visualization dashboards.
- Monthly and yearly financial reports.
- Budget planning and expense limits.
- Advanced transaction filtering and searching.
- Export transaction history to CSV and PDF.
- Improved security and application validation.

## Author

**Nischal Mahajan**

Computer Science Engineering | Artificial Intelligence

GitHub: [Nischal-Mahajan](https://github.com/Nischal-Mahajan)

## License

This project is available for educational and learning purposes.
