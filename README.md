# Simple-Linear-Regression

**Water Salinity Prediction based on Temperature**

  This project aims to predict the water salinity based on its temperature. The dataset used for this project is sourced from Kaggle and contains two columns: 'Salnty' representing the salinity in g of salt per kg of water (g/kg) and 'T_degC' representing the temperature in degrees Celsius.

**Data Source** 
  
  The dataset used for this project can be found on Kaggle at the following link: https://www.kaggle.com/datasets/sohier/calcofi

**Exploratory Data Analysis (EDA)**
  
  The initial step involved loading the dataset and performing exploratory data analysis. Key steps in EDA include:

  -Plotting a scatter plot of 'Salnty' against 'T_degC' to visualize the relationship between the two variables.
  -Handling missing values by imputing the mean values for 'Salnty' and 'T_degC' columns in the first 800 rows of the dataset.
  -Handling duplicates in the subset to ensure clean and reliable data for analysis.
  
**Data Visualization**

  The data visualization phase involved plotting the scatter plot of the subset 'sample_df' after handling missing values and duplicates. This plot was used to observe the relationship between salinity and water temperature.

**Linear Regression Model**
  
  To predict the water temperature based on salinity, a linear regression model was utilized. The 'Salnty' column was used as the input feature (X) and the 'T_degC' column as the target variable (y). The linear regression model was fitted to the data using the scikit-learn library.

**Model Visualization**

  The linear regression model's predictions were visualized by plotting the scatter plot of 'Salnty' against 'T_degC' and overlaying the regression line. The red regression line represents the predicted relationship between salinity and water temperature.

**Prediction**
  
  A specific salinity value (e.g., 35 g/kg) was used to make a prediction for the corresponding water temperature. The predicted temperature value was displayed using the fitted linear regression model.

**Model Evaluation**
  
  To assess the model's performance, the R-squared (R^2) score was calculated. The R^2 score measures the proportion of the variance in the target variable that is predictable from the input features. A higher R^2 score indicates a better fit of the model to the data.

**Conclusion**
  
  This project demonstrated the use of a linear regression model to predict water temperature based on salinity. The model achieved a satisfactory R^2 score, indicating a reasonable fit to the data. Further improvements could be made by exploring other regression techniques or incorporating additional features to enhance the predictive performance.

**Dependencies**
  
  pandas
  matplotlib
  scikit-learn
