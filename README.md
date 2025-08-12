# SCT_ML_1
🏠 House Price Prediction using Linear Regression
This project predicts house prices based on area, number of bedrooms, and number of bathrooms using a Linear Regression model. It also visualizes the data and evaluates the model’s performance.

**📌 Features**
1.Loads housing dataset (Housing.csv)

2.Selects relevant features: Area, Bedrooms, Bathrooms

3.Splits data into Training and Testing sets

4.Trains a Linear Regression model

5.Evaluates model performance using Mean Squared Error and R² score

6.Generates useful plots:

Actual vs Predicted Prices Scatter Plot

Residuals Distribution Plot

Price vs Area Regression Line

**📐 The Math Behind Linear Regression**
Linear Regression finds a straight-line relationship between inputs (features) and the output (target).
In our case:

price =
𝛽
0
+
𝛽
1
⋅
area
+
𝛽
2
⋅
bedrooms
+
𝛽
3
⋅
bathrooms
+
𝜖

Where:

β 
0
​
  = Intercept (price when all features are 0)

𝛽
1
,
𝛽
2
,
𝛽
3
​
  = Coefficients (impact of each feature on price)

ϵ = Error term (difference between actual and predicted price)

Goal: Find the best 

β values that minimize the Mean Squared Error (MSE):

MSE= 
1/n
∑
​(y 
i
​ − 
y
^
​i
​)^ 
2
 
Where:

𝑦
𝑖
​ = Actual price

𝑦
^
𝑖
​= Predicted price

**🛠 Technologies Used**

Python 

Pandas – Data manipulation

NumPy – Numerical computations

Matplotlib / Seaborn – Data visualization

Scikit-learn – Machine learning
