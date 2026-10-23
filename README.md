# Expense Tracker

A lightweight web app to record income and expenses and see a monthly, category-wise spending breakdown.

**Live demo:** _https://shriram0777.github.io/expense-tracker/_

## Features
- Add income and expense transactions with category, date and note
- Monthly view with income, expense and balance summary
- Category-wise spending chart
- Delete transactions; data persists in the browser (localStorage)
- Responsive layout with light and dark mode, input validation

## Tech stack
HTML, CSS, vanilla JavaScript. No build step or dependencies.

## Run locally
Open `index.html` in a browser, or run `npx serve .`

## Deploy (GitHub Pages)
1. Push this folder to a GitHub repository.
2. Repo **Settings → Pages → Source: Deploy from branch → main / root**.
3. Your site goes live at `https://<username>.github.io/<repo>/`.

## Roadmap
- Backend (Node.js/Express + MongoDB) with JWT authentication
- Export to CSV, budgets per category, multi-month charts
