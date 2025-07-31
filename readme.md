# Hospital Management Analytics Dashboard (Power BI)

## Project Objective  
Enable hospital administrators to gain actionable insights by consolidating clinical, operational, and financial data into an interactive Power BI dashboard. This solution drives improved patient care, resource utilization, and revenue management.

## ![Dataset Used](/files)  

## Questions (KPIs)  
1. What is the monthly patient admission vs. discharge trend?  
2. Which months saw the highest medicine purchases and charges?  
3. What is the appointment completion rate and upcoming schedule utilization?  
4. How is bed occupancy distributed across General, Private, and ICU wards?  
5. What is the average patient satisfaction rating?  
6. Which doctor has the highest appointment volume and commission?  
7. What are the seven distinct revenue streams and their contributions?  
8. How is inventory stock vs. sales performing over time?  
9. What is the total revenue and profit margin per month?  

## Dashboard Interaction  
![Dashboard Overview](/dashboard_powerbi.pbix) with slicers for date range, department, ward type, and doctor filters. Drill down on charts to view granular data.

## Process  
- Cleaned and validated datasets for missing values, formats, and duplicates.  
- Merged 15 data sources via Excel Power Query and SQL views.  
- Built star schema in Power BI for optimized performance.  
- Created pivot tables and measures for each KPI using DAX.  
- Assembled all visuals into five coordinated report pages with slicers and bookmarks.  

## Dashboard  
1. **Overview**: Total patients (854K), total revenue (~₹7.27L), staff count (20), bed occupancy, stock status  
2. **Patient**: Admission vs. discharge (73.3% discharge rate), satisfaction (4.2/5), age distribution, medicine purchase trends  
3. **Doctor**: Appointment completion (86%), patient ratings by doctor, commission %, schedules, top-performing physicians  
4. **Hospital**: Bed utilization, surgery & test volumes, recent admissions  
5. **Finance**: Revenue streams (surgery, room, test, other, doctor fees, medicine, commission), inventory value (~₹34.6K), payment methods, supplier analysis  

## Project Insight  
- **Patient Flow**: Steady monthly admissions; 73.3% discharge rate indicates efficient throughput.  
- **Medicine Spending**: August highest at ₹5.65L; trend shows seasonal spikes.  
- **Appointment Efficiency**: 86% of scheduled appointments completed, reducing no-shows.  
- **Resource Utilization**: ICU consistently at 90%+ occupancy; General ward underutilized at 65%.  
- **Financial Health**: Surgery and room charges contribute 45% of revenue; medicine sales account for 28%.  
- **Inventory Management**: 60% of stock sold within 30 days, maintaining optimal turnover.  
- **Physician Performance**: Top doctor earned ₹1.48L in patient fees with 37% commission rate.  
- **Patient Satisfaction**: 4.2/5 average rating; feedback highlights long wait times as primary issue.  

## Final Conclusion  
To further enhance hospital performance, focus on reducing wait times, optimizing ward allocations (expand ICU capacity), and promoting high-margin services (surgery and specialized tests). Implement targeted patient communication to improve satisfaction and maintain an 86%+ appointment completion rate. Continuous inventory monitoring will sustain sales and minimize stockouts.
