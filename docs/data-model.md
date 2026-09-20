# Data Model

The report's model diagram contains three tables:

  -----------------------------------------------------------------------
  Table                               Role in the report
  ----------------------------------- -----------------------------------
  Orders                              Main transactional table used for
                                      sales, profit, quantity, orders,
                                      products, customers, dates,
                                      categories, regions, states, and
                                      returns analysis

  People                              Person/sales-representative
                                      information used in customer and
                                      regional analysis

  Returns                             Return-related information used by
                                      the returns analysis page
  -----------------------------------------------------------------------

## Main Orders fields/measures referenced by the report

-   Order_Date
-   Product_Name
-   Category
-   Sub-Category
-   Customer_Name
-   Region
-   State
-   Segment
-   Total Sales
-   Total Profit
-   Total Orders
-   Total Quantity
-   Average Order Value
-   Profit Margin %
-   Total Products
-   Total Categories
-   Total Sub Categories
-   Average Sales per Product
-   Total Returned Orders

## People field referenced

-   Person

## Analytical Areas

The model supports four major analytical areas:

1.  Overall sales and profitability
2.  Product performance
3.  Customer and geographic performance
4.  Returns analysis

The repository does not include a separate raw-data file because the
source/model data is embedded in the Power BI report.
