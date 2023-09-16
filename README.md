## ExpenseEase

Hello, this is the frontend of my financial assistance app called 'ExpenseEase'. This is a project built using a Next.js 13 frontend and a Django backend. This app offers an abundance of features that serve the purpose of making financial tracking and decision making easier and streamlined for the user.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://127.0.0.1:3000](http://127.0.0.1:3000/) with your browser to see the result.

## Features

- User authentication using Django's built in user authentication system
- Allows users to create and manage their expense and revenue streams
  - Expense and Revenue streams are created and can be editted and deleted using Django REST Framework APIs
  - Expense and Revenue streams created and managed on the frontend through beautiful UI consisting of several pages and other     dynamic components like modals
- Provided users with many options of how their entered finance data can be utilized
  - Users can create financial goals for their expenses and revenue:
    - Set goals for expenses and revenue in categories, such as food, entertained, housing, stocks and trading, etc.
    - Enter budgeting goals to allow users to track their savings in multiple timeframes, such as weekly, biweekly, monthly,         etc.
  - Export data in the form of reports, currently only offered in a pdf format, which can be filed in physical records or used     at financial institutes, such as accounting offices
  - Data can be visualized in graphs, built using Chart.js, such as dynamic and interactive pie and bar graphs

