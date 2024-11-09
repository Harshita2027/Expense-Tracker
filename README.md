**Expense Tracker**

**Overview**
Expense Tracker is a simple and stylish web application that allows users to keep track of their income and expenses. Built with a clean, user-friendly interface, this tool helps users better understand their finances and manage transactions efficiently.

**Features**
*Add Transactions*: Users can easily add new income or expense transactions with a description and amount.
*Transaction List*: View all transactions with dynamic styling for income (green) and expenses (red).
*Delete Transactions*: Each transaction can be removed by hovering over the item and clicking the delete button.
*Total Balance Calculation*: Automatically calculates and displays the current balance, total income, and total expenses.
*Local Storage Support*: Saves transactions in local storage, so data persists even after the page is reloaded.
**Technologies Used**
*Frontend*: HTML, CSS, JavaScript
*Local Storage*: Used for persisting transaction data across sessions.
**Design and Styling**
*Responsive Layout*: The app is designed to center the content and make it accessible on any screen size.
*Color Indicators*: Green for income and red for expenses.
*Hover Effects*: The delete button for each transaction only appears when the item is hovered over.
*Custom Shadows*: Box-shadow effects used to enhance visual hierarchy and aesthetics.
**Installation**
*Clone the repository*:

*Copy code*
git clone https://github.com/Harshita2027/Expense-Tracker.git
cd Expense-Tracker
Open index.html: Open the index.html file in your browser to start using the application.

**Code Overview**
*HTML (index.html)*
Balance and Summary Section: Displays the total balance, income, and expenses.
Transaction Form: Input fields to add new transactions with a description and amount.
Transaction List: Displays each transaction with color-coded styling.
*CSS (style.css)*
Variables: Custom properties for shadow effects to enhance styling.
Flexbox Layout: Used for centered, responsive design.
Styled Components:
.money-plus: Green color for positive values.
.money-minus: Red color for negative values.
.delete-btn: Hover-activated delete button to remove transactions.
*JavaScript (script.js)*
Add Transaction: Functionality to add a transaction, update the display, and save data to local storage.
Delete Transaction: Allows users to remove transactions from the display and local storage.
Dynamic Balance Update: Calculates total balance, income, and expenses and updates the display.
**Usage**
Add a Transaction: Enter a description and amount for each income or expense.
Click "Add Transaction" to save it.
View and Delete Transactions: The transaction will appear in the history list.
Hover over the transaction to reveal the delete button, and click it to remove the item.
