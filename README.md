# Logistics-Operations
Healthcare Operations and Logistics Intelligence Dashboard (SQL + PowerBi Project)

#Project Objective
This project analyzes a multi-table logistics dataset restructured into a healthcare operations system to evaluate workforce efficiency, hospital performance, operational costs, patient movement, and service delivery.

#Primary goals:
- Assess healthcare staff productivity
- Identify top-performing hospitals
- Analyze patient journey efficiency
- Measure revenue generation by location
- Evaluate delay patterns and patient lifecycle bottlenecks
- Track operational risks and compliance
- Support executive decision-making with data-driven insights
- Business Problem

#Healthcare systems require operational visibility to:
- Improve patient throughput
- Reduce delays
- Optimize resource allocation
- Improve hospital performance
- Increase profitability
- Manage medical equipment efficiency
- Reduce operational costs

This project transforms logistics data into actionable healthcare intelligence.

#Dataset Summary
Core Tables Used:
| Table               | Healthcare Equivalent        | Purpose                    |
|---------------------|------------------------------|----------------------------|
| drivers             | Healthcare staff             | Staff productivity         |
| trucks              | Ambulances/medical equipment | Equipment management       |
| loads               | Patients/medical cases       | Patient case volume        |
| trips               | Patient journeys             | Treatment process analysis |
| facilities          | Hospitals/clinics            | Facility performance       |
| routes              | Geographic movement          | City and route analysis    |
| delivery_events     | Patient lifecycle events     | Timeliness and delay       |
| maintenance_records | Equipment servicing          | Operational readiness      |
| fuel_purchases      | Operational costs            | Cost analysis              |
| safety_incidents    | Compliance/risk              | Safety performance         |

#Database Relationship (ER Diagram)
<img width="1708" height="674" alt="Logistics Operations ER Diagram A drawio (1)" src="https://github.com/user-attachments/assets/82a20c32-2842-4440-a3df-156a854bde8d" />

# Tools Used

## Data Analysis
- SQL (Joins, Aggregations, CTEs, CASE Statements)
- PostgreSQL / MySQL

## Data Visualization
- Power BI
- DAX Measures
- Star Schema Modeling

## Portfolio & Documentation
- GitHub
- Markdown
- Draw.io / Lucidchart for ERD

---

# Data Modeling Approach

## Star Schema Design

### Fact Tables
- trips
- delivery_events
- fuel_purchases
- maintenance_records

### Dimension Tables
- drivers
- facilities
- routes
- trucks

### Benefits
- Reduced duplication
- Better scalability
- Faster BI performance
- Cleaner analytical reporting

---

# Key Business Analysis Results

## 1. Driver Productivity
### Insight:
- Number of trips completed per healthcare staff
- Identifies top-performing personnel
- Supports staffing optimization

---

## 2. Top Performing Drivers
### Insight:
- Highlights most active healthcare staff
- Useful for workforce planning and incentive programs

---

## 3. Facility Performance
### Insight:
- Hospitals with highest patient volumes
- Helps identify overloaded facilities

---

## 4. Load Distribution by City
### Insight:
- Determines cities with highest patient case volumes
- Supports regional healthcare planning

---

## 5. Revenue Generation by City
### Insight:
- Reveals most profitable healthcare regions
- Supports expansion strategies

---

## 6. Revenue vs Load Comparison
### Insight:
- Compares service volume to profitability
- Identifies underperforming high-volume regions

---

## 7. Profitability Per Load
### Insight:
- Measures operational efficiency
- Reveals best-value service regions

---

## 8. Transit Time Analysis
### Insight:
- Longest patient journey durations
- Identifies route inefficiencies

---

## 9. Delivery Event Distribution
### Insight:
- Lifecycle stage distribution
- Helps monitor service progression

---

## 10. On-Time vs Delayed Events
### Insight:
- Measures service quality
- Operational SLA tracking

---

## 11. Delay Hotspots
### Insight:
- Cities with highest patient delays
- Supports targeted intervention

---

# Example SQL Skills Demonstrated
- INNER JOIN
- LEFT JOIN
- CASE WHEN
- GROUP BY
- ORDER BY
- HAVING
- CTEs

## Aggregate Functions
- COUNT()
- SUM()
- AVG()
- MAX()

---

# Dashboard Features

## Power BI Pages
- Executive Overview
- Driver Performance
- Hospital Performance
- Revenue Dashboard
- Delay Monitoring
- Route Efficiency
- Operational Cost Tracking
- Equipment Maintenance

---

# Key KPIs
- Total Trips
- Total Revenue
- Revenue per Load
- Delay Rate
- Average Transit Time
- Facility Case Volume
- Driver Productivity
- Equipment Maintenance Frequency

---

# Strategic Recommendations

## Operational
- Improve high-delay cities
- Optimize long transit routes
- Reallocate underused staff
- Reduce low-profit regions

## Financial
- Focus on profitable origin cities
- Improve case-to-revenue ratios
- Reduce maintenance and fuel waste

## Healthcare
- Improve patient turnaround time
- Strengthen high-volume hospitals
- Improve SLA compliance

---

# Conclusion

This project demonstrates how logistics datasets can be transformed into healthcare operational intelligence.

## Outcomes
- Improved healthcare efficiency
- Better staff performance tracking
- Stronger profitability analysis
- Enhanced patient journey monitoring
- Executive-level healthcare decision support

# Portfolio Value

This project showcases:

- SQL expertise
- Data modeling
- Healthcare analytics
- Operational intelligence
- Power BI dashboarding
- Business problem solving
- Executive reporting

---

# Final Positioning Statement

**A full-scale healthcare operations intelligence project leveraging SQL, data warehousing principles, and business intelligence to drive strategic healthcare decisions.**
