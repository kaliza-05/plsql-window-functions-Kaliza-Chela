STEP 1: PROBLEM DEFINITION
Business context: A clothing store that works in retail industry that sells clothes, shoes,jewelry, and perfumes. The sales department wants to know how those products perform on the market, and how trends evolve.
Data challenge: The sales department collects large amounts of data but they struggle to know how the products perform on the market, customer segments and when products are most in demand which is needed for better decision making.
Expected outcome: To identity the high perfoming product on the market and monitor sales changes and growth to provide insights which will be used in better data decision making. 
STEP 2: SUCCESS CRITERIA
To identify the top selling products on the market in the region using RANK()
To track cumulative sales performance per month using SUM() OVER()
To compare sales from one month to another  to determine sales changes using LAG()/LEAD()
To group customers into spending quartiles using NTILE(4) 
To know the short-term analysis with a window frame using AVG() OVER()
STEP 6: RESULT ANALYSIS
1. Descriptive – What happened?
The rank functions indicated that some customers consistently spend more, thereby becoming significant money-makers.
The running totals determined that sales steadily improved over the course of the year, with clear highs for mid-year sales.
Navigation functions indicated changes months with good growth and others with slight decline.
Customer segmentation (NTILE) split buyers into quartiles, pointing out a small number of high spenders (top quartile) compared to lots of moderate or low spenders.

2. Diagnostic – Why did it happen?
Customers with good performance tended to buy high-end products (such as branded dresses or perfumes), which improved their ranking.
Sales peaks coincided with certain product launches (e.g., high-end products such as Versace and YSL), identifying product mix drives trends.
Dips in sales overlapped with months with fewer transactions — perhaps due to seasonal demand, low stocks, or lack of promotions.
Customer segmentation revealed that while most customers spend moderately, some minority of customers generates most of the revenue, confirming the "80/20 rule" (Pareto principle).

3. Prescriptive – What next?
Identify top customers: Create loyalty schemes or customized offers for top spenders to retain them.
Boost mid-spender spend: Reward quartile 2–3 spenders with targeted offers to upgrade them into higher spend levels.
Seasonal tactics: Use comparison of why certain months are sub-par and discount, events, or campaigns in those slow months.
Product strategy: Overstock near top-performing products with consistent high demand (shoes and perfumes) and adjust prices or promotions on sub-par categories.

STEP 7:REFERENCES
W3Schools. SQL Window Functions. https://www.w3schools.com/sql/sql_ref_window_functions.asp
Oracle. Analytic Functions (Window Functions) Overview. Oracle Database SQL Language Reference. https://docs.oracle.com/en/database/oracle/oracle-database/21/sqlrf/Analytic-Functions.html
MySQL. MySQL 8.0 Reference Manual: Window Functions. https://dev.mysql.com/doc/refman/8.0/en/window-functions.html
Mode Analytics. A Beginner’s Guide to SQL Window Functions. https://mode.com/sql-tutorial/sql-window-functions
Redgate. Practical Examples of SQL Window Functions. https://www.red-gate.com/simple-talk/sql/t-sql-programming/practical-examples-of-sql-window-functions/
GeeksforGeeks. SQL | Window Functions. https://www.geeksforgeeks.org/sql-window-functions/
PostgreSQL Global Development Group. Window Functions Tutorial. PostgreSQL Documentation. https://www.postgresql.org/docs/current/tutorial-window.html
SQLShack. Using SQL Server Window Functions: Ranking, Aggregate, and Analytical Functions. https://www.sqlshack.com/sql-server-window-functions-ranking-aggregate-analytical-functions/
Claude AI. (2025). SQL code generation and query explanations. Anthropic AI assistant.
Vertabelo Academy. SQL Window Functions: ROW_NUMBER(), RANK(), NTILE(), LAG(), LEAD(). https://academy.vertabelo.com/blog/sql-window-functions

"All sources were properly cited. Implementations and analysis represent original work. No AI-generated content was copied without attribution or adaptation."

