# 📊 Work Tracker & Salary Analytics System

A high-performance, visually stunning attendance and payroll management tool designed for professionals. This application uses a **Glassmorphic UI** and local-first data persistence to help track daily work status, calculate net payouts, and visualize productivity trends.

---

## ✨ Key Features

### 📅 **Smart Attendance Calendar**
*   **One-Click Toggle:** Cycle through statuses easily: `Present` → `Absent` → `WFH` → `Sunday` → `Holiday`.
*   **Compact Mode:** Automatically adjusts layout for long months (like **May and August**) to ensure the UI remains clean and fits on one screen without overlapping.
*   **Dynamic Themes:** The background and accent colors change every month to reflect **Indian seasonal aesthetics** (e.g., Orange for October/Durga Puja, Blue for June).

### 💰 **Automated Payroll Logic**
*   **Real-time Calculation:** Instantly calculates salary based on your monthly base rate.
*   **PTAX Compliance:** Automatically deducts **Professional Tax (₹110)** if the gross salary exceeds **₹10,000**.
*   **LOP Tracking:** Calculates **"Loss of Pay"** automatically for absent days.
*   **Efficiency Metrics:** View your **"Daily Earning Rate"** and **"Attendance Percentage"** at a glance.

### 📈 **Data Visualization & Reporting**
*   **Interactive Charts:** Uses **Chart.js** to provide a high-quality bar-graph breakdown of your monthly work distribution.
*   **Clean PDF Exports:** Generate a professional, **sidebar-free PDF report** formatted specifically for printing or submission to HR.

### 🛡️ **Privacy & Backups**
*   **Local Storage:** Your data never leaves your browser. No server, no tracking—**Total Privacy**.
*   **Backup/Restore:** Export your entire history as a `.json` file and import it on any other device or browser.

---

## 🚀 How to Use

1.  **Setup Your Profile:**
    *   Open the **Settings Sidebar** (☰ icon).
    *   Upload your profile picture.
    *   Enter your **Name, Designation, Company, and Base Salary**.
2.  **Log Attendance:**
    *   Select the current **Month and Year**.
    *   Click on any date cell to change its status. The colors and salary data will update instantly.
3.  **Analyze Your Month:**
    *   Check the **Monthly Analytics** panel on the right to see your **Net Payout** and **Work Efficiency**.
4.  **Export/Report:**
    *   Click **Download PDF Report** to save a clean version of your monthly summary.
    *   Use **Gmail Compose** to quickly send a pre-formatted summary via email.

---

## 🛠️ Technical Stack

*   **Frontend:** HTML5, CSS3 (Advanced Grid & Flexbox)
*   **Design:** Glassmorphism, Backdrop Filters
*   **Charts:** Chart.js with DataLabels Plugin
*   **Storage:** Browser `localStorage` API
*   **Fonts:** Lexend (via Google Fonts)

---

## 📌 Technical Note on Calculations

*   **Daily Rate:** `Base Salary / Total Days in selected Month`
*   **Net Salary:** `(Paid Days * Daily Rate) - Professional Tax`
*   **Paid Days:** Sum of `Present` + `WFH` + `Sunday` + `Holiday`

---


## 🗺️ Roadmap / Upcoming Features
- [ ] **Dark/Light Mode Toggle:** Allow manual override of the theme.
- [ ] **Multi-Currency Support:** Support for $, €, and £ for international users.
- [ ] **Overtime (OT) Calculation:** Add a status for extra work hours.
- [ ] **Automatic Holiday Sync:** Fetch Indian Gazetted holidays via API.
- [ ] **Data Encryption:** Optional password protection for the LocalStorage data.

---

## 👤 Credits
*   **Created by:** **Paromita Saha**
*   **Role:** Financial Data Entry & Attendance Management
*   **Version:** 2.0 (2026 Edition)

---

### 📄 License & Usage
This project is for personal use. All data is stored locally in the user's browser cache. **Note:** Please use the **Export Backup** feature regularly to prevent data loss when clearing browser history or switching computers.
