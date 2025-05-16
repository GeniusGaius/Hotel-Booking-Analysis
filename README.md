# Hotel-Booking-Analysis
Excel-based analysis of hotel booking trends and revenue performance. Insights into ADR, cancellations, customer segments, and seasonal demand.

> “Data may be silent, but it never lies. You just need to know what questions to ask.”

---

## Project Overview

I built this project as part of my data analytics training with **Quantum Analytics NG**, but the problem felt personal.

I’ve always wondered — in a world where customers cancel at the last minute, where bookings flood in from five different channels, and where the same room earns wildly different prices — **how do hotels stay profitable?**

That curiosity drove this Excel-powered deep dive into hotel booking behavior, revenue trends, and strategic blind spots.

---

## Objective

To uncover patterns in guest behavior and booking trends that directly impact **ADR (Average Daily Rate)**, **cancellation risk**, and **market performance** — and offer **actionable recommendations** for improving RevPAR.

---

## About the Dataset

The dataset simulates a real-world hospitality environment and includes:

- Booking status (confirmed, canceled)
- Guest origin (by country)
- Room type and ADR (average daily rate)
- Stay duration
- Distribution channel
- Customer type (e.g., transient, group, etc.)

---

## Data Preparation (Excel + Power Query)

Before any insights could emerge, the data needed structure. I applied the following cleaning and transformation steps using **Power Query** and Excel formulas:

- **Removed missing values and irrelevant columns**
- **Dropped duplicates based on booking ID**
- **Corrected inconsistent date and country entries**
- **Converted data types** for dates, prices, and booleans
- **Created helper columns**:
  - Booking month
  - Stay category (weekday/weekend)
  - Cancellation flag
  - Channel performance bucket

Clean data, clean insights.

---

## Key Metrics (KPIs)

| Metric | Why It Matters |
|--------|----------------|
| **ADR (Average Daily Rate)** | The heartbeat of hotel revenue |
| **Monthly Booking Trends** | For forecasting and seasonality |
| **Customer Type Impact** | Know who brings the money |
| **Top Guest Origins** | Target campaigns and packages |
| **Cancellation Frequency** | Plug revenue leaks before they grow |
| **Market Segment Performance** | Adjust pricing and promotions accordingly |

---

## Findings

- **Room A** consistently had the highest ADR (₦7.8M+), making it the most profitable option.
- **Online Travel Agencies (OTA)** brought in ₦6.6M+ — digital is dominant.
- **July and August** were peak booking months — ideal for revenue optimization strategies.
- **Transient guests** (often solo or business travelers) outperformed groups in revenue.
- **High-risk cancellation behavior** was detected from guests like “Michael Johnson” and “Robert Smith,” who canceled over 48 times.
- **Top countries**: 🇵🇹 Portugal, 🇬🇧 UK, 🇫🇷 France — clear opportunities for geo-targeted offers.

---

## Recommendations

Based on the findings, here’s how hotels can turn data into profit:

1. **Segment customers by behavior** — don’t treat every guest the same.
2. **Build cancellation risk scores** to flag serial cancelers and reduce uncertainty.
3. **Promote high-yield room types** (like Room A) in peak months.
4. **Focus on high-ADR segments** (transient & online direct bookings).
5. **Geo-target top-performing countries** with localized deals and retargeting.
6. **Optimize group pricing** — they book in bulk but yield less.

---

## 🧠 Final Thoughts

This wasn’t just an Excel project. It was a case study in how **curiosity plus structure** leads to clarity.

If you're in the hospitality business and want to go beyond "gut feelings" and start **making decisions backed by numbers**, then this project is for you.

---

## Dasbboard View in Excel
![Hotel Bookings Image](https://github.com/user-attachments/assets/eb9f0837-9c3e-4fa3-9849-0796d5cec3be)
<a href="https://www.linkedin.com/posts/john-gaius-m_dataanalytics-hoteldata-excelanalysis-activity-7319300517711519745-m_Gy?utm_source=share&utm_medium=member_desktop&rcm=ACoAABwTWvwBrwno3DC96otPksttbAeLF72I-bQ">See Complete Live Analysis Video Here</a>

