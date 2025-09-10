# Revenue-Insight-Analytics
This project is designed to deliver actionable insights into our sales and support calls. By analyzing call volume, representative effectiveness, and customer feedback, the dashboard helps us identify top performers, address customer pain points, and drive revenue growth.
# link (https://1drv.ms/x/c/7b97ba1b95b18ec7/EQFUUOmtdnpDsrBOv5S3rnEBES06LrY10_ittw6xmQ-Wrw?e=HWVDp9)
## Key Insights
### Overall Performance
High Call Volume: You handle a significant number of calls, with a total of 1000 calls logged.
Strong Revenue: The total amount generated is ₹96,623, which is a great result.
Average Call Duration: The average call duration is quite long at 89,850 seconds (or around 25 hours), which seems unusual. This could be a data entry error or an interesting outlier.
Good Customer Satisfaction: The average rating is 3.9 out of 5, which indicates generally positive customer feedback. A total of 307 calls received a 5-star rating.
Monthly Trends
The monthly call volume is cyclical, with peaks in the first half of the year (Jan-Jun) and a smaller peak in November. There are dips in the summer months (July-Aug) and a low point in December. This could be due to seasonal business or marketing campaigns.
Call Representative Performance
R05 appears to be a top performer. This representative has the highest grand total in the table (₹20,104) and is shown with a high number of calls in the bar chart.
R01 has the lowest total revenue (₹13,415) and appears to have the lowest call volume in the bar chart.
The data table shows a breakdown of representatives across different cities (Cincinnati, Cleveland, Columbus), but there's a disconnect between the representative names (R01, R02, etc.) and the city-based entries (C0001, C0002, etc.).
5-Star Calls
The majority of your 5-star calls come from ratings 4 and 5. This is a positive sign, as it indicates a strong base of highly satisfied customers.
Important Questions & Potential Solutions
### 1. Data Integrity
Question: The total duration is listed as 89,850 seconds. Is this a total or an average? Is the unit correct? This number is exceptionally high and could be a data input error.
Solution: Verify the source data for call duration. If the number is incorrect, correct it to ensure your calculations are accurate. If it is an average and not a total, then it should be presented with a more appropriate unit (e.g., minutes).
### 2. Performance Metrics
Question: Why are some representatives (like R05) outperforming others (like R01)? Is it due to call volume, the quality of their calls, or the type of calls they handle?
Solution: To understand this, you need to add more metrics to your dashboard. Consider including:
Average Call Duration per Rep: See if top performers spend more time on calls.
Average Rating per Rep: Do top performers also have higher customer satisfaction ratings?
Revenue per Call per Rep: This will show you who is most effective at generating revenue on each call.
### 3. City & Representative Data
Question: Why is the representative data in the bar chart labeled R01-R05, while the data table uses codes like C0001-C0015 within cities? Is there a direct link between these two?
Solution: Make sure your data is structured consistently. You should either use the same naming convention for representatives across all charts or add a field that links the representative ID (e.g., C0001) to the representative's name (e.g., R01). This will make the dashboard much easier to interpret.
### 4. Call Trends
Question: What causes the significant drop in calls during the summer months and the end of the year?
Solution: Investigate this further by correlating your data with external factors. You could analyze it against marketing campaigns, product launches, or even seasonal holidays. Understanding the cause will help you develop strategies to smooth out these trends, such as launching targeted campaigns during low-volume periods.
### 5. Customer Satisfaction
Question: Why did a significant number of calls receive ratings of 1, 2, and 3? What were the key issues or reasons for these lower ratings?
Solution: Create a separate report or a filterable view that lets you analyze calls with low ratings. You could filter by representative, call type, or keywords from the call notes to identify common issues. This could help you provide targeted training to your team or improve specific processes.
