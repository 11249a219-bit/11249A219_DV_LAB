Experiment No. 8: Data Visualizations in Tableau — Charts, Graphs, and Data Mapping
Aim
To create and customize different types of charts, graphs, and geographical maps in Tableau to represent data clearly and extract meaningful business insights.

Introduction
Data visualization transforms raw data into graphical representations that make patterns and comparisons easier to understand. Tableau provides an interactive environment for creating visualizations by placing fields on shelves and selecting suitable chart types.

Different visualizations serve different purposes. Bar charts compare categories, pie charts represent proportions, line charts illustrate trends or ordered comparisons, and geographical maps display data according to location.

Types of Visualizations
Bar Chart: Compares values across different categories.
Pie Chart: Shows the contribution of individual categories to a total.
Line Chart: Displays changes across an ordered dimension.
Geographical Map: Represents values across cities or regions.
Software Required
Tableau Public
A CSV dataset containing sales and geographical information
Algorithm
Start Tableau Public.
Connect to the sales dataset stored in CSV format.
Verify the field names and data types.
Create a worksheet for each required visualization.
Drag the appropriate dimensions and measures to Rows, Columns, or the Marks card.
Choose a suitable chart type using Show Me or the Marks card.
Customize labels, colors, and titles for better readability.
Create a geographical map using the City field.
Examine the resulting visualizations and compare the displayed values.
Save or publish the completed workbook.
Sample Dataset
Save the following data as sales_data.csv.

City,Region,Sales,Quantity
Hyderabad,South,55000,2
Delhi,North,20000,3
Mumbai,West,30000,4
Chennai,South,25000,2
Kolkata,East,15000,5
Bangalore,South,40000,3
Procedure
1. Create a Bar Chart
Open a new worksheet.
Drag City to Columns.
Drag Sales to Rows.
Select Bar Chart from Show Me, if necessary.
Enable mark labels if desired.
Give the worksheet the title Sales by City.
Observation: The bar heights represent sales values for the six cities, making comparisons straightforward.

2. Create a Pie Chart
Open another worksheet.
Drag Region to Color in the Marks card.
Drag Sales to Angle.
Change the Marks type to Pie.
Drag Sales to Label if you want to display the values.
Name the worksheet Regional Sales Contribution.
Observation: Each slice represents a region's contribution to total sales. Because some regions contain multiple cities, Tableau aggregates the sales values for each region.

3. Create a Line Chart
Create a new worksheet.
Drag City to Columns.
Drag Sales to Rows.
Select Line as the Marks type.
If needed, sort City in a meaningful order.
Name the worksheet Sales Across Cities.
Observation: The line connects sales values across the selected city order. Since cities are categorical rather than time-based, this chart shows an ordered comparison, not a time trend.

4. Create a Geographical Map
Open a new worksheet.
Verify that Tableau recognizes City as a geographical field.
If necessary, right-click City, select Geographic Role, and choose City.
Double-click City to generate a map.
Drag Sales to Color or Size on the Marks card.
Add Region to Tooltip or Color if useful.
Name the worksheet Geographical Sales Distribution.
Observation: The map displays the recognized cities and uses color or marker size to represent sales. If Tableau cannot identify a city correctly, check its geographical role and add suitable location context.

Expected Output
The completed Tableau workbook should contain four worksheets:

Sales by City — a bar chart comparing sales values.
Regional Sales Contribution — a pie chart showing the regional share of sales.
Sales Across Cities — a line chart comparing sales in the chosen city order.
Geographical Sales Distribution — a map showing sales by location.
Result
Thus, different charts, graphs, and geographical visualizations were created using Tableau. The bar and pie charts supported category and proportion comparisons, the line chart displayed values across an ordered dimension, and the map provided a geographical view of sales performance.
