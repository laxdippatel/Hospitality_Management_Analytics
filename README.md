# Hospitality_Management_Analytics
Hospitality Management Analytics : Power BI Project for Optimized Data Insights and Visualizations


![image](https://github.com/user-attachments/assets/48d39d95-6452-4df5-b3a9-e115794a991a)




# Data Loading and Power Query Documentation

This document outlines the steps to load data and apply transformations using Power BI for the Hospitality Management Project.

---

## **Steps for Data Loading**

1. **Prepare the Dataset:**
   - Create a folder on your desktop and store all the CSV files related to the Hospitality Challenge.

2. **Load Data into Power BI:**
   - Open a new Power BI file.
   - Navigate to the "Get Data" option, select **Folder**, and browse to the folder containing the CSV files.

3. **Transform Data:**
   - Access the **Transform Data** option in Power BI to manage and refine each dataset.

4. **Expand and Rename Tables:**
   - Duplicate the data source four times.
   - For each duplicate, expand one dataset by clicking on the **Binary** option.
   - Rename the tables accordingly for clarity and consistency.

---

## **Power Query Steps for Tables**

### **1. dim_date**

- **Remove Unnecessary Column:**
  - Remove the column `day_type`.
  - **Reason:** Based on feedback from the mock dashboard review, the classification of weekends in the dataset (Saturday and Sunday) does not align with the industry standard (Friday and Saturday). To address this, the `day_type` column will be re-created using calculated columns.

---

### **2. dim_rooms**

- **Correct Column Headers:**
  - Use the **"Use First Row as Headers"** option to correctly capture the column names.

---

## **Measures_List**

- You can refer this Measures List for the more All of measurement which taken by combination of table and make it formula based for Analytics Data.
- It will be helpful to understand the formula of used in PowerBI Dashboard.
  
- https://github.com/laxdippatel/Hospitality_Management_Analytics/blob/main/measures_list.md
  
## **Future Steps**

- Ensure proper validation of transformations applied in Power Query.
- Document any additional changes made to the datasets to maintain transparency and reproducibility.

---

This documentation provides a detailed workflow for data loading and transformations, ensuring clarity and consistency in data preparation for the Hospitality Management Project.
