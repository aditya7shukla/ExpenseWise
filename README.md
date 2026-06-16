# ExpenseWise
A simple and responsive web-based Personal Expense Tracker that helps users record income and expenses, monitor spending habits, analyze category-wise expenses, and track savings in real time.

## Features

### Income Management
- Add income sources such as salary, freelance work, stipends, etc.
- Record income amount and date.
- Automatically updates financial summaries.

### Expense Management
- Add expenses with:
  - Description
  - Category
  - Amount
  - Payment Method
  - Date
  - Optional Notes
- Edit existing expenses.
- Delete expenses when needed.

### Expense Categories

- Food
- Rent
- Travel
- Entertainment
- Study
- Shopping
- Health
- Other

### Filtering & Search

Filter expenses by:
- Date range
- Category
- Minimum amount
- Maximum amount
- Description or notes keywords

### Financial Summary

The dashboard displays:
- Total Income
- Total Expenses
- Total Savings
- Average Daily Spending
- Average Weekly Spending
- Average Monthly Spending

### Category Breakdown

View spending totals grouped by category for quick analysis.

### Responsive Design

- Mobile-friendly layout
- Modern card-based interface
- Clean and intuitive UI

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

No external libraries or frameworks are required.

---

## Project Structure

```text
personal-expense-tracker/
│
├── index.html
└── README.md
```

---

## Installation

### Option 1: Open Directly

1. Download or clone the project.
2. Open `index.html` in any modern browser.

### Option 2: Run with a Local Server

Using Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## Usage

### Add Income

1. Enter the income source.
2. Enter the amount.
3. Select a date.
4. Click **Add Income**.

### Add Expense

1. Enter expense description.
2. Select a category.
3. Enter amount.
4. Select payment method.
5. Select a date.
6. Add optional notes.
7. Click **Add Expense**.

### Filter Expenses

Use the Filters section to:
- Filter by date range
- Filter by category
- Search descriptions and notes
- Filter by amount range

Click **Apply** to view filtered results.

Click **Reset** to clear all filters.

---

## Calculations

```text
Savings = Total Income - Total Expenses
```

```text
Daily Average   = Total Spending / Active Spending Days
Weekly Average  = Daily Average × 7
Monthly Average = Daily Average × 30
```

---

## Limitations

- Data is stored only in browser memory.
- Refreshing the page clears all records.
- No database integration.
- No authentication system.
- No export/import functionality.

---

## Future Enhancements

- Local Storage support
- User authentication
- Database integration
- Expense charts and analytics
- CSV/Excel export
- PDF reports
- Budget planning
- Recurring transactions
- Dark mode
- Multi-currency support

---



## License

This project is open source and available for educational and personal use.

---

## Author

Aditya Shukla
