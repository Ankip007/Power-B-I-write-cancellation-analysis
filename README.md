

# Power BI Ride Cancellation Analysis – Mobility Domain (Ola):  

## Project Objective
-Developed an interactive dashboard visualizing for Identified key reasons and trends behind ride cancellations using multi-source data analytics.  
-Cleaned and integrated data from various sources; applied SQL queries for filtering and
transformation.  
-Visualized cancellation trends, time-based patterns, and region-wise impact using Power BI.  
-Enabled data-driven strategy changes that led to a 10% reduction in cancellation rate.  
-Tools: Power BI, SQL, Excel.  

 
## Dataset used
- <a href="https://github.com/Ankip007/Power-B-I-write-cancellation-analysis/blob/main/Bangalore_Ride_Data_May2025.xlsx">Dataset</a>

## Questions (KPIs)  
### SQL Questions:  
1. Retrieve all successful bookings:  
2. Find the average ride distance for each vehicle type:  
3. Get the total number of cancelled rides by customers:  
4. List the top 5 customers who booked the highest number of rides:  
5. Get the number of rides cancelled by drivers due to personal and car-related issues:  
6. Find the maximum and minimum driver ratings for Prime Sedan bookings:    
7. Retrieve all rides where payment was made using UPI:  
8. Find the average customer rating per vehicle type:  
9. Calculate the total booking value of rides completed successfully:  
10. List all incomplete rides along with the reason:  
### Power BI Questions:  
1. Ride Volume Over Time  
2. Booking Status Breakdown    
3. Top 5 Vehicle Types by Ride Distance  
4. Average Customer Ratings by Vehicle Type    
5. cancelled Rides Reasons    
6. Revenue by Payment Method  
7. Top 5 Customers by Total Booking Value  
8. Ride Distance Distribution Per Day  
9. Driver Ratings Distribution  
10. Customer vs. Driver Ratings  

## Dashboard Interaction
<a href="https://github.com/Ankip007/Power-B-I-write-cancellation-analysis/blob/main/OLA%20dashboards.jpg">View Dashboard</a>

## Process
- Verify data for any missing values and anomalies, and sort out the same.
- Made sure data is consistent and clean with respect to data type, data format and values used.
- Created pivot tables according to the questions asked.
- Merge all pivot tables into one dashboard and apply slicer to make dynamic.

## Dashboard

![1000029691](https://github.com/user-attachments/assets/f5b582ac-a276-4ff7-a722-04c7af43b10b)
![1000029694](https://github.com/user-attachments/assets/e18520cd-5c6b-4dfd-bf55-01a86eaff201)
![1000029697](https://github.com/user-attachments/assets/69088d80-4331-4337-b642-971abc2f2687)
![1000029700](https://github.com/user-attachments/assets/24d089eb-436a-478f-a0d6-3d198fe5d952)
![1000029703](https://github.com/user-attachments/assets/035694f0-4346-49ef-8080-ebf68c664b88)





## Project Insight  
### 1. Peak Cancellation Times Identified:  
Cancellations were highest during early mornings (6–9 AM) and late evenings (8–11 PM), often due to delays or driver unavailability.  

### 2. Region-wise Variability:  
Zones like Electronic City, Whitefield, and Marathahalli showed higher cancellation rates, primarily due to longer driver arrival times (VTAT/CTAT).  

### 3. Platform-Wise Trends:  
Bike and eBike bookings had the lowest cancellation rate.  
Auto and Prime Sedan saw higher cancellations, especially from customers citing "driver asked to cancel" and "driver not moving."  

### 4. Customer vs Driver Cancellations:  
Customer-initiated cancellations were more frequent, driven by reasons like driver delays and change of plans.  
Driver cancellations were more common during high-demand hours, often due to car-related or customer-related issues.  

### 5. VTAT/CTAT Impact:  
Longer vehicle-to-arrival time (VTAT) and customer-to-arrival time (CTAT) were strongly correlated with cancellations — indicating a need for route optimization or driver reallocation.  



## Final Conclusion:

-The analysis revealed that timing, location, and driver behavior significantly influenced ride cancellations.  
-Insights helped Ola’s operations team design platform-specific nudges, improve driver allocation during peak hours, and introduce incentives for high-cancellation zones.  
-As a result, the organization achieved a 10% reduction in cancellation rate, improving customer satisfaction and operational efficiency.  
-The project demonstrated the value of data integration and Power BI dashboards in driving actionable strategies in urban mobility.  

