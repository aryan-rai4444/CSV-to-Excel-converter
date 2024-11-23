# Aryan Rai
# 590015527
# Expense-calculator
![](I1.png)
This Python code defines a simple Expense Tracker application using the Tkinter library for the graphical user interface (GUI) and Pandas for data handling. The application allows users to record, view, and delete expense entries in a structured format.

### Key Components:
1. *File Management*: It uses a CSV file (expenses.csv) to save and load expenses. When the application starts, it loads existing data from this file, or if the file doesn’t exist, it creates an empty DataFrame to store expense records.

2. *Adding Expenses*: The add_expense function allows users to input details (date, category, amount, and description) for a new expense. It validates entries, converts the amount to a numeric type, adds the entry to the DataFrame, and saves it to the CSV file. After saving, it updates the display and clears input fields.

3. *Deleting Expenses*: The delete_expense function lets users select and remove an expense from the displayed list. It removes the selected entry from the DataFrame, updates the file, and refreshes the list display.

4. *GUI Setup*:
   - Text entry fields let users input expense details, with a "Set Today's Date" feature for convenience.
   - Buttons are provided for adding and deleting expenses.
   - A list box displays all recorded expenses for easy review.

5. *User Feedback*: The app uses messagebox to show success or warning messages based on user actions, enhancing user experience and handling input errors effectively.

6. *Auto-Population*: Upon startup, the app loads and displays existing expenses in the list box, ensuring all entries are visible for quick access.

This expense tracker is a functional, easy-to-use app for basic personal finance management, designed to be user-friendly and informative with real-time updates and feedback.
