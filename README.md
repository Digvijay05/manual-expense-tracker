<h1 align="center">Manual Expense Tracker</h1>
<h3 align="center">Expenses, income and admissions. On your phone, offline.</h3>

<p align="center">
  <a href="https://github.com/Digvijay05/manual-expense-tracker/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/Digvijay05/manual-expense-tracker?label=latest&style=for-the-badge&cacheSeconds=3600"></a>
  <a href="https://github.com/Digvijay05/manual-expense-tracker/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/Digvijay05/manual-expense-tracker/total?style=for-the-badge&cacheSeconds=3600"></a>
  <a href="https://manual-expense-tracker.pages.dev"><img alt="Website" src="https://img.shields.io/website?url=https%3A%2F%2Fmanual-expense-tracker.pages.dev&label=website&style=for-the-badge&cacheSeconds=3600"></a>
</p>

An Android app for recording daily expenses, income and admissions in rupees. Everything stays on the phone: no server, no account, and it works without internet.

🌐 **Website:** [manual-expense-tracker.pages.dev](https://manual-expense-tracker.pages.dev)

## 📱 Screenshots

<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://manual-expense-tracker.pages.dev/screens/home-dark.webp"><img alt="Home: today's net, spending over the last days, and progress toward the month's targets" src="https://manual-expense-tracker.pages.dev/screens/home-light.webp" width="200"></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://manual-expense-tracker.pages.dev/screens/day-dark.webp"><img alt="Day: every expense and admission for a date" src="https://manual-expense-tracker.pages.dev/screens/day-light.webp" width="200"></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://manual-expense-tracker.pages.dev/screens/charts-dark.webp"><img alt="Reports: daily income and expenses chart and running net profit" src="https://manual-expense-tracker.pages.dev/screens/charts-light.webp" width="200"></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://manual-expense-tracker.pages.dev/screens/targets-dark.webp"><img alt="Targets: income and admissions progress for the month" src="https://manual-expense-tracker.pages.dev/screens/targets-light.webp" width="200"></picture>
</p>

## ✨ Features

### 📒 Record
- Quick entry for a day's totals, or itemised entries with a calculator keypad
- Swipe to delete, with undo
- Day view with every entry for that date

### 📊 Understand
- Reports and charts: net profit, expenses, income, investment and returns
- Monthly summary, targets and rolling totals
- Alerts when you cross a target

### 📁 Import and export
- Import from Excel (`.xlsx`) or PDF, with per-row error checks and undo
- Export to Excel or PDF (the PDF carries a CSV copy of your data inside it)

### 🔒 Private
- App lock
- Encrypted backups (AES-256), locked with your own passphrase
- No ads, no tracking, no account

## 📥 Download

Get the latest APK from the **[website](https://manual-expense-tracker.pages.dev)** or from **[Releases](https://github.com/Digvijay05/manual-expense-tracker/releases/latest)**. The website also has a [step-by-step install guide](https://manual-expense-tracker.pages.dev/install).

### Install
1. Download `ExpenseTracker-v<version>.apk` on your phone.
2. Open it from the Files app. The first time, Android asks to allow installs from that app: allow it.
3. If Play Protect warns that the app is unknown, choose **Install anyway**.

### Update
Install the new APK **over** the existing app. **Never uninstall to update**: uninstalling deletes all your data. Back up first (More → Backup → Back up now) and copy the backup file off the phone.

### Verify the download
Every release lists the APK's SHA-256 in a `.sha256` file. On a PC:

```powershell
Get-FileHash .\ExpenseTracker-v1.0.0.apk -Algorithm SHA256
```

Every official release is signed with the same certificate. Its SHA-256 fingerprint is:

```
D8:00:B8:8F:4C:36:EB:F0:94:60:3B:48:40:29:B4:D5:04:33:A4:A4:09:48:24:CD:EC:A3:5C:07:3B:56:B8:09
```

After installing, **Settings → About** shows the app's signing certificate; it must match this. To check an APK before installing, with the Android SDK build tools:

```powershell
apksigner verify --print-certs .\ExpenseTracker-v1.0.9.apk
```

and compare the `certificate SHA-256 digest` line (the same value, without colons). If it ever differs, do not install that APK.

## 📝 Changelog

What changed in each version is in the notes of each [release](https://github.com/Digvijay05/manual-expense-tracker/releases).

---

<p align="center">© 2026 Manual Expense Tracker. All rights reserved. Source code is not public.</p>
