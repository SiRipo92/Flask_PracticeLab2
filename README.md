# Transactions Tracker - CRUD Application

This is a **CRUD (Create, Read, Update, Delete)** application designed for tracking financial transactions, developed as part of the **Hands-on Lab in Module 2** of the **Python "Developing AI Applications with Python and Flask" Course** by **IBM** on **Coursera**.

## Overview

The goal of this project is to build a **financial transaction recording system** using Flask. The system enables users to:

- **Create** new transaction entries
- **Read** and view the list of transactions
- **Update** existing transaction details
- **Delete** transaction entries

## Project Structure

The project follows the standard Flask structure:

### Key Files:

- `app.py`: The main application script that defines the routes and logic for CRUD operations.
- `/templates/`: Contains HTML templates for rendering the pages:
  - `transactions.html`: Displays a list of transactions with options to add, edit, or delete.
  - `form.html`: Contains the form for adding a new transaction.
  - `search.html`: A form to filter transactions based on a range of amounts.
  - `edit.html`: A form for editing an existing transaction.
- `/static/`: Directory for any static assets like CSS or JavaScript files (if applicable).

## Features

- **Create**: Add new transaction entries by specifying a date and amount.
- **Read**: View the list of transactions in a table format.
- **Update**: Edit transaction details (date and amount).
- **Delete**: Remove transactions from the list.
- **Total Balance Calculation**: Display the total balance of all transactions at the bottom of the records table.

## Installation

### Prerequisites

- Python 3.x
- Flask

### Setup

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/transactions-tracker.git
    cd transactions-tracker
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask application:

    ```bash
    python app.py
    ```

4. Open your browser and navigate to `http://127.0.0.1:5000/` to view the application.

## Usage

1. **Add Transaction**: Use the "Add Transaction" form to add new transactions to the system.
2. **View Transactions**: The "Transaction Records" page will show all transactions, and you can edit or delete them.
3. **Edit Transaction**: Click the "Edit" button next to a transaction to update its details.
4. **Search Transactions**: The "Search Transactions" page allows you to filter transactions by specifying a minimum and maximum amount.

## Author(s)

- **Vicky Kuo**: Project lead and primary author.
- **Abhishek Gagneja**: Additional contributor.
- **Sierra Ripoche**: Developer in training for the Full Stack Software Development Specialization Certification

## Course Reference

This project is part of the **"Python Project for AI Application Development"** course offered by IBM on Coursera. You can learn more about the course and its modules by visiting the following link:

[Python Project for AI Application Development - Coursera](https://www.coursera.org/learn/python-project-for-ai-application-development)

## License

© IBM Corporation 2023. All rights reserved.  
This notebook and its source code are released under the terms of the [MIT License](LICENSE).
