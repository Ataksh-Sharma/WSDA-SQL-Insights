# WSDA-SQL-Insights

This repository contains a collection of SQL queries used for analyzing customer and invoice data within a music sales database. The following are the descriptions of the queries implemented:

1. Customer Information Query

Purpose: Displays the first and last names, and email addresses of all customers in the database.

Output: Returns customer names and email addresses, sorted by last name in descending order, with a limit of 10 results.

2. Invoice Analysis: Songs Purchased and Invoice Totals

Purpose: Retrieves invoice details for customers who made purchases within specific price ranges.

Output: Filters invoices based on total amounts, such as 0.99, between 1.98 and 5.00, or exactly 1.98 and 3.96.

3. Invoice Analysis by Billing City

Purpose: Retrieves invoices billed to customers from specific cities.

Output: Filters invoices based on billing city, such as Brussels, Orlando, and Paris, and orders the results by invoice date.

4. Invoices by City Starting with B or Containing B

Purpose: Analyzes invoices billed to cities that start with 'B' or contain 'B'.

Output: Filters invoices based on city name patterns using the LIKE operator.

5. Invoices on Specific Date

Purpose: Retrieves invoices billed on a specific date (2010-05-22).

Output: Filters invoices based on the specified invoice date.

6. Invoice Analysis with Specific Conditions

Purpose: Filters invoices with totals less than 3.0, or billed to cities starting with 'P' or 'D'.

Output: Retrieves invoices with conditions on the total amount and billing city.

7. Sales Categorization

Purpose: Categorizes sales into different groups based on the total amount.

Output: Assigns each invoice to a sales category (Baseline Purchase, Low Purchase, Target Purchase, or Top Performer) and retrieves the top performers.

8. Top 10 Sales by Employee

Purpose: Retrieves the top 10 sales for each customer, along with the employee responsible for each sale.

Output: Displays customer names, employee names, and sales totals for the top 10 highest sales.

9. Mailing List for US Customers

Purpose: Creates a mailing list for US-based customers.

Output: Combines customer information into a formatted mailing address and provides postal code details.

10. Average Invoice Total by City

Purpose: Calculates the average total of invoices by city, and optionally by country.

Output: Displays average totals for invoices, grouped by billing city and country.

11. Invoices Below Global Average

Purpose: Retrieves invoices with totals below the rounded global average total.

Output: Filters invoices with totals below the calculated global average and sorts them by total in descending order.

12. Invoice Details After Specific Invoice Date

Purpose: Retrieves invoice details for invoices with dates later than a specific invoice.

Output: Displays billing details for invoices after the date of InvoiceId 251.

13. Average Invoice Total by City and Global Average

Purpose: Displays the average invoice total by city and the global average for all invoices.

Output: Groups the results by billing city and shows the global average.

14. Invoice Details for Specific Invoice Dates

Purpose: Retrieves invoice details for specific invoice dates.

Output: Filters results to match the dates for InvoiceIds 251, 252, and 254.

15. Tracks Not Included in Any Invoice Line

Purpose: Identifies tracks that are not included in any invoice line.

Output: Displays track details for tracks not present in the InvoiceLine table.

16. Create View for Track and InvoiceLine Details

Purpose: Creates a view that combines track details with invoice line data.

Output: Defines a view joining InvoiceLine and Track based on the TrackId.

17. DML Operations: Insert, Update, Delete

Purpose: Demonstrates Data Manipulation Language (DML) operations for inserting, updating, and deleting data in the Artist table.

Output: Adds a new artist, updates an existing artist, and deletes an artist.

18. Customer Sales Ranking and Cumulative Sales

Purpose: Ranks customers by total sales and calculates their cumulative sales over a specified period.

Output: Displays customer details, their rank based on sales, and cumulative sales for each customer.

19. Customer Sales with CTE (Common Table Expressions)

Purpose: Uses Common Table Expressions (CTEs) to calculate the total sales for each customer and rank them based on total sales.

Output: Displays the ranked customers by total sales.
