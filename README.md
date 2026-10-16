[README-DEPLOY.md](https://github.com/user-attachments/files/33544631/README-DEPLOY.md)
# CashFlow Buddy — beginner deployment guide

## What's included
- `index.html`: complete single-file app (HTML, CSS, and JavaScript)
- Local browser storage; no server or API key required
- Add/edit/delete transactions, mark income received / expenses paid, recurring rules, 30/60/90-day forecast, chart, CSV export
- Demo data is preloaded on first open

## Test it on your computer
1. Download and unzip `cashflow_buddy.zip`.
2. Open the `index.html` file in Chrome, Edge, or Firefox.
3. Try adding an income and an expense.
4. Refresh the page: data should still be there in the same browser.

## Deploy free with GitHub Pages
1. Create or sign in to a GitHub account at https://github.com.
2. Click **New repository** and name it `cashflow-buddy`. Choose **Public** for the simplest GitHub Free setup.
3. Click **Create repository**.
4. Inside the repository, choose **Add file → Upload files**.
5. Upload `index.html` from this folder and click **Commit changes**.
6. Open the repository's **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Choose branch `main` and folder `/ (root)`, then click **Save**.
9. Wait a few minutes and refresh the Pages settings. Click **Visit site** when the link appears.

Your URL will look like `https://YOUR-USERNAME.github.io/cashflow-buddy/`.
GitHub's documentation says publication may take up to 10 minutes: https://docs.github.com/en/pages/quickstart

## Important limitations
- This is a prototype, not a production-ready SaaS.
- Data is stored only in the current browser/device. Clearing browser data can erase it; there is no account login, cloud sync, or multi-user separation.
- Don't enter sensitive business financial data in the prototype.
- Recurring rules create forecast occurrences; mark completed payments carefully to keep your records accurate.
- GitHub Pages publishes a public website. Never upload customer data, secrets, or API keys to the repository.
- Monthly subscriptions, secure user accounts, cloud database, and server-side access controls are not included yet.

## Suggested next stage
Validate with 3–5 test users using dummy or non-sensitive data. If people will pay, add authentication and a secure hosted database before offering this to multiple customers.
