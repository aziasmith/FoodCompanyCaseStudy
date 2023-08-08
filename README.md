# Food Delivery Company Menu Consolidation & Brand Identity Case Study
Case study project for Google data analytics course

![image](https://github.com/aziasmith/FoodCompanyCaseStudy/blob/main/online-food-delivery-industry-min.jpg)

# Background
A food delivery company operates out of multiple cities across the country. They have various fulfillment centers that prepare and distribute the meals that are ordered. They have a wide variety of cuisines and 51 menu items that are offered. They currently offer four different cuisines (Italian, Thai, Indian, and Continental) which makes it difficult to have a solid brand identity. The marketing team would like to establish two cuisines in order to market the brand better. In additon to that, the fulfillment center managers are having staffing issues. A simplified menu would make it easier for the fulfillment centers to train new employees faster. 

# Business Task
In order to simplify the menu and establish the brand identity, I have been tasked to identify which cuisine types and meals are most popular. 

# Data Source
This case study is being done by using a [data set](https://www.kaggle.com/datasets/kannanaikkal/food-demand-forecasting) from Kaggle that was originally published by Edwin U Kannanaikkal. 

# Data Analysis 
I cleaned, consolidated, and analyzed my data with R. Initially there were three different data tables to merge into one file. 

View my R script [here](https://github.com/aziasmith/FoodCompanyCaseStudy/blob/main/Food%20Delivery%20Company%20Menu%20Consolidation%20Case%20Study%20Script.pdf)

The cleaned and consolidated [data set](https://github.com/aziasmith/FoodCompanyCaseStudy/blob/main/complete_meal_info.csv)

# Visualizations
This graph shows the average number of orders for each meal and its organized by cuisine type. 
![image](https://github.com/aziasmith/FoodCompanyCaseStudy/blob/main/Meal%20Orders%20Organized%20by%20Cuisine%20Type%20Bar%20Chart.png)

This pie chart represents the percentage of the total orders for each cuisine type. 
   
![image](https://github.com/aziasmith/FoodCompanyCaseStudy/blob/main/Percent%20of%20Total%20Orders%20by%20Cuisine%20Pie%20Chart.png)

This box and whisker plot shows the variation of the average number of order by cuisine. The box represents the inner 50% of the data and the line going through the box is the median value for each cuisine. The points for the Indian and Thai cusines are outliers. 

![image](https://github.com/aziasmith/FoodCompanyCaseStudy/blob/main/Box%20and%20Whisker%20Plot.png)

# Final Conclusion
Upon first glance of the bar chart, it looks like Indian and Thai cuisines have the most orders. But, the pie chart shows that 65.48% of the total average orders come from Italian and Thai cuisines. Italian has the highest average number of orders with 34.57% and Continential has the lowest average number of orders with 14.63%. 

In the box and whisker plot, the lines going through the boxes of the box and whisker plots are the medians. Italian has the highest median value and Indian has the lowest median value. Indian cuisine has three data outliers and Thai has two data outliers. 

My recommendation would be to use Italian and Thai cuisines for the overall brand identity and remove the Indian and Continental food items from the menu. With the Indian meals that are outliers in the data, I would suggest to offer those dishes as a special occassionaly and use it as a promotion tool. 
