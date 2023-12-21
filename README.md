# Capstone_Project-Customer-Segmentation
**Objective:** Segment e-commerce website customers and propose marketing strategies for the target segment

| Feature          | Dataset(CSV)         |   Description                            |                               
|:----------------:|:----------:|:-------------------------------------:|
| **CustomerID**   |Sales, Customer|  The id of the customer |
| **Transaction_ID** |Sales| The id of the transaction |
| **Transaction_Date** |Sales| Date of transaction |
| **Product_SKU** |Sales, Products| The id of the product |
| **Product_Description** |Sales, Products| Product name |
| **Product_Category** |Sales, Products| Category of the product |
| **Quantity** |Sales| Amount of purchase |
| **Avg_Price** |Sales| Average price of the product |
| **Delivery_Charges** |Sales| Delivery charge of the transaction |
| **Coupon_Status**|Sales| Status of coupon usage: Used, Not used, Click |
| **Month**|Coupon| Month name |
| **Coupon_Code**|Coupon| Coupon code |
| **Discount_pct**|Coupon| Discount point based on coupon code |
| **GST**|Tax| Tax amount percentage based on product category |
| **Gender**|Customer| Gender of the customer |
| **Location**|Customer| Location of the customer |
| **Tenure_Months**|Customer| Duration of the customer staying with the store |
| **Offline_Marketing_Expense**|Marketing Expenditure| Offline marketing expense such as magazine ads, billboards |
| **Online_Marketing_Expense**|Marketing Expenditure| Online marketing expense such as online ads |

## Problem Statement
The marketing team of the Google Merchandise website wants to identify different segments from its pool of customer data, understand each segment’s behavior, determine the segment that marketing team should invest its marketing expenditure to boost their spending and propose marketing tactics for the chosen segment.


## Points to be addressed
1. Identify different segments of customers
2. Understand each customer segment's behavior
3. Choose a customer segment
4. Determine marketing tactics for the chosen segment

## Model Evaluation
### K-Means Clustering:
    - The result is 8 segments and data is distributed higher in Segment1, Segment2, Segment5, and Segment6. So focus on 4 of these segments for higher return on investment.
    - Revenue per segment comparison: Segment1 and Segment6 generate the lowest revenue
    - Tenure days per segment comparison: Segment1, 3, and 6 tenure days are the lowest
    - Days since last purchase per segment comparison: Segment1, 2, 3, and 5 contain customers that purchase only once. Segment6 has highest average days
    Frequency per segment comparison: Segment1 and 6 are the lowest frequently purchased groups


### Final Evaluation:
    - Segment 1 and Segment 6 are the low-valued customers revenue generated. Majority of customers resided in Chicago, California, and New York. The majority is female. Their top purchased product group is Google, with top categories are Office, Drinkware, Apparel, Lifestyle, and Nest. The 5 popular products are Maze pen, Google 22 oz water bottle, Google sunglasses, Sport bag, Google metallic notebook.

## Recommendation for the marketing team:  

    - Targeted campaign email marketing - email marketing for specific audiences
    - Specified the customers' emails as Segment 1 and Segment 6 
    - Email content: 
        - Re-engage customers with their top product categories: Office, Drinkware, Apparel and top product group: Google
        - Promoting unpopular product categories such as Accessories, Google Waze, Gift Cards and unpopular product groups: Youtube, using special promotions such as price reduction 
        - Bundle deals 
    - Increase email marketing sent out in November and December for Black Friday and Christmas events, and April as the lowest number of customers month
    - Allocate higher email marketing resources to specific demographics to increase awareness and purchases: 
        - Gender: Male 
        - Location: New Jersey and Washington DC

    
