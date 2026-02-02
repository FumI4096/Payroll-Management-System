# Payroll Management System 

A desktop application for managing employee payroll, leave requests, and attendance tracking built with Python and Tkinter.

## 📖 About

This Payroll Management System provides a user-friendly graphical interface for HR departments to manage employee information, process payroll, track leave requests, and maintain attendance records efficiently.

## 🛠️ Built with

- **Python** - Core programming language
- **Tkinter** - GUI framework for the desktop interface
- **MS SQL Server** - Database for storing employee and payroll data

## 📋 Prerequisites

Before running the application, ensure you have:
- Python 3.x installed
- Tkinter (usually comes pre-installed with Python)
- pip (Python package manager)
- MS SQL Server installed and running
- pyodbc (Python SQL Server connector)

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/FumI4096/Payroll-Management-System.git
cd Payroll-Management-System
```

### 2. Database Setup

1. Ensure SQL Server Management Studio is installed and running
2. Create a new database for the payroll system
3. Update the database connection settings in the source code:
   ```python
   driver = 'your_driver_name'
   server = 'your_server_name'
   database = 'your_database_name
   ```
4. Run any provided SQL scripts to create tables and schema

### 3. Run the Application

```bash
python login.py
```

## 🖥️ Usage

1. **Login**: Start the application and log in with your credentials
2. **Register Employees**: Add new employees to the system
3. **Manage Leaves**: Submit and approve leave requests
4. **Process Payroll**: Calculate and generate employee payroll
5. **Logout**: Safely exit the system

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork this repository
2. Create a feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a Pull Request

## 📝 License

This project is available for educational and personal use.
