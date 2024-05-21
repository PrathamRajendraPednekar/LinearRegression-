# LinearRegression

Problem Statement:

-The company wants to understand the relationship between its advertising expenditures across different media (TV, Radio, and Newspaper) and the resulting sales. 
 the goal is to use this understanding to predict future sales based on planned advertising spends and to optimize the allocation of the advertising budget to 
 maximize sales.

Solution Approach:

-To solve this problem, we applied a Linear Regression model to the dataset that contains information about the expenditures on TV, Radio, and Newspaper 
 advertisements and the corresponding sales figures. The steps involved in the project were as follows:

Steps Taken:

1. Data Loading and Exploration

- Loaded the dataset from a CSV file.
- Explored the dataset to understand its structure and summary statistics.
- Identified the features (TV, Radio, Newspaper) and the target variable (Sales).

2. Data Preprocessing

- Checked the dataset for missing values and data types.
- Split the dataset into training and testing sets (80% training, 20% testing).

3. Model Training

- Used the LinearRegression model from the sklearn library.
- Trained the model on the training data (features: TV, Radio, Newspaper; target: Sales).

4. Model Evaluation

- Evaluated the model performance using the testing set.
- Calculated key metrics such as R-squared and Root Mean Squared Error (RMSE).
- Visualized the correlation between features using a heatmap.

5. Prediction

- Used the trained model to predict sales for the testing set.
- Compared the actual sales with the predicted sales.

Performance of the Model

    R-squared: This metric indicates how well the model's predictions explain the variability of the actual sales data. An R-squared value closer to 1 implies a 
             better fit.
  
    Root Mean Squared Error (RMSE): This metric measures the average magnitude of the prediction errors. Lower values indicate better model performance.

Business Impact
  
    Prediction of Sales: The model helps in predicting future sales based on different advertising budgets, allowing the company to forecast revenue more 
                         accurately.Optimization of Ad Spend: By understanding the impact of each advertising channel on sales, the company can allocate its budget 
                         more effectively, focusing on the channels with the highest return on investment.
                       
    Strategic Planning: The insights from the model can assist in strategic planning and decision-making, ultimately leading to more efficient use of resources and 
                       improved business outcomes.

This linear regression model provides a valuable tool for the company to enhance its advertising strategy, leading to potentially higher sales and better allocation of the advertising budget.
