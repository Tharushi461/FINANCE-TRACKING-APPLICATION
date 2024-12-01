# Personal Finance Tracker
This is a personal finance tracker application that allows you to manage and visualize your income and expenses over time. It supports adding transactions, viewing summaries, and generating plots to analyze your spending habits.

# Features
Add New Transaction: Allows the user to input transaction details such as date, amount, category (Income/Expense), and description.
View Transactions: Retrieve transactions within a specified date range and display a summary including total income, total expenses, and net savings.
Plot Transactions: Visualize income and expenses over time with a plot showing the trends.
# Requirements
Python 3.x
pandas
matplotlib
CSV file for storing transactions (finance_data.csv)
# Setup
Install Required Libraries: Ensure that you have Python installed and the required libraries by running:

#  bash
Copy code
pip install pandas matplotlib
Create the CSV File: The application will automatically create a finance_data.csv file if it doesn’t exist, which will store all transaction data.

# Usage
Run the Application
To start the application, run the following command in your terminal:

bash
Copy code
python main.py
Main Menu
You will be presented with the following options:

Add a New Transaction: Enter the details for a new transaction (date, amount, category, description).
View Transactions and Summary: Enter a date range (start and end date) to view transactions within that range, along with a summary of total income, expenses, and net savings.
Exit: Close the application.
Transaction Details
When adding a transaction, you will be asked for the following details:

Date: The date of the transaction (you can leave it empty to use today's date).
Amount: The amount of the transaction.
Category: Whether it is "Income" or "Expense".
Description: A short description of the transaction.
Plotting Transactions
If you choose to plot the transactions, the program will generate a graph showing your income and expenses over time. The graph is displayed using matplotlib.

# Example
Adding a Transaction:
mathematica

Enter the date of the transaction (dd-mm-yyyy) or enter for today's date: 
Enter the amount: 200
Enter the category (Income/Expense): Income
Enter a short description: Freelance Work
Viewing Transactions and Summary:
vbnet

Enter the start date (dd-mm-yyyy): 01-01-2024
Enter the end date (dd-mm-yyyy): 31-12-2024
Transactions from 01-01-2024 to 31-12-2024
Date       Amount Category Description
01-01-2024 200    Income    Freelance Work

# Summary:
Total Income: $200.00
Total Expense: $0.00
Net Savings: $200.00
Plot Example:
A plot of income and expenses over time will be shown, with the income shown in green and the expenses in red.

# File Structure
bash

finance_tracker/
├── main.py               # Main script to run the application
├── data_entry.py         # Helper functions for getting user inputs
├── finance_data.csv      # CSV file to store transactions
├── README.md             # Project documentation
└── requirements.txt      # Required Python libraries
Contributing
Feel free to fork this project, open issues, or create pull requests for improvements. All contributions are welcome!

