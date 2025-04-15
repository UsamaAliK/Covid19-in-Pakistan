# COVID-19 in Pakistan: Exploratory Data Analysis (EDA)

This project provides an in-depth exploratory data analysis (EDA) of COVID-19 cases in Pakistan. The analysis focuses on understanding the spread, recoveries, and deaths caused by the pandemic across different provinces and cities of Pakistan.

## Project Overview

The project aims to:
- Analyze the trends in COVID-19 cases, recoveries, and deaths over time.
- Examine the impact of travel history and local transmission on the spread of the virus.
- Investigate the distribution of cases and recoveries across provinces and cities.
- Provide visualizations to highlight key insights and trends.

## Data Source

The dataset used in this project is stored in the file `PK COVID-19.csv`. It contains the following columns:
- **Date**: The date of the reported case.
- **Cases**: The number of cases reported on the given date.
- **Deaths**: The number of deaths reported on the given date.
- **Recovered**: The number of recoveries reported on the given date.
- **Travel_history**: The travel history of the infected individual (if available).
- **Province**: The province where the case was reported.
- **City**: The city where the case was reported.

## Analysis Steps

1. **Data Cleaning and Preprocessing**:
   - Handle missing values and duplicates.
   - Standardize column values (e.g., travel history and province names).
   - Convert date columns to appropriate formats.

2. **Exploratory Data Analysis**:
   - Analyze trends in cases, recoveries, and deaths over time.
   - Group data by month, province, and city for detailed insights.
   - Examine the impact of travel history on the spread of the virus.

3. **Visualizations**:
   - Bar plots for cases, recoveries, and deaths by month, province, and city.
   - Heatmaps to visualize the distribution of cases across provinces and months.
   - Comparative analysis of cases vs. recoveries.

4. **Key Metrics**:
   - Calculate recovery and death rates.
   - Identify provinces and cities with the highest and lowest case counts.

## Key Insights

- **Monthly Trends**:
  - Cases and deaths surged significantly in March and April 2020.
  - Recoveries showed a sharp increase in April 2020.

- **Provincial Analysis**:
  - Punjab and Sindh reported the highest number of cases and recoveries.
  - Khyber Pakhtunkhwa and Sindh had the highest death counts.

- **City-Level Analysis**:
  - Lahore and Karachi were the most affected cities in terms of cases and recoveries.
  - Dera Ghazi Khan showed a high recovery rate.

- **Travel History**:
  - Local transmission was the primary source of infections.
  - Significant cases were linked to travel history from Iran/Taftan and Tableeghi Jamaat gatherings.

## Tools and Libraries

The analysis was performed using the following tools and libraries:
- **Python**: For data processing and analysis.
- **Pandas**: For data manipulation.
- **NumPy**: For numerical computations.
- **Matplotlib** and **Seaborn**: For data visualization.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the Jupyter Notebook `Data Analysis.ipynb` and run the cells sequentially.

## Visualizations

The project includes various visualizations, such as:
- Bar plots for cases, recoveries, and deaths by month, province, and city.
- Heatmaps for case distribution across provinces and months.

## Conclusion

This project provides a comprehensive analysis of COVID-19 in Pakistan, highlighting key trends and insights. The findings can help policymakers and healthcare professionals make informed decisions to combat the pandemic effectively.

## Author

This project was developed by [Your Name]. For any questions or suggestions, feel free to contact me at [Your Email].

