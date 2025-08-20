Personal Finance Tracker

A comprehensive command-line application for tracking income and expenses with powerful visualization capabilities.

Features

*Transaction Management: Add new income and expense entries with flexible date input
*Financial Reporting: View transactions and financial summaries for any date range
*Data Visualization: Generate line charts to visualize income and expenses over time
*CSV Storage: All data is stored in a persistent CSV file for easy access and backup
*Input Validation: Robust validation for dates, amounts, and categories

Installation 

Ensure you have Python 3.7+ installed on your system
Clone or download the project files
Install required dependencies:
pip install -r requirements.txt

Usage

Run the application:
python main.py

Main Menu Options

Add a new transaction

Enter transaction date (or press Enter for today's date)
Input amount (positive decimal values only)
Select category (I for Income, E for Expense)
Add an optional description
View transactions and summary

Specify a date range (start and end dates in dd-mm-yyyy format)
View all transactions within the range
See financial summary including total income, expenses, and net savings
Option to visualize data with a line chart

Exit - Close the application

Data Format

Transactions are stored in finance_data.csv with the following columns:
date: Transaction date in dd-mm-yyyy format
amount: Transaction amount as a decimal value
category: Either "Income" or "Expense"
description: Optional text description

Example Usage

1. Add a new transaction
2. View transactions and summary within a date range
3. Exit
Enter your choice (1-3): 1

Enter the date of the transaction (dd-mm-yyyy) or enter for today's date: 15-08-2024
Enter the amount: 250
Enter the category ('I' for Income or 'E' for Expense): I
Enter a description (optional): Freelance payment
Entry added successfully

Technical Details

Built with Python 3.7+
Uses pandas for data manipulation and analysis
Implements matplotlib for data visualization
Features comprehensive input validation and error handling
Follows object-oriented design principles with a dedicated CSV handler class

Requirements

pandas >= 1.0.0
matplotlib >= 3.0.0

