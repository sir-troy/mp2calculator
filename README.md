# MP2 Calculator (Unofficial)

**Version 1.0**

A simple, mobile-friendly calculator that estimates how much your Pag-IBIG MP2 savings could grow in 5 years. It's in English and Tagalog.

> **Disclaimer:** This project is **not** associated with, endorsed by, or operated by Pag-IBIG Fund (HDMF). It only gives estimates. For official information, visit [pagibigfund.gov.ph](https://www.pagibigfund.gov.ph).

## Features

- **Same amount every month:** enter a monthly amount and an optional one-time deposit.
- **My own amounts:** a 5-year table where you type a different amount for each month, or leave months blank.
- Dividends either kept in (compounded) or paid out yearly.
- A year-by-year chart and table, with a "Copy my results" button.
- Sections on MP2 perks, how MP2 works and how to start, plus 17 FAQs.
- English and Tagalog.
- **Privacy:** nothing the visitor types is saved or sent. All math runs in the browser.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole website: layout, styles and calculator, in one file. |
| `rates.txt` | The MP2 dividend rates. **This is the file you update every year.** |
| `README.md` | This guide. |

## Updating the dividend rate

Pag-IBIG Fund usually announces the new MP2 rate once a year, around **late February to March**.

1. Open `rates.txt` on GitHub and click the pencil icon (Edit).
2. Add a new line at the bottom, for example: `2026 = 7.20`
3. Click **Commit changes**.

The site picks up the newest year as the "Latest" rate on the next visit. The top of `rates.txt` explains where to find the official rate.

## Hosting on GitHub Pages

1. Go to the repository's **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose the **main** branch and the **/ (root)** folder, then click **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Notes

- Likes, view counts and the feedback form only work on the claude.ai version of this page. On GitHub Pages they are hidden automatically.
- The calculator assumes deposits at the start of each month and applies the yearly rate to the average monthly balance. Pag-IBIG's actual figures may differ slightly.

## Changelog

- **v1.0** (November 2026): first release.

© 2026 MP2 Calculator. All rights reserved. Pag-IBIG Fund and MP2 are names of the Home Development Mutual Fund, used here only for reference.
