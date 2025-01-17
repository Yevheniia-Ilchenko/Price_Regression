# Price_Regression
Task
Your task is to create a model using Regression, which will predict future order prices by the hour of the day. The closer this model will be to the truth - the better. All tasks, where you need to modify this Colab are highlights with TASK. If no TASK provided - then you just need to run that cell without any modifications.

### 1. Linear Regression
Let's start with Linear Regression, and check, if it fits our needs. Here you need to do these steps (TASK):

Apply linregress to time and prices.
Create estimate_order_price function to predict value by slope & intercept
Map estimate_order_price function to time and save in estimated_order_prices list.
Plot the scatter and the linear regression line (already written instead of you)

### Evaluation Metrics
R² Score & Mean Squared Error (MSE)
To evaluate the performance of the model, calculate the R² score and Mean Squared Error (MSE) for both the training and test datasets.

### 2. Polynomial Regression
If Linear Regression does not meet the requirements, try Polynomial Regression, which might provide better results with a curved line fit.

### Fit Train Data with Polynomial Regression
Use numpy to create a polynomial model with a degree of 3 and fit it to the training data.

### Conclusion
This project involves creating a regression model to predict order prices based on the hour of the day. Linear Regression is initially used, and if it does not meet the requirements, Polynomial Regression is applied for better results. The model's performance is evaluated using R² score and MSE.

### Acknowledgments
This project was developed using tools like numpy, scipy, and matplotlib. The guidance for each step is provided to ensure a thorough understanding and successful implementation of the regression model.
