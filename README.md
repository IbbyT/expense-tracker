# Expense Tracking Application

This is a simple command-line application for tracking and summarizing expenses using SQLite. The application allows you to enter new expenses, view expenses, and get a summary by category and date.

## Features

- **Add New Expenses:** Enter details of a new expense including date, description, category, and price.
- **View Expenses:** View a list of all expenses or get a summary of expenses by category for a specific month and year.
- **Category Management:** Select from existing categories or create new ones.

## Requirements

- Python 3.x
- SQLite (comes pre-installed with Python)

## Usage

1. **Run the Application:**
   ```bash
   python expense_tracker.py
2. Choose an Option:
   - 1. Enter a new expense: Add a new expense with details.
   - 2. View expenses summary: Get a summary of expenses by category and date.

3. Entering a New Expense:
- Enter the date of the expense in the format YYYY-MM-DD.
- Enter a description of the expense.
- Choose an existing category or create a new one.
- Enter the price of the expense.

4. Viewing Expenses Summary:
- 1. View all expenses: Display all expenses stored in the database.
- 2. View monthly expenses by category: Provide the month and year to see the total expenses for each category.
 
## Code Overview
- Database Connection: Connects to an SQLite database named expenses.db.
- Table Creation: Creates a table expenses if it does not already exist.
- Expense Entry: Prompts the user to enter details of an expense and stores it in the database.
- Expense Summary: Allows the user to view all expenses or get a summary of monthly expenses grouped by category.
