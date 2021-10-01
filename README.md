# Housing_Analysis_withPyviz

The goal of this dashboard is to provide charts, maps, and interactive visualizations that help customers explore the data and determine if they want to invest in rental properties in San Francisco.

First, I will create a jupyter notebook to analyze the housing data in rental_analysis.ipynb.

Second, I will use the dashboard.ipynb notebook to create an interactive dashboard to further evaluate the housing data.

### Rental Analysis

In order to build the dashboard, I will first complete the various calculations needed in the rental_analysis notebook. 

#### Housing Units Per Year

In this section, I calculate the number of housing units per year and visualize the results as a bar chart using the Pandas plot function. Use the max, min, and standard deviation of the data to scale the plot's y limits.

#### Average Housing Costs in San Francisco Per Year

In this section, determine the average sales price per year and the average gross rent per year to better understand housing costs over time. Visualize the average (mean) gross rent and average price per square foot per year and visualize it as a bar chart.

#### Average Prices By Neighborhood

Use hvplot to build two visualizations of average prices with a dropdown menu to filter by neighborhood. The first will be a line plot that shows the average price per square foot over the timeframe for each neighborhood. The second line plot will show the average monthly rent over time for each neighborhood.

This will allow for a more "apples-to-apples" price comparison for purchasing a home vs. renting.

#### Top 10 Most Expensive Neighborhoods

To figure out which neighborhoods are the most expensive, we will calculate each neighborhood's average sale price. Arrange the prices in descending order to find the top ten neighborhoods based on average price and create a bar chart for the results.


#### Comparing Cost to Purchase Versus Rental Income

Here, create an interactive chart with a dropdown filter to browse by neighborhood using hvplot. The visualization will feature a comparison of avg. price per square foot vs average monthly rent. Use the groupby function from hvplot to create the dropdown menu for the neighborhoods. 


#### Neighborhood Map

Using the neighborhood coordinates, we will create an interactive map that shows the average prices by neighborhood. Use the mapbox API (which you will your API key from mapbox to create) to build this visualization.


####  Cost Analysis

Build the following plots using plotly express:

1) Parallel Coordinates Plot

2) Parallel Categories Plot

3) Sunburst Plot

These can be used to filter and analyze different factors related to each neighborhood's housing prices.


### Dashboard

Having coded the calculations and analysis, now use the Panel library to create one interactivate dashboard for all of the visualizations. 