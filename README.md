# Hotel Booking Data Warehouse & Power BI Dashboard

## Project Overview
This project demonstrates the design and implementation of a **Data Warehouse** for a hotel booking system.  
It includes an **ETL process** and a **Power BI dashboard** for business insights.

The data warehouse follows a **galaxy schema** and integrates data from multiple sources:
- `customersData.csv` (customer details)
- `hotelbooking` (MySQL database)
- `room_data.xlsx` (room details)

The Power BI report (`DATAWAREHOUSE.pbix`) provides visualization and analysis of hotel booking data.

---

##  Architecture
1. **ETL Process**
   - Implemented using **Talend** and **Apache NiFi**.
   - Loads and transforms data into MySQL Data Warehouse.

2. **Data Warehouse**
   - Designed with a **galaxy schema**.
   - Contains dimension and fact tables such as:
     - `Dim_Customer`
     - `Dim_Hotel`
     - `Dim_Room`
     - `Fact_Booking`

3. **Visualization**
   - Interactive Power BI dashboard with KPIs:
     - Booking trends over time
     - Customer demographics
     - Revenue analysis
     - Room utilization

---

##  Repository Contents
- `DATAWAREHOUSE.pbix` → Power BI dashboard file

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/DATAWAREHOUSE.git
