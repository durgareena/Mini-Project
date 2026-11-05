# Mini-Project
Supply Chain & Procurement Performance Analysis
Project Overview
The Supply Chain & Procurement Performance Analysis project focuses on analyzing purchase orders, supplier performance, warehouse operations, order fulfillment, and delivery timelines using Microsoft Excel and Power BI.

The cleaned dataset contains 18,000 purchase-order records. The project aims to transform raw procurement data into meaningful insights that support better business decisions.
Objectives
- Analyze procurement spending and order value trends.
- Track order fulfillment by comparing ordered and received quantities.
- Identify delivery delays and review delivery performance.
- Compare supplier performance.
- Analyze procurement patterns across countries and warehouse regions.
- Present key metrics through an interactive Power BI dashboard.
Dataset
Source Description: Inventory & Supply Chain Dataset for Analysis
Domain: Supply Chain / Procurement Analytics

The dataset includes purchase order details, supplier information, warehouse locations, delivery dates, quantities, order status, and order values.
Key Attributes
- purchase_order_id – Unique purchase order identifier.
- ordered_at – Date the purchase order was placed.
- expected_at – Expected delivery date.
- received_at – Actual receipt date, when recorded.
- Delivery delay days – Difference between actual and expected delivery dates.
- Delivery performance – Early, On Time, or Delayed.
- Received_status – Receipt completion category.
- Status – Received, Partial, Open, or Cancelled.
- supplier_id – Supplier identifier.
- country_code and country _names – Country code and name.
- warehouse_id and warehouse_region – Warehouse identifier and region.
- quantity_ordered – Quantity requested.
- quantity_received – Quantity received.
- quantity not received – Quantity not yet received.
- order_value – Recorded purchase order value.
Tools & Technologies
- Microsoft Excel: Used for dataset review, cleaning, preparation, and Pivot Tables.
- Power Query: Used for data transformation and preparation.
- Power BI Desktop: Used for data modelling, DAX measures, visualizations, and dashboard development.
Data Pre-Processing
- Checked for and removed duplicate records.
- Identified missing values in the received_at column.
- Standardized date and numerical formats.
- Created calculated fields for delivery delay and quantity not received.
- Filtered and sorted records by order status, supplier, warehouse, and delivery performance.
- Sorted date and month fields chronologically.
- Used Pivot Tables to summarize monthly order value, order status, supplier and warehouse performance, and ordered versus received quantities.
Data Modelling & DAX
Relationships were established between the cleaned dataset and analysis tables. Relationship cardinality and filter directions were configured to support reporting. A separate Measure table was used to organize DAX measures.
DAX Measures
- Total Orders – Calculates the total number of purchase orders.
- Total Order Value – Calculates the total recorded order value.
- Total Quantity Ordered – Calculates the total quantity ordered.
- Total Quantity Received – Calculates the total quantity received.
- Total Suppliers – Calculates the number of suppliers.
- Delayed Orders – Calculates the number of delayed orders.
Calculated Columns
- Delivery Delay Days – Calculates the number of days between expected and actual receipt dates.
- Delivery Performance – Categorizes orders based on delivery timing.
Power BI Dashboard
The consolidated dashboard includes:
- KPI cards displaying total orders, total order value, total quantity received, total quantity ordered, and total supplier count.
- A line chart showing monthly procurement value trends.
- A donut chart showing purchase order status distribution.
- A bar chart comparing order value by delivery performance.
- A bar chart displaying delayed orders by supplier.
- A supplier performance table showing total orders, order value, delayed orders, and average delivery delay.
- A treemap showing order value across countries.
- Slicers for order status and warehouse region.
- Interactive visual filtering, clear titles, and data labels where applicable.
Key Findings
- The dataset contains 18,000 purchase orders from 250 suppliers.
- Total order value is approximately 7.01 billion.
- Total quantity ordered is approximately 17 million, compared with approximately 15 million received.
- Supplier analysis shows variation in delayed-order counts and average delivery delays.
- Procurement value varies across countries.
- Order statuses include Received, Partial, Open, and Cancelled.
Note: The currency of the order value is not specified in the project dataset/report.
Analysis Types
Descriptive Analysis
- Summarized total orders, order value, quantities, and supplier count.
- Analyzed monthly procurement value trends.
- Examined order status distribution and country-wise procurement value.
- Compared supplier delivery performance and delayed orders.
Diagnostic Analysis
- Identified suppliers with higher numbers of delayed orders.
- Compared average delivery delay across suppliers.
- Examined delivery performance categories to identify areas requiring further investigation.
- Analyzed differences between ordered and received quantities.
Predictive Analysis
- Historical monthly procurement trends can be used as a baseline for future procurement planning.
- Supplier delivery history may help identify suppliers who could be at risk of future delays.
- Predictive forecasting has not been implemented in the current dashboard.
Prescriptive Analysis
- Review suppliers with high delayed-order counts and investigate the reasons for delays.
- Monitor the difference between ordered and received quantities to improve fulfillment tracking.
- Prioritize follow-up on open and partially received orders.
- Use monthly procurement trends and supplier performance metrics to support purchasing and delivery planning.
Conclusion
Excel and Power BI supported the project workflow from data cleaning and preprocessing to interactive reporting. The dashboard provides visibility into procurement value, order status, supplier performance, delivery delays, and fulfillment.

These insights can support better procurement planning, supplier monitoring, and delivery performance improvement. Overall, the project demonstrates how data analytics and visualization can transform supply chain data into meaningful information for informed decision-making.
