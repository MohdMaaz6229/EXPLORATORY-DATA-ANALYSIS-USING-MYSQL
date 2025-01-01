# **Exploratory Data Analysis (EDA) on Layoffs Dataset**

## **Project Overview**  
This project explores trends and insights from a layoffs dataset using SQL. The analysis investigates factors contributing to layoffs, such as industry, location, and company stage, along with patterns in funding and employee reductions.

---

## **Dataset Description**  
The dataset contains information about layoffs across various companies and industries, with the following key columns:  
- **company**: Name of the company.  
- **location**: City of the company.  
- **industry**: Industry category.  
- **total_laid_off**: Number of employees laid off.  
- **percentage_laid_off**: Percentage of workforce laid off.  
- **date**: Date of the layoff event.  
- **stage**: Business stage (e.g., Series A, IPO).  
- **country**: Country where the company is located.  
- **funds_raised**: Total funding raised by the company (in millions).

---

## **Key Features of Analysis**  
1. **Data Cleaning**:  
   - Handled missing values in `total_laid_off` and `percentage_laid_off`.  
   - Standardized text formats for `location` and `industry`.  

2. **Exploratory Analysis**:  
   - Identified industries and countries most affected by layoffs.  
   - Analyzed the relationship between funds raised and layoffs.  
   - Studied layoff trends over time.

3. **Insights**:  
   - Industries with the highest layoffs.  
   - Countries most impacted by workforce reductions.  
   - Trends in layoffs based on company stage and funding.  
