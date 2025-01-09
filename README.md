# Market-Trend-Analysis-on-Housing-data-from-Hyderabad-Pune-and-Mumbai
Conducted an in-depth analysis of rental and sales data from housing.com price, BHK, area, furnishing status, and location
This project involved scraping data from housing.com to gather key real
estate information for both rentals and sales in Hyderabad, and rental data
for Pune and Mumbai. The goal was to analyze current market trends across
these cities.
Libraries Used:
BeautifulSoup: For parsing HTML.
Requests: For fetching data from the website.
NumPy: For numerical operations.
Pandas: To structure the data into DataFrames and export to CSV.
Data Collected:
Hyderabad Rentals: BHK, Price, Location, Area, Furnish status.
1. Hyderabad Sales: BHK, Price, Property Name.
2. Pune & Mumbai Rentals: Prices.
3. Data Processing:
Data organized into Pandas DataFrames for easy analysis.
Exported the data into CSV format for future use.

# IMPORTANCE OF DATA
## CLEANING
Ensuring Data Accuracy and Reliability
Here are the key benefits of data cleaning in your project:
Improves Data Accuracy: Removing duplicates and NaN values ensures
that only valid, accurate data is used for analysis, reducing the risk of
misleading results.
1. Enhances Data Consistency: Cleaned data is more consistent, ensuring
uniformity across attributes like prices, locations, and property types.
2. Reduces Data Bias: Eliminating duplicates helps prevent certain data
points from skewing the overall trends or analysis.
3. Facilitates Better Decision-Making: Clean data leads to more reliable
insights, helping stakeholders make informed decisions based on actual
market trends.
4. Optimizes Storage: Removing unnecessary or faulty data reduces the file
size, making storage and handling more efficient.

# DATA ANALYSIS
1. Descriptive Statistics
Purpose: Understand the central tendencies and variability of the
dataset.
Metrics:
Price: Mean, median, standard deviation, minimum, and
maximum values.
BHK, Bathrooms: Frequency distribution
Furnish: Count of furnished vs unfurnished properties.
Area: Average square footage.
2. Location-Based Analysis
Purpose: Identify trends across different locations.
Methods:
Price Distribution: Compare average rental prices across
locations
3. Correlation Analysis
Purpose: Determine the relationships between variables.
Methods:
Correlation between price and area (larger properties tend to cost
more).
Correlation between BHK and price.
4. Outlier Detection
Purpose: Identify unusual listings with abnormally high or low prices.
Methods:
Use box plots or Z-scores to detect listings that fall outside the
typical price range.
5. Categorical Analysis (for Furnish Status)
Purpose: Explore how furnishing status affects price.
Methods:
Use bar charts to compare the average price of furnished vs.
unfurnished properties.

# Conclusion: 
In this project, web scraping was successfully employed to collect
valuable real estate data from multiple cities, including Hyderabad, Pune,
and Mumbai. By using Python libraries such as BeautifulSoup, Requests,
and Pandas, we retrieved essential attributes like property types, prices,
and locations.
Data cleaning played a crucial role in enhancing the dataset's quality. By
removing duplicates and handling missing values, we ensured accuracy,
consistency, and reliability, which are vital for meaningful analysis. Clean
data not only avoids skewed results but also enhances the performance
of future predictive models.
Finally, the data analysis phase allowed for insightful comparisons of
housing trends across cities, providing stakeholders with valuable market
insights. This well-structured, cleaned dataset now lays the foundation for
further exploration, such as pricing predictions and expanded city
comparisons.
