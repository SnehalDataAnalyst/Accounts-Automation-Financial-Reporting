# 📊 Accounts Automation & Financial Reporting System
# An automated fee-collection tracking dashboard built in Power BI — replacing a manual, spreadsheet-based process for tracking student fee collection across academic years 2021–2023, with SQL used for data cleaning and Excel for source data preparation.

📌 Dashboard Preview

📋 Table of Contents
Overview
Problem Statement
Key Insights
Results & Business Impact
Dashboard Design
Tech Stack
Folder Structure
Key Metrics
Contact

Overview

This project automates fee-collection tracking and reporting for an educational institution, covering academic years 2021–2023 across batches 8th–12th. Raw fee records were cleaned and structured using SQL and Excel, then modeled into an interactive Power BI dashboard that gives a real-time view of collection performance, pending dues, and payment trends — replacing a manual, error-prone reconciliation process.

Problem Statement

Before automation, fee records were tracked manually across scattered spreadsheets per batch and academic year, which created several problems:

No real-time visibility into pending dues or overall collection rate
Manual reconciliation of cash vs. UPI payments was slow and error-prone
Year-end reporting required manually compiling data from multiple disconnected sheets
No easy way to spot underperforming batches or partial-payment accounts
Key Insights
Collection performance: 87.03% collection rate — ₹66.7L received against total billed fees, leaving ₹8.3L in pending dues
Balanced batch distribution: Fees received are almost evenly split across batches 8th–12th (~19.8%–20.1% each), indicating stable enrollment and collection across grade levels
Partial-payment segment: A distinct group of students have only partially cleared their fees — a concrete, actionable segment for targeted follow-up
Per-student benchmark: Average revenue per student (₹17.79K) provides a baseline to flag batches or years performing below expectations
Payment timing lag: Month-wise payment status tracking surfaces where actual payment dates trail billing months, useful for spotting seasonal collection delays

Results & Business Impact
Reduced manual fee-tracking and reporting effort by ~80%
Converted a static, end-of-year reconciliation process into a real-time, filterable dashboard (by academic year, batch, and payment mode)
Made ₹8.3L in pending dues immediately visible instead of buried across sheets, enabling proactive follow-up
Established a single source of truth for collection rate and revenue across 3 academic years

Dashboard Design

The report is intentionally kept to a single page for a clean, at-a-glance view of KPIs, the batch-wise revenue breakdown, and the student-level fee table.

Rather than adding a second visible page, month-by-month payment status detail is delivered through a Power BI report-page tooltip: a dedicated page sized to tooltip dimensions and linked to the student fee table. Hovering over a student's row surfaces their paid/pending payment history by month, without navigating away from the main dashboard — balancing a clean summary view for stakeholders with on-demand transaction-level detail.
