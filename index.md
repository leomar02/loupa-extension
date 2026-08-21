---
title: Loupa — see more in every LinkedIn job search
---

<p align="center">
  <img src="assets/icon.png" width="96" height="96" alt="Loupa icon">
</p>

# Loupa

**A lightweight Chrome extension that surfaces the details LinkedIn buries — and lets you sort and filter results without leaving the page.**

Loupa adds compact badges to every job card and a floating toolbar for sorting and
filtering. Everything runs locally in your browser: no accounts, no tracking, no data
ever leaves your machine.

<p align="center"><a href="https://chromewebstore.google.com/detail/loupa/jkijhchgpdafmmalnfneiojdafakjghf"><strong>Install Loupa from the Chrome Web Store →</strong></a></p>

---

## What it does

### Badges on every job card

- **Posted date** — spot stale listings at a glance, or see *No date* when LinkedIn hides it
- **Salary** — in a consistent format (`$95K/yr`, `$45/hr`, `$4,000/mo`), or *No salary* when the listing doesn't give one
- **Workplace type** — Remote, Hybrid, or On-site, as a clear icon
- **Easy Apply** — highlighted so quick-apply roles stand out

![Loupa badges on LinkedIn job cards](assets/hero.png)

### A sort and filter toolbar

A floating rail sits at the edge of the page:

| Control | What it does |
| --- | --- |
| 🕐 Latest first | Newest postings on top; undated ones sink to the bottom |
| 💲↓ / 💲↑ | Sort by salary, high to low or low to high |
| 👁 Unviewed first | Push jobs you've already opened to the bottom |
| 🅰 Hide promoted | Remove sponsored listings entirely |
| 🕐 Hide undated | Hide listings with no posting date |
| ↻ Reset | Back to LinkedIn's original order |

Sorts and filters **combine** — so you can line up exactly what you want to see, such as
unviewed jobs only, promoted listings hidden, highest paying first.

![Loupa sorting LinkedIn results by salary](assets/sort.png)

Salary sorting normalizes pay periods (hourly ≈ 2,080 hrs/yr, monthly × 12) and compares
the top of each range, so an hourly rate is ranked fairly against an annual salary.

---

## What's new

### 1.17.0 — August 2026

- **A "No salary" badge.** Most LinkedIn listings don't post a salary, and until now
  an empty space could mean either "not listed" or "Loupa missed it". Cards without a
  salary now say so outright, in the same muted grey as *No date*.
- **Consistent pay periods.** Listings mix `$4,000/mo`, `$4,000 a month` and
  `$4,000 per month` on the same results page. Every salary badge now reads the same
  compact way — `$95K/yr`, `$45/hr`, `$4,000/mo` — so figures are comparable as you
  scan rather than needing conversion in your head.

### 1.16.0 — August 2026

- First public release on the Chrome Web Store: badges for posted date, salary,
  workplace type and Easy Apply, plus the sort-and-filter rail.

You can check your installed version at `chrome://extensions`. Chrome updates
extensions automatically, usually within a few hours of a release going live.

---

## How it works

Loupa is **visual-only and non-destructive**. Sorting reorders cards on screen using the
CSS `order` property rather than moving anything in the page, so LinkedIn's infinite
scroll and its own behavior keep working exactly as before. Nothing is deleted, saved,
or sent anywhere.

Job cards are found via stable anchors rather than LinkedIn's frequently-changing CSS
class names, which keeps it working across their UI updates.

---

## Privacy

Loupa collects **nothing**. No analytics, no tracking, no cookies, no accounts, and no
network requests of its own. All processing happens locally in your browser.

**[Read the full privacy policy →](privacy.html)**

---

## Support

Having trouble, or spotted a job board layout Loupa doesn't handle?

Please use the **Support** tab on the [Chrome Web Store listing](https://chromewebstore.google.com/detail/loupa/jkijhchgpdafmmalnfneiojdafakjghf) to report it. Including a
screenshot and the search page you were on makes issues much faster to fix.

**Common things to check first:**

- Loupa runs on LinkedIn job pages (`linkedin.com/jobs/…`). It won't appear elsewhere.
- If badges stop appearing after a LinkedIn redesign, reload the page first — the
  extension re-scans automatically as new cards load.
- The toolbar appears once real job cards are on the page, so it won't show on an empty
  or still-loading search.

---

<sub>Not affiliated with, endorsed by, or sponsored by LinkedIn. LinkedIn is a trademark
of LinkedIn Corporation.</sub>
