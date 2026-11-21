<h1 align="center">Manual Expense Tracker</h1>
<h3 align="center">Expenses, income and admissions. On your phone, offline.</h3>

<p align="center">
  <a href="https://github.com/Digvijay05/manual-expense-tracker/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/Digvijay05/manual-expense-tracker?label=latest&style=for-the-badge"></a>
  <a href="https://github.com/Digvijay05/manual-expense-tracker/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/Digvijay05/manual-expense-tracker/total?style=for-the-badge"></a>
</p>

An Android app for recording daily expenses, income and admissions in rupees. Everything stays on the phone: no server, no account, and it works without internet.

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

Get the latest APK from **[Releases](https://github.com/Digvijay05/manual-expense-tracker/releases/latest)**.

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

After installing, **Settings → About** shows the app's signing certificate. It must be the same on every update.

## 📝 Changelog

What changed in each version is in the notes of each [release](https://github.com/Digvijay05/manual-expense-tracker/releases).

---

<p align="center">© 2026 Manual Expense Tracker. All rights reserved. Source code is not public.</p>
