# PowerBi-Food-Delivery-Forecast-Dashboard
This project shows the use of Power Query and DAX Query to analyse the food delivery data, add new measures and columns, and create a dashboard using Power BI.

## Objective 
The granular analysis to optimize product offerings, improve fulfillment center performance, and enhance overall operational efficiency in the food delivery service. By leveraging detailed insights, the goal is to maximize customer satisfaction, streamline costs, and ensure a sustainable and competitive position in the market.

### Tools Used
* Power BI
* Power Query
* Dax Query
* Data modeling

#### Cleaning and Analyzing using Power Query
- Open Excel and connect to your Food delivery data
- Use Power Query to clean and transform the data
- Create a copy template for one sheet in Power Query transformations and apply the same transformations to all sheets
- Apply all necessary cleaning steps, such as removing duplicates, renaming columns, and changing data types (As it is a clean data, I have skipped this step)
- Create a parameter to select the desired data based on a specific condition
- Encapsulate all steps into a function to be reused for future sheets and data
- Load and Apply the cleaned data into Power BI

![query 1](https://github.com/TrushnaR/PowerBI-Food-Delivery-Forecast-Dashboard-/assets/155801135/d30204e1-0ce0-44a6-b0ad-7212193fb6fa)
![query2](https://github.com/TrushnaR/PowerBI-Food-Delivery-Forecast-Dashboard-/assets/155801135/29104a7f-42a8-422c-8b92-236ed4cc61a1)

![query3](https://github.com/TrushnaR/PowerBI-Food-Delivery-Forecast-Dashboard-/assets/155801135/6fc45e16-bcdb-4425-84eb-5232df63b632)
![query4](https://github.com/TrushnaR/PowerBI-Food-Delivery-Forecast-Dashboard-/assets/155801135/0417f1a8-5c96-42c5-83e0-9cc3420aa111)

##### Exploring and Manipulate Some Data Using DAX Query
* With DAX Query, we can effectively manipulate and analyse the data to provide insights for visualization and identify areas for improvement for HR.
* Create Measures and columns Using DAX functions such as count, sum, calculate, if, switch, divide and Date-time function for exploring some clean data for improve dashboard KPI in PowerBI.

![Screenshot 2024-01-17 112711](https://github.com/TrushnaR/PowerBI-Food-Delivery-Forecast-Dashboard-/assets/155801135/82ed9478-310f-42a2-bc0e-e3c6696da4d0)

##### Custom Forecasting-Explore advanced forecasting models under the "Modeling" tab
![modelling](https://github.com/TrushnaR/PowerBi-Food-Delivery-Forecast-Dashboard/assets/155801135/d3d57af9-ab84-4a38-a491-74d67daed06a)

#### Power BI Dashboard Visualization
* Design the dashboard layout
* Create a measure table to aggregate and display the data using Dax functions
* Use Visualization for charts and filters for filter dashboard
* Now, Add Title Food Delivery Forecast Dashboard
* Add Year column as Slicer and add some informative KPI.
* Add Card, Sun Burst Pie chart , Column Chart, Stacked Bar Chart.

Download The File and Open In Power BI Desktop for Interactive Viewing.
[View Screenshots](https://github.com/TrushnaR/PowerBi-Food-Delivery-Forecast-Dashboard/tree/main/PowerBi%20Food%20Delivery%20Forecasting%20Images) of the Dashboard.
[View Video](url) of Dashboard.
* Note: The PowerBI online publishing link isn't available right now because of subscription issues.
* I'll add that online link soon, so anyone can open it and interact with it.

