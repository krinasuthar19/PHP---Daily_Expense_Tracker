# Daily Expense Tracker (DET)

## Overview

Daily Expense Tracker (DET) is a personal financial management web application designed to help users track daily expenses, manage monthly budgets, and visualize spending habits. It provides a clean and efficient interface along with dynamic reporting features for better financial decision-making.

---

## Key Features

### Expense and Budget Management
- Track daily expenses with categories  
- Set monthly budgets for each category  
- Prevent budgets from exceeding total monthly income  

---

### Multi-Month Persistence
- Remembers selected month and year across pages  
- Ensures consistent navigation between dashboard and reports  

---

### Dynamic Category Management
- Add, remove, or reactivate expense categories  
- Categories stored in database (no code changes required)  

---

### Daily Report View
- View transactions for a selected date  
- Pie chart visualization of daily spending  

---

### Analytics and Reporting
- View insights based on:
  - Monthly data  
  - Yearly data  
  - All-time data  
- Interactive charts using Chart.js  

---

### Secure Authentication
- Password encryption using `password_hash()`  
- Secure login verification using `password_verify()`  

---

## Tech Stack

### Backend
- PHP (Native, MySQLi Prepared Statements)

### Database
- MySQL / MariaDB  

### Frontend
- HTML5  
- CSS3  
- JavaScript  

### Libraries and Tools
- Bootstrap 4/5  
- Chart.js  
- Feather Icons  

---

## Database Structure

Main tables used in the system:

- users  
- expenses  
- income  
- budgets  
- expense_categories  

---

## Installation and Setup

### Prerequisites

- XAMPP / WAMP / MAMP  
- PHP and MySQL environment  

---

### Steps to Run

1. Create a database named:

```sql
CREATE DATABASE dailyexpense;
````

2. Configure database connection in `config.php`

3. Create required tables (users, budgets, categories, expenses, income)

4. Place project folder in:

```
htdocs/
```

5. Start Apache and MySQL

6. Open browser and run:

```
http://localhost/project-folder
```

---

## Usage

1. Register a new account
2. Add expense categories
3. Record income
4. Set monthly budgets
5. Track expenses
6. Analyze reports and dashboards

---

## Project Structure

* index.php – Dashboard
* login.php – Login page
* register.php – Registration
* config.php – Database configuration
* add_expense.php – Add expenses
* manage_expense.php – Manage expenses
* income.php – Income tracking
* budget.php – Budget management
* manage_categories.php – Category management
* daily_report.php – Daily analytics
* reports.php – Advanced reports

---

## Use Cases

* Personal expense tracking
* Budget planning
* Financial habit analysis
* Academic and portfolio project

---

## Limitations

* No mobile app support
* No cloud sync
* Limited scalability

---

## Future Improvements

* Add mobile responsiveness improvements
* Integrate real-time sync
* Add export reports (PDF/Excel)
* Implement notifications

---

## Conclusion

This project demonstrates a complete web-based financial tracking system with secure authentication, dynamic data handling, and interactive visualizations. It provides a practical solution for managing personal finances efficiently.

