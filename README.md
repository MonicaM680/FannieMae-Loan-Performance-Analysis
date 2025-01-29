# FannieMae-Loan-Performance-Analysis
## Overview

This project analyzes the Fannie Mae Single-Family Loan Performance Data, focusing on mortgage loan performance, risk, and trends over time. By using PySpark and other data analysis tools, the project aims to provide insights into borrower behaviors, loan default risks, and various other mortgage-related factors.

## Project Objectives

The primary objectives of this project include:

### 1. FICO Score Analysis
- Compare the average FICO scores across two assigned years.

### 2. Delinquency Trends
- Analyze monthly delinquency rates (30, 60, and 90 days past due) and how they vary by loan term.

### 3. Credit Score Distribution
- Create a stacked bar chart showing credit score distribution by mortgage type and state for first-time buyers.

### 4. Correlation Analysis
- Investigate relationships between FICO score, Loan-to-Value (LTV) ratio, and interest rates with loan status.

### 5. Loan Status Distribution
- Examine distributions of FICO scores, LTV ratios, and interest rates across different loan statuses (performing, delinquent, defaulted).

### 6. Default Rate Trends
- Assess how default risks have evolved by comparing loans originated in different quarters.

### 7. Loan Recovery Analysis
- Evaluate the percentage of loan amounts recovered after defaults via foreclosure or other means.

### 8. Property Price Trends
- Plot statistics (average, median, variance) of property price changes over time, grouped by month.

## Data Source

The dataset used in this project is sourced from the Fannie Mae Single-Family Loan Performance Data, which is publicly available on the Fannie Mae website.

The dataset includes:

- **Acquisition Data**: Static loan characteristics at the time of origination (e.g., credit scores, loan terms).
- **Performance Data**: Monthly updates on loan performance, including delinquency status, payments, and modifications.

### Data Coverage:
- **Time Period**: 2000 - 2023
- **Updates**: Quarterly
- **Granularity**: Loan-level data

## Tools and Technologies Used

- **Programming Language**: Python
- **Big Data Processing**: PySpark (Google Colab)
- **Data Visualization**: Matplotlib, Seaborn
- **Data Storage**: Parquet (for efficient processing)
- **Documentation**: Markdown within notebooks

## Project Workflow

1. **Mount Google Drive**:
   - Upload the dataset to your Google Drive and mount it in Google Colab.

2. **Load and Process Data**:
   - Convert the dataset from CSV to Parquet format for efficient processing.
   - Use PySpark to read and process the data.

## Contributing
Feel free to fork this repository and submit pull requests with improvements.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, reach out to **Monica Muniraj** at [monicamuniraj12@gmail.com](mailto:monicamuniraj12@gmail.com).
