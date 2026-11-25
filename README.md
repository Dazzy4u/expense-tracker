# Expense Tracker

A simple web app to record your daily expenses and see where your money goes.

**Live app:** https://dazzy4u.github.io/expense-tracker/

## Features

- Add an expense with a name, amount, category and date
- See the total spent for the selected month
- Bar chart showing spending by category
- Filter expenses by month and category
- Delete an expense
- Choose your currency (₹, $, €, £)
- Download all expenses as a CSV file (opens in Excel or Google Sheets)
- Data is saved in your browser, so it is still there when you come back
- Works on phone and computer, with automatic dark mode

## Built with

- HTML
- CSS
- JavaScript (no libraries or frameworks)
- Browser localStorage for saving data
- GitHub Pages for hosting

## How to run it

1. Download or clone this repository.
2. Open `index.html` in any browser.

No installation needed.

## How it works

1. You fill in the form and click **Add expense**.
2. JavaScript saves the expense in a list and stores that list in the browser using localStorage.
3. The page then updates the total, the category bars and the expense list.
4. Changing the month or category filter updates everything again.

## Note

Your data is saved only in the browser you use. If you clear your browser data or open the app on another device, the expenses will not be there. Use **Download CSV** to keep a backup.

## Ideas for the future

- Edit an existing expense
- Set a monthly budget and show a warning when it is reached
- Add a pie chart
- Save data online so it works across devices

## Author

Nishant Bhandral
