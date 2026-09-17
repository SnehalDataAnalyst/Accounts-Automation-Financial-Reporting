# 📊 Accounts Automation & Financial Reporting System

Automated fee-collection tracking and reporting dashboard for an educational institution — replacing a manual, spreadsheet-based process with real-time visibility into collection performance, pending dues, and payment trends across academic years 2021–2023.

📌 Project Summary

This project automates fee-collection tracking for batches 8th–12th across academic years 2021–2023. Raw fee records were cleaned and structured using SQL and Excel, then modeled into an interactive Power BI dashboard giving real-time visibility into collection rate, pending dues, and payment trends — replacing a manual, error-prone reconciliation process.

🎯 Problem Statement

Before automation, fee records were tracked manually across scattered spreadsheets per batch and academic year:
-No real-time visibility into pending dues or overall collection rate
-Manual reconciliation of cash vs. UPI payments was slow and error-prone
-Year-end reporting required manually compiling data from multiple disconnected sheets
-No easy way to spot underperforming batches or partial-payment accounts

🛠 Tools Used

SQL – Data cleaning and preparation
Excel – Raw data source and pre-processing
Power BI – Dashboard modeling, DAX measures, and visualization

📂 Dataset

Student-level fee records across batches 8th–12th, academic years 2021–2023
Columns: Student Name, Batch, Total Fees, Fees Received, Payment Mode, Payment Status, Payment Date
Source: [Add your dataset link here]

📊 Dashboard Preview

The report is a single, clean summary page — KPIs (collection rate, total fees received, pending fees, revenue, average revenue per student), a batch-wise revenue breakdown, and a student-level fee table are all visible at a glance.

Rather than a second visible page, month-by-month payment status detail is delivered through a Power BI report-page tooltip — a dedicated page sized to tooltip dimensions and linked to the student fee table. Hovering over a student's row surfaces their paid/pending payment history by month, without navigating away from the main dashboard. This keeps the summary view clean for stakeholders while still surfacing transaction-level detail on demand.

💡 Key Insights

💰 87.03% collection rate — ₹66.7L received against total billed fees, leaving ₹8.3L in pending dues
⚖️ Balanced batch distribution — fees received are almost evenly split across batches 8th–12th (~19.8%–20.1% each), indicating stable collection across grade levels
🧾 Partial-payment segment — a distinct group of students have only partially cleared their fees, a concrete segment for targeted follow-up
🎓 Average revenue per student: ₹17.79K — a baseline to flag underperforming batches or years
📅 Payment timing lag — month-wise tracking surfaces where payment dates trail billing months, useful for spotting seasonal collection delays

#📈 Results & Business Impact

-Reduced manual fee-tracking and reporting effort by ~80%
-Converted a static, end-of-year reconciliation process into a real-time, filterable dashboard (by academic year, batch, and payment mode)
-Made ₹8.3L in pending dues immediately visible, enabling proactive follow-up instead of reactive chasing
-Established a single source of truth for collection rate and revenue across 3 academic years

🚀 How to Use

Download the .pbix file
Open in Power BI Desktop
If prompted to refresh data, point it to your local Excel/CSV file
Use the slicers (Academic Year, Batch, Mode of Payment) to explore

👩‍💻 Author
Snehal Kokate Aspiring Data Analyst SQL • Excel • Power BI
