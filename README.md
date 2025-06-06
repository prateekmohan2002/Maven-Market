# Maven-Market

Insert a Matrix visual to show Total Transactions, Total Profit, Profit Margin, and Return Rate by Product_Brand (on rows)

Add conditional formatting to show data bars on the Total Transactions column, and color scales on Profit Margin (White to Green) and Return Rate (White to Red)
Add a visual level Top N filter to only show the top 30 product brands, then sort descending by Total Transactions

Add a KPI Card to show Total Transactions, with Start of Month as the trend axis and Last Month Transactions as the target goal

Update the title to "Current Month Transactions", and format as you see fit
Create two more copies: one for Total Profit (vs. Last month Profit) and one for Total Returns (vs. Last Month Returns)
Make sure to update titles, and change the Returns chart to color coding to "Low is Good"

Add a Map visual to show Total Transactions by store city

Add a slicer for store country 
Under the "selection controls" menu in the formatting pane, activate the "Show Select All" option
Pro Tip: Change the orientation in the "General" formatting menu to horizontal and resize to create a vertical stack (rather than a list)

Next to the map, add a Treemap visual to break down Total Transactions by store country

Pull in store_state and store_city beneath store_country in the "Group" field to enable drill-up and drill-down functionality

Beneath the map, add a Column Chart to show Total Revenue by week, and format as you see fit

Add a report level filter to only show data for 1998
Update the title to "Weekly Revenue Trending"

In the lower right, add a Gauge Chart to show Total Revenue against Revenue Target (as either "target value" or "maximum value")

Add a visual level Top N filter to show the latest Start of Month
Remove data labels, and update the title to "Revenue vs. Target"

Select the Matrix and activate the  Edit interactions option to prevent the Treemap from filtering


Select "USA" in the country slicer, and drill down to select "Portland" in the Treemap

Add a new bookmark named "Portland 1000 Sales"
Add a new report page, named "Notes"
Insert a text box and write something along the lines of "Portland hits 1,000 sales in December"
Add a button (your choice) and use the "Action" properties to link it to the bookmark you created
Test the bookmark by CTRL-clicking the button
Find 2-3 additional insights from the Topline Performance tab and add new bookmarks and notes linking back
