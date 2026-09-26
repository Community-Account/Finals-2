# Budget Tracker System

This is a simple Budget Tracker made with HTML and JavaScript.

## What it does

- Add a budget amount
- Add expenses (title + amount)
- Remove an expense
- Show total budget, total expenses, and budget left
- Reset everything
- Saves data in localStorage so it stays after refresh

## Files

- index.html - the page structure
- script.js - all the logic

## How to run

1. Download both files and keep them in the same folder.
2. Open index.html in your browser.
3. Start adding budget and expenses.

## How it works

- Budget and expenses are stored in variables.
- When you add data, it is also saved in localStorage using JSON.stringify.
- When the page loads, saved data is loaded back using JSON.parse.
- The expense table is updated every time you add or remove an expense.

## Notes

- No CSS is used, so it looks plain.
- Code is written in simple JavaScript (var, functions, loops) for practice.
