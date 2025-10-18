# 🪐 WhatsApp Web group Member Extractor

A lightweight browser script that automatically extracts **names, phone numbers, and group names** from WhatsApp Web groups — directly into a CSV file.

It includes a live overlay with full control (Pause / Play / Stop / Download), real-time progress, timer, and adjustable smooth scrolling.

---

## 🚀 Features

| Feature | Description |
|----------|-------------|
| 🕒 Smooth Auto Scroll | Continuously scrolls through the WhatsApp group member list in real time |
| 📞 Name + Number Capture | Extracts both names and numbers — even those without a saved contact name |
| 📋 Group Detection | Automatically detects and logs the current group name |
| ⏸ ▶ ⏹ ⬇ Controls | Pause, Play, Stop, and Download buttons built right into the overlay |
| ⚡ Adjustable Speed | Change scroll speed in real time (1–5 px/frame) |
| 🧾 CSV Export | One-click CSV download of all collected members |
| 🟢 Resume Support | Continue extraction after pausing, without losing progress |
| ⏱ Timer | Tracks total elapsed time and scroll cycles |

---

## 🧠 How It Works

This script runs **entirely client-side** on WhatsApp Web.  
It scrolls through the “View all participants” panel, continuously parsing the visible DOM to detect names and phone numbers.

When finished (or anytime you wish), you can download the results as a `.csv` file — ready for Excel or Google Sheets.

---

## ⚙️ Setup & Usage

1. Open **[WhatsApp Web](https://web.whatsapp.com)** on your browser.  
2. Open any group and click **“View all participants.”**
3. Press `F12` (or right-click → Inspect → Console tab).
4. Paste the full script below into the console and hit **Enter**.
5. A floating overlay box will appear on the top-right corner of your screen.
6. Click **▶ Play** to start auto extraction.

---

## 🧩 Controls Overview

| Button | Action |
|---------|--------|
| ▶ **Play** | Start or resume scrolling and data capture |
| ⏸ **Pause** | Temporarily stop scrolling (can resume anytime) |
| ⏹ **Stop** | Stop completely (ready for a new group) |
| ⬇ **Download** | Export captured members as CSV |

> You can also adjust the **scroll speed slider** at any time.

---

## 📂 Output Example

A generated `.csv` file looks like this:

| Group | Name | Phone |
|--------|------|-------|
| Anime Fans 🇯🇵 | lalaboy | +91 12345677 |
| gamer group | (no name) | +44 12345 49677 |
| find me dog | John Wick | +1 333 555 1111 |

---

## 🛠️ Script Snippet

```javascript
// Copy-paste this full script into your WhatsApp Web console
