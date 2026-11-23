# Predicting House Prices

**Level 5, Mission 4** | Group project | [Back to portfolio](../README.md)

Completed with Mission Ready classmates.

**My contribution:** I set up our group chat, suggested how we could split the work, set a check-in date a week before the deadline, and reviewed the finished workbook. My teammates completed the analysis in our shared Fabric workbook.

## Goal
Predict house prices from features of the house, then compare two models.

## Dataset
500 houses with 7 features: Square_Feet, Num_Bedrooms, Num_Bathrooms, Num_Floors, Garage_Size, Location_Score and Distance_to_Center. The target is Price. There were no missing values. Provided through Mission Ready.

## What we did
1. Loaded and checked the data.
2. Ran EDA: summary statistics, a scatter plot, a price histogram and a correlation heatmap.
3. Split the data 80/20 into training (400 houses) and testing (100 houses).
4. Trained a Multiple Linear Regression model.
5. Trained a Random Forest model (200 trees).
6. Compared both models using RMSE and actual vs predicted charts.

## Key findings
- Prices range from about $277k to $961k and are roughly bell-shaped.
- Square_Feet and Num_Bedrooms have the strongest link to price (about 0.56 each). That is a moderate relationship.
- **Multiple Linear Regression performed better:** RMSE $63,952, compared with $72,013 for Random Forest.
- Both models underestimated houses over $700k and overestimated houses under $400k.

## What we learned
- A simpler model can beat a more complex one when the data follows linear patterns.
- RMSE shows the typical size of a model's error in dollars.
- Next steps could include tuning the Random Forest and adding more features.

## Tools
Python, Pandas, scikit-learn, Matplotlib, Seaborn, Microsoft Fabric.

## Files
[Open the notebook](Level-5-Mission-4-House-Price-MLR.ipynb). The cloud storage credentials from the original were removed for security.
