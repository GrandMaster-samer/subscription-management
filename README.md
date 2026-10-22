# Subscription Tracker

A simple web page for tracking customer subscriptions: who is subscribed, which package, how much they pay, and when it expires. It highlights subscriptions that are due soon or already expired, so renewals are not forgotten.

It is a single `index.html` file with no libraries and no server. Built with HTML, CSS and JavaScript.

> The names and data in the demo are made-up samples. Do not enter real customers' personal information if you publish your own copy online.

## Features

- Add subscriptions with customer name, package, monthly price and expiry date
- Automatic status for each subscription: active, due within 7 days, or expired
- One-click **Renew 1 month** (renews from today if already expired, otherwise from the current expiry date)
- Filter by status, and search by name or package
- Monthly income total for subscriptions that have not expired
- Export everything to a CSV file that opens in Excel or Google Sheets
- Data is saved in your browser (`localStorage`), so it stays after you close the page

## How to use

1. Open `index.html` in a browser, or visit the live page (see below).
2. Fill in the form and press **Add subscription**.
3. Use the boxes at the top to filter, and the buttons on each row to renew or delete.

## Run it online with GitHub Pages

In the repository go to **Settings → Pages**, choose the `main` branch and the root folder, then save. The page will be available at `https://GrandMaster-samer.github.io/subscription-management/`.

## Notes

- Data is stored only in the browser you use. Clearing the browser data, or opening the page on another device, starts again with the sample data.
- Dates are handled in local time. Renewing on the 31st moves to the last day of shorter months.

## License

MIT. See the `LICENSE` file.
