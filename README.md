# Salary-Tracking-system
Salary &amp; Attendance Tracking System
📊 Work Tracker & Salary Analytics System
A high-performance, visually stunning attendance and payroll management tool designed for professionals. This application uses a Glassmorphic UI and local-first data persistence to help track daily work status, calculate net payouts, and visualize productivity trends.
✨ Features
📅 Smart Attendance Calendar
One-Click Toggle: Cycle through statuses easily: Present → Absent → WFH → Sunday → Holiday.
Compact Mode: Automatically adjusts layout for long months (like May/August) to ensure everything fits on one screen.
Dynamic Themes: The background and accent colors change every month to reflect Indian seasonal vibes (e.g., Orange for October/Durga Puja, Blue for June).
💰 Automated Payroll Logic
Real-time Calculation: Instantly calculates salary based on a monthly base rate.
PTAX Compliance: Automatically deducts Professional Tax (₹110) if the gross salary exceeds ₹10,000.
LOP Tracking: Calculates "Loss of Pay" for absent days.
Efficiency Metrics: View your "Daily Earning Rate" and "Attendance Percentage" at a glance.
📈 Data Visualization
Interactive Charts: Uses Chart.js to provide a bar-graph breakdown of your monthly work distribution.
Professional Reports: Generate a clean, sidebar-free PDF report for submission to HR or managers.
🛡️ Privacy & Backups
Local Storage: Your data never leaves your browser. No server, no tracking.
Backup/Restore: Export your entire history as a .json file and import it on any other device.
🚀 How to Use
Setup Your Profile:
Open the Settings Sidebar (☰ icon).
Upload your profile picture.
Enter your Name, Designation, Company, and Base Salary.
Log Attendance:
Select the current Month and Year.
Click on any date cell to change its status. The colors will update instantly.
Analyze:
Check the Monthly Analytics panel on the right to see your Net Payout and Efficiency.
Export/Report:
Click Download PDF Report to save a clean version of your monthly summary.
Use Gmail Compose to quickly send a summary via email.
🛠️ Technical Stack
Frontend: HTML5, CSS3 (Advanced Grid & Flexbox)
Design: Glassmorphism, Backdrop Filters
Charts: Chart.js with DataLabels Plugin
Storage: Browser localStorage API
Fonts: Lexend (via Google Fonts)
📌 Technical Note on Calculations
Daily Rate: Base Salary / Total Days in selected Month
Net Salary: (Paid Days * Daily Rate) - Professional Tax
Paid Days: Sum of Present + WFH + Sunday + Holiday
👤 Credits
Created by: Paromita Saha
Purpose: Financial Data Entry & Attendance Management
Version: 2.0 (2026 Edition)
📄 License
This project is for personal use. All data is stored locally in the user's browser cache. Use the Export Backup feature regularly to prevent data loss when clearing browser history.
