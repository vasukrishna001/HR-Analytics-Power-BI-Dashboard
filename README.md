# HR Analytics Power BI Dashboard

Welcome to my **HR Analytics Power BI project**! This repository provides an end-to-end demonstration of how to collect, clean, and visualize HR data, focusing on employee attrition trends.

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Data Sources](#data-sources)  
3. [Data Preparation & Modeling](#data-preparation--modeling)  
4. [Visualization & Insights](#visualization--insights)  
5. [How to Use This Repository](#how-to-use-this-repository)  
6. [Project Structure](#project-structure)  
7. [Contributing](#contributing)  
8. [License](#license)

---

## Project Overview
1. **Data Acquisition**  
   - Raw HR analytics datasets were downloaded from [Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/datasets/davidafolayan/hr-analytics)).  
   - Multiple CSV files were consolidated into an **Excel file** with separate sheets.

2. **Data Cleaning**  
   - Managed missing values, removed duplicates, and corrected spelling errors in Power Query.  
   - Unwanted columns were removed to streamline analysis.

3. **Data Modeling**  
   - Established relationships between tables using Power BI’s **Relationship Editor**.  
   - Created new columns and measures, such as numerical encoding for attrition, age bins, and salary ranges.

4. **Visualization**  
   - Built interactive dashboards in **Power BI** showcasing key metrics like total employees, attrition rate, average salary, and more.  
   - Created filters (Gender, Department) to segment the data for deeper insights.

---

## Data Sources
- **Raw Data**: HR analytics CSV files from Kaggle.  
- **Combined File**: Excel workbook containing multiple sheets for each dataset.  
- **Power BI**: Used the **.pbix** file included in this repository to create visuals.

---

## Data Preparation & Modeling
1. **Import to Power BI**  
   - Imported the combined Excel file into Power BI Desktop.  
   - Auto-detected data types to ensure correct formatting in Power Query.

2. **Clean & Transform**  
   - Handled missing data by either replacing values or removing null rows, depending on context.  
   - Removed irrelevant columns to reduce data clutter.  
   - Fixed spelling errors and standardized categorical data (e.g., department names).

3. **Relationships & Calculations**  
   - Linked relevant tables with **one-to-many** relationships.  
   - Added a new numerical column for attrition (e.g., 1 for “Yes,” 0 for “No”).  
   - Generated measures for **age bins** (e.g., 18-25, 26-35, etc.) and **salary ranges** (e.g., 20K-40K, 40K-60K, etc.).

---

## Visualization & Insights
1. **Overall Attrition Metrics**  
   - **Total Employees**: 1470  
   - **Employees Left**: 237  
   - **Attrition Rate**: 16.1%  
   - **Average Tenure**: 4.56 years  
   - **Average Salary**: ~113K  
   - **Average Age**: ~29

2. **Attrition by Education**  
   - Marketing: 27%  
   - Computer Science: 25%  
   - Information Technology: 20%  
   - Business: 8%  
   - (Other categories vary)

3. **Attrition by Job Role**  
   - Top 4 roles with highest attrition:
     - Data Scientist  
     - Sales Executive  
     - Software Engineer  
     - Sales Representative  

4. **Attrition by Tenure**  
   - ~120 employees left within 2 years of joining, suggesting early turnover challenges.

5. **Attrition by Salary**  
   - Majority of those who left earned around 20K.  
   - A smaller peak at 73K salary range.

6. **Attrition by Age**  
   - 25-year-olds: 113 left  
   - 18-year-olds: 96 left

7. **Performance Ratings**  
   - The attached graph shows distinct attrition trends by performance rating, with mid-level ratings often contributing to higher turnover.

8. **Interactive Filters**  
   - **Gender Filter**: Male, Female, Non-binary.  
   - **Department Filter**: Human Resources, Sales, Technology, etc.

For a detailed view, refer to the **PDF report** in the `reports` folder.

---

