# Excel Project Documentation - World Billionaires
Analyzing Billionaires data in Excel. <br>
Author: Leonardo Beduschi Iunes <br>

## Introduction
This project analyzes a dataset titled "Billionaires", which provides detailed information about the world’s wealthiest individuals. The dataset initially contained 482 rows and multiple columns that capture various attributes about each billionaire and their respective countries.

## Project Overview
This project involves using Excel to clean and analyze the data. The goal of this project is to explore the dataset to uncover insights about the world's wealthiest individuals, their distribution across countries and industries, and the socioeconomic factors associated with their wealth.

## Steps Involved
### **1. Data Import**  
   The dataset includes the following key columns:

**Rank:** The billionaire’s position based on their net worth. <br>
**Category:** The classification of the billionaire, such as entrepreneur, investor, or executive. <br>
**Name:** The full name of the billionaire. <br>
**Country:** The country where the billionaire resides or is associated with. <br>
**City:** The city of residence or primary operation. <br>
**Source:** The primary source of the billionaire’s wealth, such as technology, retail, or real estate. <br>
**Industries:** The industries in which the billionaire operates or invests. <br>
**SelfMade:** Indicates whether the billionaire’s wealth is self-made or inherited. <br>
**Gender:** The gender of the billionaire. <br>
**FinalWorth:** The net worth of the billionaire, expressed in billions of dollars. <br>
**BirthYear:** The year the billionaire was born. <br>
**Age:** The calculated age of the billionaire. <br>
**CPI_Country:** The Consumer Price Index (CPI) for the billionaire’s country. <br>
**GDP_Country:** The Gross Domestic Product (GDP) of the billionaire’s country. <br>
**Life_Expectancy_Country:** The average life expectancy in the billionaire’s country. <br>
**Tax_Revenue_Country: The** total tax revenue as a percentage of GDP for the billionaire’s country. <br>
**Total_Tax_Rate_Country:** The total tax rate for businesses in the billionaire’s country. <br>
**Population_Country:** The total population of the billionaire’s country. <br> <br>
Initial Dataset Description
Before data cleaning and processing, the dataset consisted of 482 rows. These entries represented individual billionaires, with potential inconsistencies or missing values that required cleaning for accurate analysis. <br>
   Link: [Billionaires Statistics Dataset.xlsx](https://github.com/user-attachments/files/18526046/Billionaires.Statistics.Dataset.xlsx)<br><br>
   <img src="https://github.com/user-attachments/assets/0fb7babb-c473-40eb-b1b5-34fc971c55b3" alt="Image" width="700"/>

   
### **Data Cleaning**

To ensure the dataset was accurate and ready for analysis, the following data cleaning steps were performed:

1. **Backup Creation**:  
   A backup of the original dataset was saved to preserve the raw data before any modifications were made.

2. **Removal of Duplicates**:  
   Duplicate rows were identified and removed to ensure each billionaire appeared only once in the dataset.

3. **Standardizing Gender Values**:  
   - Replaced `'M'` with `'Male'` for consistency.  
   - Replaced `'F'` with `'Female'`.  

4. **Adding an Age Column**:  
   Calculated the `Age` column by subtracting the `birthYear` from the current year. This provided an additional metric for analysis.

5. **Changing Data Types**:  
   - Converted relevant columns to appropriate data types for accurate computations and visualizations.  
     For example:  
     - `FinalWorth` to numeric.  
     - `BirthYear` to integer.  
     - `Age` to integer.  

These steps ensured the dataset was cleaned, standardized, and ready for exploratory data analysis.


<img src="https://github.com/user-attachments/assets/0035dbff-a80b-49b7-b7a7-d216968b9c7d" alt="Image" width="800"/>

### **Analysis**

During the analysis phase, several techniques were applied to gain insights from the cleaned dataset. The following steps were undertaken:

1. **Descriptive Analysis**:  
   - Performed descriptive analysis to summarize key metrics, including average, median, and distribution of billionaire wealth (`finalWorth`), age, and other numeric variables.  
   - Identified trends and outliers in the data for further exploration.

2. **Pivot Tables**:  
   Pivot tables were used extensively to answer specific questions and explore relationships within the data. Key analyses include:  
   
   - **Top 10 Billionaires**:  
     Ranked the wealthiest individuals based on their `finalWorth`, highlighting the top 10 billionaires.  
   
   - **Billionaires by Group of Ages**:  
     Grouped billionaires by age ranges (e.g., 20-30, 30-40) to analyze the distribution of wealth and the count of billionaires in each age group.  
   
   - **Self-Made Percentage**:  
     Calculated the percentage of billionaires who are self-made versus those who inherited their wealth, providing insights into the sources of wealth.  
   
   - **Countries by Worth**:  
     Aggregated billionaire wealth by country to identify the countries with the highest total and average billionaire net worth.  
   
   - **Gender by Category**:  
     Analyzed the distribution of gender across different categories, highlighting trends in representation by category (e.g., industries, sources).

These analyses provided valuable insights into the dataset, enabling a deeper understanding of the characteristics and trends among the world’s billionaires.

### **Visualization**

In the visualization phase, various charts and interactive elements were created to represent the insights derived from the data. The focus was on building an intuitive and interactive dashboard for analysis. The steps and components include:

1. **Charts**:  
   Created multiple charts to visualize key insights, making the data easier to understand and explore:  
   
   - **Top 10 Richest Billionaires**:  
     A bar chart showcasing the 10 wealthiest individuals, ranked by their `finalWorth`.  
   
   - **Billionaires by Age**:  
     A column chart displaying the distribution of billionaires across age groups, highlighting trends by age.  
   
   - **Countries by Total Worth**:  
     A horizontal bar chart showing the total wealth of billionaires by country, identifying countries with the highest concentration of wealth.  
   
   - **Gender Representation by Category**:  
     A stacked bar chart comparing gender representation within different categories, such as industries and sources of wealth.  
   
   - **Self-Made vs. Inherited Wealth**:  
     A pie chart displaying the percentage of self-made billionaires versus those with inherited wealth.

2. **Interactive Slicers**:  
   Added slicers to make the dashboard interactive and allow users to filter the data dynamically:  
   
   - **Category**:  
     Filter data based on the category of the billionaire (e.g., entrepreneur, investor, executive).  
   
   - **Self-Made**:  
     Toggle between self-made and inherited wealth for deeper analysis.  
   
   - **Gender**:  
     Filter data by gender to analyze trends for male and female billionaires.

3. **Interactive Dashboard**:  
   Combined charts and slicers into a cohesive, interactive dashboard:  
   
   - **Layout**: Designed the dashboard to be clean and user-friendly, ensuring key insights are easy to identify.  
   - **Dynamic Filtering**: Enabled real-time filtering and chart updates based on slicer selections.  
   - **Highlighting Insights**: Added titles, legends, and labels to emphasize key findings in each chart.  
   
The interactive dashboard serves as the centerpiece of the project, providing a visual and dynamic representation of the data and enabling users to explore it from various perspectives.


## Dashboard
<img src="https://github.com/user-attachments/assets/d50447ee-9144-4993-ac15-7c726afea870" alt="Image" width="1000"/>
<br>

**Interactive Dashboard:** 
[Billionaires Statistics Dataset Raw.xlsx](https://github.com/user-attachments/files/18526200/Billionaires.Statistics.Dataset.Raw.xlsx)

## Conclusion

This project transformed raw data about billionaires into meaningful insights through cleaning, analysis, and visualization. Key findings include trends in wealth distribution by country, age, and industry, as well as disparities in gender representation and self-made status. <br>
The interactive dashboard allowed for dynamic exploration, highlighting patterns such as the dominance of certain countries and industries in billionaire wealth. While effective, future improvements could include incorporating updated data and deeper analysis of socioeconomic factors for richer insights. This project demonstrates the value of structured analysis in understanding complex datasets.
