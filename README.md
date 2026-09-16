# Online Retail Analysis (Tableau)

This was an individual task for my BUSA 8031 Business Analytics unit, based
on the Forage Tata Data Visualization job simulation. The brief was to take
a messy online retail dataset and turn it into visualizations that answer
different questions for a CEO (focused on overall revenue and growth) and
a CMO (focused on customers and purchasing behavior).

## What's in here

- `Online_Retail_Analysis.twbx`, the Tableau workbook with all the
  visualizations, open it in Tableau (or Tableau Public/Reader) to explore
  the charts
- `BUSA8031_Online_Retail_Personal_Report.pdf`, my write up covering the
  approach, the findings, and what I took away from the simulation
- `Online_Retail_Data_Set.csv.zip`, the dataset, zipped up since the raw
  file is too big to upload as is, unzip it to get the CSV


## What I did

I cleaned the dataset in Excel first, removing rows with negative
quantities or zero and negative unit prices, then added a revenue column
by multiplying quantity by unit price. From there I built four
visualizations in Tableau: a monthly revenue trend, a bar chart of the top
10 countries by revenue (excluding the UK, since it dominates the data), a
bar chart of the top 10 customers by revenue, and a map showing product
demand by country.

## What stood out

Revenue held fairly steady through the first eight months of the year,
then jumped sharply from September and peaked in November before the
partial December data drops off. Sweden stood out as an exception in the
country chart, it doesn't sell the highest quantity but still lands in the
top 10 for revenue, which points to higher priced items rather than
volume. On the customer side, a small number of customers account for a
disproportionate share of revenue, which is good for the top line but
something I'd flag as a concentration risk worth managing.

## Tools

Built with Tableau and Microsoft Excel. 
