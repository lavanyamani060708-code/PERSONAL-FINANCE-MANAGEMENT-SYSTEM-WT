# Personal Finance Management System

A complete frontend-only **Personal Finance Management System** built for a Web Technology college project.

## Technologies

- HTML5
- CSS3
- JavaScript
- Browser localStorage
- Live Server

No React, Node.js, npm, Firebase, database, backend, or package installation is required.

## Folder Structure

```text
Personal-Finance-Management-System/
├── index.html
├── dashboard.html
├── add-transaction.html
├── transactions.html
├── budget.html
├── reports.html
├── goals.html
├── settings.html
├── style.css
├── script.js
└── README.md
```

## How to Run

1. Extract the project ZIP.
2. Open the extracted folder in VS Code.
3. Open `index.html`.
4. Right-click `index.html`.
5. Select **Open with Live Server**.
6. Click **Try Demo Account**.

No terminal commands are required.

## Demo Account

Use the **Try Demo Account** button on the login page.

The demo automatically creates:
- Salary: ₹30,000
- Freelance: ₹5,000
- Food: ₹2,500
- Transport: ₹1,500
- Education: ₹3,000
- Shopping: ₹2,000
- Entertainment: ₹1,000
- Monthly budget: ₹20,000
- Sample savings goal

## Features

### Authentication
- Local registration
- Local login
- Demo login
- Logout

### Dashboard
- Total balance
- Income
- Expenses
- Savings
- Monthly budget
- Remaining budget
- Recent transactions
- Expense summary
- Quick actions

### Transactions
- Add income or expense
- Search
- Type filter
- Category filter
- Delete individual transactions
- Clear all transactions
- Income/expense totals

### Budget
- Monthly budget
- Category budgets
- Progress bars
- Overspending warning

### Reports
- Income
- Expenses
- Savings
- Highest expense category
- Category-wise visual bars
- Income vs expense visual chart
- Monthly spending visual chart

### Goals
- Create savings goals
- Target amount
- Current saved amount
- Target date
- Progress percentage
- Remaining amount
- Delete goals

### Settings
- Name
- Email
- Currency
- Dark mode
- Clear financial data
- Logout

## Data Storage

The application uses browser `localStorage`.

This means:
- Data is saved in the current browser.
- No server is required.
- Data is not sent to an external database.
- Clearing browser storage can remove the project data.

## Navigation

```text
index.html
   ↓
dashboard.html
   ├── add-transaction.html
   ├── transactions.html
   ├── budget.html
   ├── reports.html
   ├── goals.html
   └── settings.html
            ↓
         Logout
            ↓
       index.html
```

## Academic Project Description

The Personal Finance Management System is a client-side web application designed to help users record income and expenses, monitor balances, create budgets, analyze spending patterns, and manage savings goals. The application demonstrates core Web Technology concepts including semantic HTML, responsive CSS, JavaScript DOM manipulation, form validation, event handling, dynamic content generation, browser localStorage, and client-side data processing.

## Important Note

This is an educational frontend project. Since there is no backend or database, the authentication and financial data are stored only in the browser and should not be used for real financial information.
