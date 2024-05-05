
# Vrinda Store Analysis-Dashboard

### Dashboard Link : <iframe width="700" height="700" frameborder="0" scrolling="no" src="https://onedrive.live.com/embed?resid=C79A15996AC23D3B%21108&authkey=%21APF1GHi0xJC73co&em=2&wdAllowInteractivity=False&wdHideGridlines=True&wdHideHeaders=True&wdDownloadButton=True&wdInConfigurator=True&wdInConfigurator=True"></iframe>
## Objective

The objective of this project is to create an annual sales report for the year 2022 for Vrinda store. By analyzing the sales data, the aim is to gain insights into customer behavior, product performance, and sales trends. These insights will be used to inform strategic decision-making and drive sales growth in the year 2023.

## Problem Statement

This dashboard helps the Vrinda Store understand their customers better. Vrinda store aims to enhance its sales performance and better understand its customer base to drive growth in the upcoming year. However, the lack of comprehensive insights into their sales data for the year 2022 impedes their ability to make informed decisions. To address this challenge, the store seeks to create an annual sales report for 2022 that provides actionable insights into customer behavior, product performance, and sales trends. By analyzing this data, Vrinda store aims to devise strategic initiatives to increase sales and improve customer satisfaction in 2023.

## Steps followed 

### Step 1 : Load Data in Excel
- Import the dataset into Excel. Ensure that your dataset is in a structured format, such as CSV or Excel file

### Step 2 :Data Cleaning

- Identify and remove any errors or empty values in the dataset.
- Use Excel's data validation tools to ensure data accuracy and consistency.
- Check for any duplicate entries and remove them if necessary.

### Step 3 :Data Processing

-  Create a new column named "Age Group" to categorize customers based on their age.
- Use the formula =IF(E2>=50,"Senior",IF(E2>=30,"Adult","Young")) to assign age groups to each customer.
- Create another new column named "Month" to extract the month from the date column.
- Use the formula =TEXT(G2,"mmm") to extract the month abbreviation from the date.

### Step 4 :Creating Pivot Tables
Create pivot tables to analyze various aspects of the sales data.
- Pivot Table 1: Order vs. Sales
    - Rows: Order ID
    - Values: Sales Amount
- Pivot Table 2: Gender vs. Sum of Amount
    - Rows: Gender
    - Values: Sum of Sales Amount
- Pivot Table 3: Order Status
    - Rows: Order Status
    - Values: Count of Orders
- Pivot Table 4: Top 10 States vs. Sum of Amount
    - Rows: State (Top 10)
    - Values: Sum of Sales Amount
- Pivot Table 5: Age vs. Gender vs. Sum of Amount Spent
    - Rows: Age Group, Gender
    - Values: Sum of Sales Amount
- Pivot Table 6: Orders from Different Channels
    - Rows: Sales Channel
    - Values: Count of Orders
Once we have created Tables next part is analysis
  
### Step 5 :Analysis
- Analyze the Order vs. Sales pivot table to identify patterns or trends in sales orders

![order vs sales](https://github.com/SahilRajput99/Excel/assets/168499493/a6e15a9a-ea82-47e4-b177-8ca2e4ec31fc)

- Explore the Gender vs. Sum of Amount pivot table to understand spending patterns based on gender.

![Gender](https://github.com/SahilRajput99/Excel/assets/168499493/473d27bb-370b-4c8b-80e9-49a6b51dd14b)

- Examine the Order Status pivot table to track the distribution of order statuses.

![Order status](https://github.com/SahilRajput99/Excel/assets/168499493/901bca42-7a47-4659-9d7c-0530da6c5b29)

- Review the Top 10 States vs. Sum of Amount pivot table to identify regions with the highest sales.

![Top 10 states](https://github.com/SahilRajput99/Excel/assets/168499493/ebc26a7e-f702-4a2f-8e1c-57ea9028caa4)

- Analyze the Age vs. Gender vs. Sum of Amount Spent pivot table to understand spending behavior across different age groups and genders.

![Age vs gender](https://github.com/SahilRajput99/Excel/assets/168499493/d6f4b4d4-22c1-4b96-83bc-e229e65dda55)

- Explore the Orders from Different Channels pivot table to assess the performance of various sales channels.

![Channels](https://github.com/SahilRajput99/Excel/assets/168499493/f709ebcf-15d1-4bbb-8641-a0f2318e23ea)

### Step 6 :Interactve Dashboard

- Create a new worksheet for your dashboard.
- Insert the pivot tables and other visualizations you created earlier onto the dashboard.
- Add slicers, filters, and interactive elements to allow users to explore the data dynamically.
- Format the dashboard to make it visually appealing and easy to navigate.

# Snapshot of Dashboard

![Dashboard](https://github.com/SahilRajput99/Excel/assets/168499493/4cf48e23-75ff-4af4-99bd-67b9f7e98ce4)

# Insights

Following are the insights
- Women are more likely to buy compared to men:

Women account for a higher percentage of purchases compared to men, indicating a potential opportunity to tailor marketing strategies and product offerings to better cater to female customers' preferences and needs.

- Top Three States Contributing to Sales:

Maharashtra, Karnataka, and Uttar Pradesh are the top three states contributing to sales, comprising 65% of total sales. Focusing on these regions can help optimize marketing efforts and allocate resources effectively to capitalize on existing customer demand.

- 35% of Sales from Adult Age Group (30-49 years):

The adult age group (30-49 years) constitutes 35% of total sales, highlighting the importance of targeting this demographic segment with products and promotions that resonate with their preferences and lifestyle.

- Max Contribution from Age Group 25-49 years:

The age group between 25 and 49 years contributes the most to sales, with 50% of total sales coming from customers aged 25-49 years. Tailoring marketing campaigns and product assortments to appeal to this age range can help drive further growth.

- Max Contribution from Amazon, Flipkart, and Myntra Channels:
Amazon, Flipkart, and Myntra channels collectively contribute 80% of total sales. Investing in strategic partnerships and promotional activities with these e-commerce platforms can help maximize reach and visibility among online shoppers.

# Recommendations:
Vrinda Store should prioritize marketing and product offerings towards women customers aged 30-49 residing in Maharashtra, Karnataka, and Uttar Pradesh. This demographic represents a significant portion of the store's current customer base.

To further enhance sales, Vrinda Store can explore offering office wear coupons redeemable on major online marketplaces like Amazon, Myntra, and Flipkart. This strategy targets the identified customer segment with a product category likely relevant to their lifestyle and leverages the dominant sales channels.

By implementing these data-driven recommendations, Vrinda Store can attract new customers, retain existing ones, and ultimately achieve its sales growth objectives.
