# LinearRegression_Diamonds
  
# Project Goal and Description
  The goal of this project was to estimate the price of 5000 diamonds achieving the smallest amount of error based on previous records of diamonds' prices.
  
# Technologies 
  - Python (Pandas, Scikit Learn, Seaborn)
  - Tableau

# Steps
- Exploratory quantitative and visual analysis was made for the historycal diamonds' data;
- A first baseline model was created with the average price of diamonds and the "price_predicted" column was added to Rick's file (RMSE = 3980.7);
- Strong correlations were noticed between carat and price, which lead to linear regression for model improvement (RMSE = 1605.15);
- Other variables with high correlations to the historical diamonds' price were used in modeling trials and outliers were removed, but not much difference was noticed in the ammount of error (RMSE varied between 1586.8-1591.2);
- 'carat','x'(length), 'y'(width), 'z'(depth) variables were used to predict prices according to different categories of diamonds colors (RMSE = 1467.7), cuts (RMSE = 1491.3) and clarities (RMSE = 1139.8).
- A graphic was created in Tableau to display the best modeling results.

# Conclusion
Diamonds' prices in historical records vary specially according to cariat and different clarity types, which can be used with other features (lenght, width and depth) for creating a price prediction model with RMSE = 1139.8. Linear regression might need to be combined with other models and techniques for further insights. 
   
# Contact
- LinkedIn: vanessadechen
- GitHub: /vdechen
- Email: vanessadechen@gmail.com
