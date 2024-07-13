# code_alpha_task02

## Project Detail
## Data Collection
+ **Source:** The data is loaded from a CSV file named ``USA_Housing.csv``.
+ **Features:** Average area income, average area house age, average number of rooms, number of bedrooms, area population, and address.
+ **Target:** House price.
## Data Preprocessing
+ **Exploratory Data Analysis:** Basic statistics, missing value analysis, and visualization.
+ **Data Cleaning:** Dropping the Address column and handling missing values.
+ **Feature Scaling:** Using StandardScaler to standardize the features and target variable.
+ **Train-Test Split:** Splitting the data into training ``(90%)`` and testing ``(10%)`` sets.
## Model Building
 1. __Linear Regression__


 2. __Decision Tree Regression__

 3. __Random Forest Regression__

 4. __Gradient Boosting Regression__
## Model Training
 + Each model is trained on the training data and used to make predictions on the test data.
## Evaluation and Visualization
+ **Metrics:** Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
+ **Visualization:** Actual vs. predicted values, residual analysis.
## Results
+ **Visualization:** Scatter plot of actual vs. predicted values, residual distribution plot.

+ **Evaluation Metrics:**

+ **Linear Regression:**

  - MSE: 0.0789
  - RMSE: 0.2809

+ **Decision Tree:**
  - MSE: 0.2455
+ **Random Forest:**
  - MSE: 0.1132

+ **Gradient Boosting:**
  - MSE: 0.0965
## Model Ranking
&emsp;1. **Linear Regression: 0.0789** 

&emsp;2. **Gradient Boosting: 0.0965**

&emsp;3. **Random Forest: 0.1132**

&emsp;5. **Decision Tree: 0.2455**
## How to Run
  1. Clone the Repository
```
git clone https://github.com/Touseef-Asif/code_alpha_task02.git

```
2. Navigate to the Project directory
```
cd house-price-prediction

```
3. Install the required Dependencies
```
pip install numpy
pip install pandas
pip install scikit-learn
pip install matplotlib
pip install seaborn

```
4. Run the Jupyter Notebook to see the data preprocessing, model training, and evaluation steps:
```
jupyter notebook https://github.com/Touseef-Asif/code_alpha_task02/blob/main/House_pricing_prediction_LR_task03.ipynb
```

## Contact
If you have any questions or feedback, please feel free to reach out to me:

+ Name: Touseef Asif
+ Email: touseefasifbgh533@gmail.com
+ GitHub: https://github.com/Touseef-Asif
## Model Comparison
+ The models are compared based on their MSE scores to identify the best-performing model.
