✅ 1. Importing Required Libraries
    numpy: For numerical calculations.
    pandas: For data handling and manipulation.
    matplotlib: For plotting graphs.

📂 2. Load the Dataset
     Reads the CSV file using pandas.
     Dataset contains job positions, levels, and their corresponding salaries.

📊 3. Splitting the Dataset
     x = ds[["Level"]]
     y = ds[["Salary"]]
     x: Feature (Position Level)
     y: Target (Salary)

📉 4. Visualizing the Data
    Visual scatter plot of Level vs Salary to observe the non-linear trend.

🤖 5. Model Building - Polynomial Regression
    Transforms the feature set x into polynomial features of degree 5.
    Trains a Linear Regression model on the transformed data.

🎯 6. Making Predictions
    reg.predict(poly_reg.fit_transform([[6.5]]))
    Predicts salary for a position level of 6.5 using the polynomial regression model.

📈 7. Visualizing the Polynomial Regression Curve
    Blue dots: Actual salary data
    Red curve: Polynomial Regression model prediction

