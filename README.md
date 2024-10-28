**Customer-Segmentation_Analysis-MileStone_1**


**overview:**

The goal of this project is to utilize Power BI to segment customers, enabling businesses to gain a deeper understanding of their customer base through the analysis of purchasing behavior, demographics, and preferences. This segmentation will be derived from customer, transaction, and product data, providing businesses with the opportunity to enhance their marketing, sales, and customer service strategies in various regions.

**Datasets taken into Actions**

1) The customers.csv file includes information such as customer age, gender, location, total spend, loyalty points, and preferred payment method.
2) In the transactions.csv file, you can find the transaction history, purchase frequency, total spend, shipping addresses, and delivery address.
3) Details about product categories and purchase information are stored in the products.csv file.
4) The regions.csv file holds sales details across different regions.


**CUSTOMER SEGMENTATION ANALYSIS CREATION**

**Data Cleaning Steps**

1) Loading Datasets Utilize the "Get Data" function in Power BI to import the necessary datasets such as customers, transactions, and products. In the Power Query Editor, ensure data cleanliness by:
a) Removing any duplicate entries.
b) Addressing any missing values.
c) Verifying the appropriate data types for all columns.
2) Establishing Connections Create associations between the datasets: Connect the Customer Dataset and Transaction Dataset using the CustomerID column. If utilizing a Product Dataset, establish a link to the Transaction Dataset through the ProductID column.
3) Generating Additional Columns RFM Analysis: Introduce new columns for: Recency: Compute the number of days since the most recent purchase for each customer. Frequency: Calculate the total transaction count per customer. Monetary Value: Aggregate the total expenditure made by each customer. 4.Demographic Segmentation: Age Groups: Customers are categorized into predefined groups based on their age, such as 18-25 and 26-35. Loyalty Points: Customers are grouped into low, medium, or high loyalty tiers according to their loyalty points. Payment Methods: Customers are segmented based on their preferred payment method, such as PayPal or credit card. #Conclusion The datasets have undergone successful cleaning and standardization, resulting in consistent, error-free, and well-structured data in each dataset, which can be utilized for analysis and reporting in Power BI.
