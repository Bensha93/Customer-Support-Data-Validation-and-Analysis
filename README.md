# Customer Support Data Validation and Analysis

This project focuses on validating and analyzing customer support data to ensure data quality and provide actionable insights. The repository contains SQL queries designed to handle missing data, categorize support tickets, and generate reports that highlight key metrics related to response and resolution times, as well as customer satisfaction ratings.

---

## **Project Overview**

The project is divided into three main tasks:

### **Task 1: Data Validation and Cleaning**  
**Objective**: Validate and clean the `support` table based on provided data descriptions. This ensures all columns meet expected criteria, including handling missing values, standardizing categorical variables, and correcting date formats.  

- Cleaned columns include `category`, `status`, `creation_date`, `response_time`, and `resolution_time`.  
- Query ensures that missing values are replaced appropriately and data conforms to specified ranges.

### **Task 2: Analyzing Response Time by Category**  
**Objective**: Calculate the minimum and maximum response times for each category of support tickets.  

- Output includes columns: `category`, `min_response`, and `max_response`.  
- Response times are rounded to two decimal places for clarity and uniformity.

### **Task 3: Survey Rating Analysis for Specific Categories**  
**Objective**: Investigate the ratings provided by customers for support tickets related to "Bug" and "Installation Problem" categories.  

- Extracted information includes `rating`, `customer_id`, `category`, and `response_time`.  
- Data is filtered to focus on the target categories using a join between the `support` and `survey` tables.

---

## **Files in the Repository**

1. **Task_1_Data_Validation.sql**  
   - SQL query for cleaning and validating the `support` table.  
2. **Task_2_Response_Time_Analysis.sql**  
   - SQL query for analyzing minimum and maximum response times by category.  
3. **Task_3_Survey_Rating_Analysis.sql**  
   - SQL query for extracting ratings for specific support categories.
