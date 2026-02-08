* INSY8311SQL/PL-ASSIGNMENT-1-JACKSON-MANZI-GROUP-B-SUNDAY.
* SQL JOINs & Window Functions Assignment

**Business Problem
About Business Context

Simba Supermarket is an online and physical retail company operating even in the e-commerce industry.
The sales and operations department relies on transactional data to track customer orders, product demand, and overall sales performance.

 Data Challenge

Although Simba Supermarket records: all customer orders, management does not have a clear view of all booked products, the most purchased products and some time a customer may even order a products that are not even present in stock, or the customers who place the highest number of orders.this result in hardy to monitor sales performance,bad reputation and recognition issue to customers...

Expected Outcome

My goal for this showings is to identify all booked products to avoid more booking on same product which destroy reputatios. determine the most frequently purchased products for better inventory management and recognize customers for sales boosting.

** Success Criteria
1. Success Criterion: (Ranking)

My aim: Identify the most orded products in all orders from customer using ranking functions for better stock planning and management.
(window function: RANK())

2.Success Criterion: (Running Total)

My aim: Calculate  totals of sales over time to understand sales rising which is happening.
(window function: SUM() OVER())

3.Success Criterion: (Period Comparison)

My aim: Compare present product sales with previous time to check increases or decreases in demanding.
(window function: LAG() or LEAD())

4.Success Criterion: (Customer dividing)

My aim: Divide customers into four groups based on their order frequency to identify mostly ordering customers.
(window function: NTILE(4))

5.Success Criterion: (Moving Average)

My aim: Analyse average sales occuring over the  time using  averages to support predictions and availability of products in stocks.
(window function: AVG() OVER())

** Database Schema
My schema here is going to help in understanding more about booked products, customer orders, and purchasing move at Simba Supermarket.
here we need three main relations(tables): Customer relation, Product relation and 0lso Order relation.

The Customer relation stores customer informations, the Product relation stores product and stock informations, and the Order relation records all product being booked  by customers.
The tables are connected using primary and foreign keys for JOIN operations and window function to be applicable.
*** ER Diagram
[ER Diagram](er_diagram.png)

** Part A: SQL JOINs

** INNER JOIN
- Purpose:
- Business Interpretation:

** LEFT JOIN
- Purpose:
- Business Interpretation:

*** RIGHT / FULL JOIN
- Purpose:
- Business Interpretation:

*** FULL OUTER JOIN
- Purpose:
- Business Interpretation:

*** SELF JOIN
- Purpose:
- Business Interpretation:

** Part B: Window Functions

*** Ranking Functions
- Interpretation:

*** Aggregate Window Functions
- Interpretation:

*** Navigation Functions
- Interpretation:

*** Distribution Functions
- Interpretation:

** Results Analysis
- Descriptive:
- Diagnostic:
- Prescriptive:

** References
(List your references)

** Integrity Statement
All sources were properly cited. Implementations and analysis represent original work.
