# 📊 Fitness Hub Dashboard – Business Requirements & Report

This document outlines the **business requirements** and how the **Fitness Hub Dashboard** addresses them.  
The dashboard was designed to streamline reporting, reduce manual effort, and provide clear visual insights into the gym’s performance.

---

## 🏢 Problem Statement 1 – Overall Business Performance

### Requirement
Currently, data is summed up manually each time to calculate:
- Total number of clients
- Total number of trainers
- Total revenue generated
- Total expenses incurred
- Total profit earned

### Dashboard Solution
- The **Overview Page** automatically displays total members, trainers, revenue, expenses, and profit.
- KPIs are shown using **cards and summary visuals** for quick insights.
- Profit is calculated dynamically (Revenue – Expenses).

---

## 📅 Problem Statement 2 – Monthly Performance Tracking

### Requirement
Manually checking monthly data for:
- Clients acquired
- Revenue generated
- Expenses incurred
- Profit earned
- Side-by-side comparison of expenses vs. revenue

### Dashboard Solution
- The **Monthly Members & Finances Section** shows trends across months.
- Visual comparisons between **Revenue, Expenses, and Profit** using **bar and line charts**.
- Enables **month-over-month performance tracking** for better decision-making.

---

## 🏷️ Problem Statement 3 – Membership Status Tracking

### Requirement
Track and monitor membership tiers and client statuses:
- Overview by membership type (Platinum, Gold, Silver)
- Active vs. Expired memberships
- Member-level tracking (expiring soon, expired, cancelled)

### Dashboard Solution
- **Memberships Panel** displays active and expired memberships by tier.
- **Client Memberships Table** lists individual users, their status, and membership progress (with visual progress bars).
- Enables proactive management of renewals and retention.

---

## 🧮 Problem Statement 4 – Fitness & Health Calculations

### Requirement
A calculator to compute:
- BMI (Body Mass Index)
- BMR (Basal Metabolic Rate)
- TDEE (Total Daily Energy Expenditure)
- Other health insights based on Age, Weight, Height, Gender, and Activity Level

### Current Status
🚧 **Not yet implemented.**  
Currently, fitness and health metrics are calculated externally (manual/online tools).  

### Future Plan
- Build a **Fitness Calculator page** inside the dashboard.
- Inputs: Age, Gender, Weight, Height, Activity Level.
- Outputs: BMI, BMR, TDEE, and calorie recommendations.
- Visual indicators (progress bars, charts) for easier interpretation.

---

## 👤 Problem Statement 5 – Member/Client Detailed Profile

### Requirement
A detailed profile page containing:
- Personal info (Name, Age, Gender, Contact, Address)
- Membership details (Tier, Start Date, Expiry Date, Status)
- Health and fitness data (BMI, BMR, TDEE, Goals)

### Current Status
🚧 **Not yet implemented.**  
The dashboard currently provides **high-level client membership tracking** but not individual detailed profiles.  

### Future Plan
- Add a **dedicated profile page** for each client.
- Pull personal + membership data from the dataset.
- Integrate fitness calculations (BMI, BMR, TDEE).
- Allow quick filtering by **active, expiring, or expired members**.

---

## ✅ Benefits of the Dashboard

- Eliminates manual calculations and reporting.
- Provides **real-time business insights**.
- Improves **membership management and client retention**.
- Enhances **decision-making** through visual performance tracking.
- Offers **health tools** for members (BMI, BMR, TDEE).

---

## 📌 Next Steps / Enhancements

- Automate data refresh directly from the gym’s database.
- Add **predictive analytics** for churn prediction and revenue forecasting.
- Enable dashboard sharing through **Power BI Service** for managers and trainers.
- Integrate with **mobile-friendly reports** for quick access on the go.

---
