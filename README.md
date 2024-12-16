Expense Tracker

Overview

The Expense Tracker is a simple Python console application that helps users track their expenses by adding, viewing, and analyzing their spending habits. It allows users to categorize expenses, view the total expenditure, and filter expenses by specific categories.

Features

Add Expenses: Record an expense by specifying the amount and category.

View All Expenses: Display a list of all recorded expenses with details.

Calculate Total Expenses: Summarize the total amount spent across all expenses.

Filter Expenses by Category: View expenses filtered by a specific category.

Exit: Close the application.

How It Works

The application uses a Python list to store expenses as dictionaries.

Each expense record contains:

amount: The monetary value of the expense (a float).

category: A string representing the category of the expense.

The application provides a menu-driven interface for user interaction.

Requirements

Python 3.x

How to Run

Clone or download the project files.

Open a terminal and navigate to the directory containing the expense_tracker.py file.

Run the program using the following command:

python expense_tracker.py

Follow the on-screen prompts to add, view, or analyze expenses.

Code Structure

add_expense(expenses, amount, category): Adds an expense to the list.

print_expenses(expenses): Displays all expenses in a readable format.

total_expenses(expenses): Calculates the total amount of all expenses.

filter_expenses_by_category(expenses, category): Filters expenses by the specified category.

main(): The main function that drives the program's menu system.

Example Usage

Add an Expense:

Enter the amount: 50.75

Enter the category: Food

View All Expenses:

Amount: 50.75, Category: Food

Calculate Total Expenses:

Total Expenses: 50.75

Filter Expenses by Category:

Enter the category: Food

Expenses for Food:
Amount: 50.75, Category: Food

Future Improvements

Add persistent storage (e.g., using a database or a file) to save expenses.

Implement a graphical user interface (GUI).

Add expense editing and deletion functionality.

Generate reports for specific time periods.

License

This project is licensed under the MIT License. Feel free to use and modify it.
