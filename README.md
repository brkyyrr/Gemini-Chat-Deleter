# 🧹 Gemini Stubborn Chat Deleter

**Browser Automation Script for Google Gemini (gemini.google.com)**

This script automatically deletes **all chat conversations** from the Google Gemini web interface by simulating real user interactions directly in the browser console.

> ⚠️ **WARNING:** This action is irreversible. Once executed, your Gemini chat history will be permanently deleted.

---

## 🚀 Features

- Built specifically for **Google Gemini**
- Automatically deletes all conversations
- Supports multiple languages (`Delete` / `Sil`)
- Smart UI delays to prevent race conditions
- Forced confirmation fallback using `mat-primary`
- Pure JavaScript (no external dependencies)

---

## 🎯 Use Cases

- Cleaning up large Gemini chat histories
- Resetting conversations on test/demo accounts
- Browser-based UI automation experiments
- Avoiding manual, one-by-one deletions

---

## 🛠 How to Use

1. Go to **https://gemini.google.com**
2. Open **Developer Tools → Console** (`F12`)
3. Paste the script below
4. Press **Enter**
5. The script will delete conversations one by one

---
