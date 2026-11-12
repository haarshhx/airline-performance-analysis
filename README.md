# ✈️ Airline Performance Analysis
### Which airline should a corporate travel desk book by default?

A data analytics project evaluating Indian domestic airlines using punctuality, cancellation rates and passenger complaints to identify the most reliable airline for corporate travel.

## 🎯 Business Problem

A corporate travel desk needs to select a default airline for employee bookings. The objective is to identify an airline that minimizes travel disruptions while maintaining service reliability.

## 📊 Key Findings

**1. IndiGo – Best punctuality**

- Average on-time performance: 86.02%
- Highest punctuality in all nine months (January–September 2026).
- Best overall scorecard ranking.

**2. Akasa Air – Strongest cancellation performance**

- Average cancellation rate: 0.13%.
- Lower cancellation rate than IndiGo in 8 out of 9 months.
- Its punctuality gap with IndiGo narrowed significantly in the last three months.

**3. SpiceJet and Alliance Air – Higher disruption concerns**

- SpiceJet's punctuality declined from 56.8% in January to 16.6% in September.
- Alliance Air recorded 63.57 complaints per 10,000 passengers.

## 🏆 Airline Scorecard

| Airline | On-Time % | Cancellation % | Complaints / 10K | Rank |
|---|---:|---:|---:|---:|
| IndiGo | 86.02% | 0.41% | 2.63 | 1 |
| Akasa Air | 80.79% | 0.13% | 2.52 | 2 |
| Air India Group | 79.50% | 0.74% | 3.23 | 3 |
| Alliance Air | 70.81% | 4.47% | 63.57 | 4 |
| SpiceJet | 34.56% | 7.39% | 4.82 | 5 |

*Based on January–September 2026 averages. Lower score is better.*

## ⚖️ Scoring Methodology

A weighted ranking model was developed:

- On-time performance: 50%
- Cancellation rate: 30%
- Passenger complaints: 20%

The monthly rankings were combined to calculate the final score.

## 💡 Business Recommendation

**Recommended default: IndiGo**

Akasa Air should be retained as the primary alternative.

The recommendation should be reviewed if:
- Akasa matches or exceeds IndiGo's punctuality for two consecutive months.
- IndiGo's cancellation rate rises above 1%.
- Company-specific route performance differs from national results.

## 🛠️ Tools & Skills

- Power BI
- Microsoft Excel
- Data Cleaning and Validation
- KPI Analysis
- Weighted Scoring Model
- Trend Analysis
- Business Intelligence
- Data-Driven Decision Making

## 📁 Project Report

[View the complete Airline Performance Analysis PDF](./airline_scorecard_interactive.pdf)

## 📚 Data Source

DGCA Monthly Domestic Air Traffic Reports (October 2025 – September 2026).

## ⚠️ Limitations

- On-time performance reporting expanded from 6 to 10 airports in January 2026.
- National averages may not represent company-specific routes.
- Ticket prices, schedules and availability are outside the scope of this analysis.

---

*Developed as a Data Analytics portfolio project.*
