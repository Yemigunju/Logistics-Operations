# Logistics-Operations
Healthcare Operations and Logistics Intelligence Dashboard (SQL + PowerBi Project)

### Project Objective
This project analyzes a multi-table logistics dataset restructured into a healthcare operations system to evaluate workforce efficiency, hospital performance, operational costs, patient movement, and service delivery.

### Primary goals:
- Assess healthcare staff productivity
- Identify top-performing hospitals
- Analyze patient journey efficiency
- Measure revenue generation by location
- Evaluate delay patterns and patient lifecycle bottlenecks
- Track operational risks and compliance
- Support executive decision-making with data-driven insights
- Business Problem

### Healthcare systems require operational visibility to:
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
<img width="1402" height="673" alt="Logistics Operations - Executive Dashboard" src="https://github.com/user-attachments/assets/94e56a2a-6df1-4802-969d-ca10bf4ff3fb" />


## 1. Driver Productivity
### Insight:
- There were 83696 trips completed by the healthcare staff
- Identifies top-performing driver was Robert Jackson (DRV00019) 
- This supports staffing optimization

---

## 2. Top Performing Drivers
### Insight:
- Highlights most active healthcare staff as Robert Jackson (DRV00019)
- This is useful for workforce planning and incentive programs
<img width="588" height="203" alt="Top 5 drivers" src="https://github.com/user-attachments/assets/b8f19a5b-4d70-40d0-8594-81cf8333a8aa" />

---

## 3. Facility Performance
### Insight:
- Hospitals with highest patient volume is Nasville Distribution Center
- This helps identify overloaded facilities
<img width="579" height="433" alt="total cases handled by each hospitals" src="https://github.com/user-attachments/assets/520067f7-9e96-4dcb-879f-28aebab2fbdf" />

---

## 4. Load Distribution by City
### Insight:
- Columbus is the city with the highest patient case volume
- This supports regional healthcare planning
<img width="649" height="606" alt="Loads handled per city" src="https://github.com/user-attachments/assets/5a862819-4248-488c-9328-5281e8c6c361" />

---

## 5. Revenue Generation by City
### Insight:
- Philadelphia has Total revenue of #945,031,155
With #16416 total loads. Followed by Columbus with #885,047328 in total revenue with 15336 in total loads. This reveals most profitable healthcare regions
- This supports expansion strategies

---

## 6. Revenue vs Load Comparison
### Insight:
- The average revenue per load #1,039,360. This helps to compares service volume to profitability
- This helps identify underperforming high-volume regions
<img width="552" height="263" alt="Load volume and revenue per city" src="https://github.com/user-attachments/assets/22d044eb-cda5-4432-806d-5f6f9106f609" />


---

## 7. Profitability Per Load
### Insight:
- The average profit per load #57742, top ptofit per load is #58150 recorded by Phoenix and the least profit per load is #57349 recorded by Memphis. This helps measure operational efficiency
- This reveals best-value service regions
<img width="553" height="173" alt="Most profitable cities per load" src="https://github.com/user-attachments/assets/29a9ec58-5e8f-45b7-b9a5-f5697c303684" />

---

## 8. Transit Time Analysis
### Insight:
- The average transit time is 123 hrs. Miami has the longest transit time with 131 hrs and the least at Denver with 11hrs. This helps identify the longest patient journey duration
- This helps identify route inefficiencies
<img width="551" height="196" alt="Route with the longest average transit time" src="https://github.com/user-attachments/assets/13e55a33-bf7e-4494-bf8e-0e6db69a1418" />


---

## 9. Delivery Event Distribution
### Insight:
- There were 170820 total events, with 36076 delivery events. 50% was delivery while 50% pickup. This helps identify the lifecycle stage distribution
- This helps monitor service progression

---

## 10. On-Time vs Delayed Events
### Insight:
- 100% of events were delayed. The measures service quality
- This enhances operational SLA tracking

---

## 11. Delay Hotspots
### Insight:
- Atlanta is the city with highest patient delays
- This supports targeted intervention

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
