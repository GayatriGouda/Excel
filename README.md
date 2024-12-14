
# Food waste analysis
This  analysis outlines a simple, effective method for analyzing food
waste using Microsoft Excel. We'll explore key steps and visualizations that
can help you identify waste patterns, pinpoint areas for improvement, and
make informed decisions to reduce your food waste footprint.

1. Analyze Wasted Quantity by Food Item
•	Objective: Identify food items with the highest waste.
•	Steps:
1.	Sort the dataset by the "Wasted Quantity (kg)" column in descending order.
2.	Use a pivot table:
	Rows: Food Item
	Values: Sum of Wasted Quantity (kg)
3.	Identify the top items contributing to waste.
______________
2. Calculate Waste Percentage.
•	Objective: Understand the proportion of waste compared to purchase.
•	Steps:
1.	Add a new column: "Waste Percentage".
2.	Use this formula in Excel:
css
Copy code
= [Wasted Quantity (kg)] / [Purchased Quantity (kg)] * 100
3.	Identify food items with a high waste percentage.
______________
3. Correlate Waste with Purchase Frequency
•	Objective: Check if purchasing frequency impacts waste.
•	Steps:
1.	Use a scatter plot:
	X-axis: Purchase Frequency (per week).
	Y-axis: Waste Percentage.
2.	Look for trends. For example:
	High-frequency purchases may lead to higher waste.
	Suggest buying less frequently for those items.
______________
4. Optimize Purchase Quantities
•	Objective: Find food items that are over-purchased.
•	Steps:
1.	Add a column: "Excess Purchased".
css
Copy code
= [Purchased Quantity (kg)] - [Consumed Quantity (kg)]
2.	Identify items where "Excess Purchased" is consistently high.
3.	Suggest reducing the purchase quantity for those items.
______________
5. Group Similar Food Items
•	Objective: Aggregate waste patterns for similar categories (e.g., fruits, vegetables).
•	Steps:
1.	Add a category column (manually categorize items like fruits, dairy, etc.).
2.	Create a pivot table:
	Rows: Category
	Values: Sum of Wasted Quantity (kg) and Average Waste Percentage.
______________
6. Visualize Waste Trends
•	Objective: Make findings clear.
•	Steps:
o	Create charts:
1.	Bar Chart: Top 5 wasted food items.
2.	Pie Chart: Contribution of each category to total waste.
______________
7. Statistical analysis
Calculate new purchase quantity for the purchase quantity
Using regression analysis we test weather new purchase quantity is best fit or not
______________
8. Implement recommendations
Reduce purchase quantities for high-waste items, adjust purchase frequency,
and prioritize consuming perishable items sooner .
Trend analysis suggests reducing the purchase of vegetables (a high-waste
food category) and other major food items with significant waste .
Using statistical analysis, we can conclude that following the new calculated
purchase quantities will lead to a reduction in food wastage in the coming
days.
   
