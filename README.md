# black_friday_sales_analysis

Research Questions:

1.Are married customers purchasing more products on average compared to unmarried customers, and does this trend differ by city tier?
2.What is the relationship between age and purchase behavior? Do different age groups exhibit distinct purchasing patterns?
3.How does the length of stay in the current city influence product purchases?

Data Preparation and Cleaning:

[Describe any data cleaning steps performed here]

## SQL Queries
```-- Query 1: Average products purchased by marital status and city tier
SELECT 
    City_Category, 
    CASE 
        WHEN Marital_Status = 1 THEN 'Married'
        ELSE 'Unmarried' 
    END AS Marital_Status, 
    AVG(Total_Products) AS Avg_Products_Per_Marital_Status
FROM (
    SELECT 
        City_Category, 
        Marital_Status, 
        SUM(Product_Category_1) + SUM(Product_Category_2) + SUM(Product_Category_3) AS Total_Products
    FROM 
        black_friday_data
    GROUP BY 
        City_Category, 
        Marital_Status
) AS City_Marital_Status_Totals
GROUP BY 
    City_Category, 
    Marital_Status;

-- Query 2: ... (Add SQL query for analyzing age and purchase behavior here)
-- Query 3: ... (Add SQL query for analyzing the impact of stay duration on purchases here)
```

## Data Visualization:

Question 1: Are married customers purchasing more products on average compared to unmarried customers, and does this trend differ by city tier?

[Include a screenshot of the Tableau visualization here]

Key Observations:
[Summarize your key observations from the visualization, e.g., "Married customers in City Category A tend to purchase more products on average compared to unmarried customers."]
Insights:

[Summarize the key findings and insights from the analysis of the first question]
[Summarize the key findings and insights from the analysis of the second question]
[Summarize the key findings and insights from the analysis of the third question]
Limitations and Future Work:

[Mention any limitations of the analysis or data]
[Suggest potential areas for future research or analysis]
