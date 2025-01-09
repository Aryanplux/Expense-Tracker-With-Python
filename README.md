Expense Tracker with Python

Overview

This project is an Expense Tracker built using Python. It helps users manage their expenses by categorizing them and calculating totals. A key focus of the project is understanding and implementing Lambda functions to create concise and functional code.

Features

Add expenses with amounts and categories.

Display a list of all expenses.

Calculate the total amount of expenses.

Leverage Python's Lambda functions for clean and efficient operations.

Key Concepts

Lambda Functions

A Lambda function in Python is a small anonymous function defined using the lambda keyword. These functions are used throughout the project to simplify operations, such as extracting values from dictionaries and performing calculations.

Example:

# Lambda function to extract the 'amount' key from an expense dictionary
lambda expense: expense['amount']

Python's map() and sum()

map(): Applies a function to all items in an iterable (e.g., a list).

sum(): Calculates the total sum of all numeric values in an iterable.

Project Structure

app.py: The main script containing all the functions for managing expenses.

README.md: This file, providing an overview of the project.

Usage

Adding an Expense

Use the add_expense() function to add an expense to the tracker. Each expense includes an amount and a category.

Example:

expenses = []
add_expense(expenses, 50, 'Food')
add_expense(expenses, 20, 'Transport')

Printing Expenses

Use the print_expenses() function to display all expenses.

print_expenses(expenses)

Calculating Total Expenses

Use the total_expenses() function to calculate the total amount spent.

print(total_expenses(expenses))

Installation

Clone the repository:

git clone https://github.com/your-username/expense-tracker.git

Navigate to the project directory:

cd expense-tracker

Run the script:

python app.py

Learning Outcomes

How to use Python dictionaries and lists to manage data.

The power of Lambda functions for writing concise and readable code.

Leveraging Python's built-in functions like map() and sum().

Future Enhancements

Add functionality to delete or update expenses.

Store expenses persistently using a database or a file.

Build a graphical user interface (GUI) for easier interaction.

Contributing

Contributions are welcome! Feel free to fork the project and submit pull requests.



