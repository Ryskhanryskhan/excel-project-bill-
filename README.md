# Excel Data Analysis Project - Portfolio

### Project Overview

This Excel project analyzes a dataset containing personal information, GDP, and wealth data of individuals. The goal is to clean, transform, and analyze the data to derive insights such as the top 10 wealthiest people, the distribution of millionaires by age, and other key demographic trends.

### Applied Steps

#### 1. Data Cleaning and Transformation
- **Removing Duplicates**: The dataset was cleaned by removing any duplicate entries to ensure accuracy and consistency.
- **Replacing Values**: Gender columns with values "F" and "M" were transformed to "Female" and "Male" for better clarity.
- **Combining Birth Date Columns**: The birth year, month, and day columns were combined into a single "Date of Birth" column for easier analysis.
- **Calculating Age**: The age of each person was calculated using the `YEARFRAC` and `ROUNDDOWN` formulas to subtract the birth year from the current year.

#### 2. Data Formatting
- **GDP Data Cleaning**: In the "GDP Country" column, dollar signs and commas were removed using the **Find & Replace** function to make the data manipulable.
- **Number Formatting**: The data type was changed from "General" to "Number" format. Decimal places were removed, and space separators were applied for better readability of large numbers.

#### 3. Creating and Formatting the Table
- **Table Creation**: The cleaned and transformed dataset was converted into an Excel table for better organization and ease of analysis.
- **Table Formatting**: The table was formatted to improve its appearance and ensure that all data was aligned correctly.

#### 4. Descriptive Analysis
- **Descriptive Statistics**: Using the **Data Analysis Tool** in Excel, a descriptive analysis was performed on the relevant columns to calculate mean, median, standard deviation, etc., providing an overview of the data distribution.

#### 5. Pivot Table Creation
- **Wealthiest People Analysis**: A pivot table was created to analyze the top 10 wealthiest individuals by summing the **Final Wealth** column. The names of individuals were placed in the row area, and the **Final Wealth** values were summed in the value area.
- **Filtering Top 10**: A filter was applied to show only the top 10 wealthiest individuals by selecting "Top 10" in the filter settings.
- **Sorting**: The pivot table was sorted in descending order of **Final Wealth** to display the wealthiest individuals at the top.

#### 6. Age and Millionaire Analysis
- **Counting Millionaires by Age**: A pivot table was created to count the number of millionaires in each specific age group.
- **Grouping by Age Range**: The individuals were grouped by age in 10-year increments to provide insights into wealth distribution across different age ranges.

#### 7. Slicers for Interactivity
- **Slicers**: Inserted slicers were added to the table and pivot tables, allowing users to filter the data by categories like country, gender, and wealth status, making the dashboard interactive and user-friendly.

### Key Insights

- The **Top 10 Wealthiest Individuals** were easily identified and displayed in the pivot table.
- Age groups were analyzed to show the distribution of millionaires, offering insights into which age groups hold the most wealth.
- The slicers allowed for dynamic filtering, helping to explore the data based on different parameters.

### Conclusion

This Excel project demonstrates the process of cleaning, transforming, and analyzing large datasets using various Excel functions such as Find & Replace, Pivot Tables, Descriptive Statistics, and Slicers. The results provide valuable insights into wealth distribution, allowing stakeholders to understand the demographics of wealthy individuals more clearly.
