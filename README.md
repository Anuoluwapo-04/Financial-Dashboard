# Financial-Dashboard
This financial dashboard provides insights into the company's sales and profitability, highlighting performance across different metrics.
## Project Goal
The goal of this Power BI dashboard is to analyze the company’s financial performance using a sample dataset provided in Microsoft Power BI. It aims to create a visually appealing dashboard that offers an overview of the company's profitability, enabling stakeholders to make informed business decisions.

## Data Cleaning or Preparation
- Performed data transformation using Power Query Editor by removing columns such as COGS, net sales, and gross sales, and employed DAX calculations to derive these values.
- Added calculated measures and a date table to enhance the depth of analysis and support more detailed insights.

## Exploratory Data Analysis
EDA involved exploring the Financial data to answer key questions such as:
- What is the monthly profit trend?
- Which region is performing best in terms of profitability?
- Which days are the peak profit periods?

## Data Ananlysis
Some of the KPI's and DAX used includes:
- Transactions = COUNTROWS(financials)
- Total COGS = SUMX(financials,financials[Units Sold]*financials[Manufacturing Price])
- Gross sales = SUMX(financials,financials[Units Sold]*financials[Sale Price])
- Net Sales = [Gross sales]-[Total Discount]

## Data Visualization

![image](https://github.com/user-attachments/assets/477198c6-8c7a-4c72-b5d5-19ff651a411d)

## Results
1. **Total Profit:** The company has a total profit of £12M, with the highest contributions coming from Small Business (£26M) and Government (£8M) segments.
2. **Monthly Profit Trend:** Profit varies significantly by month, with a notable dip in June. However, the end of the year shows a strong upward trend, especially in December.
3. **Day of the Week Performance:** Monday is the most profitable day (£4.2M), whereas Sunday shows a significant loss (-£1.1M). This suggests varying customer behavior throughout the week.
4. **Yearly Comparison:** The majority of the profit (88.18%) comes from the year 2013, indicating a significant decrease in profit the following year.
5. **Geographical Performance:** Germany contributes the most to total profit (£3,264,536), whereas France is the lowest-performing country (£1,825,690).
6. **Discount Impact:** High discount levels lead to a loss (-£4M), indicating that discounting strategy needs review to prevent profit erosion.

## Recommedations
1. Increase marketing efforts and resources towards the Small Business and Government segments to maximize profits.
2. Explore reasons behind the poor performance on Sundays and consider operational changes or targeted promotions to boost Sunday sales.
3. Review and adjust the discount policies to ensure they are not negatively impacting profitability, especially the high discount bands.
4. Expand operations and marketing efforts in Germany while examining factors contributing to France's lower performance to improve results.
5. Capitalize on the year-end profit increase by planning strategic sales and marketing campaigns around this time to maximize profit.





