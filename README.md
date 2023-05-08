# Prediction of Product Sales & insights of the market
![Market thumbnails](https://user-images.githubusercontent.com/128573553/236938630-8bb8c24a-075b-4fd2-b250-20ac65500a06.jpg)
## Analyze item visibility and sale of item types
Quan Nguyen  

**The project will focus on developing a comprehensive sales prediction model specifically for food items that are sold at various stores. This predictive model will be designed to analyze and interpret a wide range of data, including sales history, customer preferences, product features, and store location data, among others. By harnessing the power of data analytics and machine learning techniques, the goal of this project is to provide the retailer with actionable insights into the properties of products and outlets that play crucial roles in driving sales.**

## Original Data Source:

Big Mart Sales Prediction:https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/  

There is 8523 rows, and 12 columns in this data

## Data Dictionary

![data dictionary](https://user-images.githubusercontent.com/128573553/236410755-4ead1f60-5672-483d-bb8a-b46d48a8551c.png)

# **After cleaning data, the following processes were perform:**
## Exploratory Data Analysis

> During the exploratory data analysis, every numeric columns will be visualized with a boxplot and histogram.
> Barplot was chosed to plot categorical columns.
> This create a great overall data analysis for the entire data set

![Item oulet sales eda](https://user-images.githubusercontent.com/128573553/236939971-4437c9a3-57ca-4a87-9f50-6dfae3bbcae9.png)

>With this skewed to the right this columns, we can see that the sale of outlets mostly lie around the Q1 percentile.
Median is approximately at $1900

## Explanatory Data Analysis
> - To visualize explantory purposes, two bargraphs was chose to visualize. 
> - The bargraphs were chosen to compare the categories columns.

![ExDA](https://user-images.githubusercontent.com/128573553/236940460-cbdc882f-a08a-4671-98b9-2c862154020b.png)

> The graph does show that the supermarket type 3 outlets are the most profitable in average sales, stakeholders should be maximize their profits if they invest in this type of outlet.

![Visibility by item type](https://user-images.githubusercontent.com/128573553/236940496-24dd9788-6fd6-472d-8b9d-e75fe306af61.png)

> - Breakfast is the easiest item that can be found.
> - Health and Hygiene items are the hardest items that can be found.


## Machine Learning Using the Following Models:

> - Linear Regression Model
> - Tuned Linear Rgressor Model
> - Random Forest Regressor Model
> - Tuned Random Forest Regressor Model

## Models Evaluated & Results

![Metrics ](https://user-images.githubusercontent.com/128573553/236941894-06bbb44a-cf56-4b3c-ba06-b9a68ed82128.png)

-  The Final Model Chosen was `Random Forrest Regressor Model` with the depth of 5 and number of estimators tuned to 200
-  For the testing set on the model `60.2%` of the variance in y was explained by x.
-  The Root Mean Squared error had a calculation of  `$1060`

Using this model to make predictions about what item types, which types of outlet will maximize profits for stakeholders. Also, we can use this model predicts sales of every single item.

## Recommendations

Market Products insights:  

- For new stakeholders want to invest in this market:
    - Breakfast are the easiest item to find among the outlets, therefore if we want to max out products sale, we should invest majority of funds for this item types.
    - Besides, Supermarket type 3 has a domination in sales among outlet size. If providers want to participate in this market, they should consider this type of market to coordinate. 

Model Performance  

 - Overall, we can see that Tuned Random Forrest Regressor are the most efficient for this data in terms of its regression metrics.

