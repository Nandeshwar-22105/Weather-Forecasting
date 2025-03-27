Weather Prediction Model

Overview
This project involves building a weather prediction model using multiple machine learning algorithms to forecast temperature based on various meteorological parameters.

Dataset
The dataset used is kanpur.csv, which contains weather data for Kanpur. The data includes features such as:

-->Maximum Temperature (maxtempC)
-->Minimum Temperature (mintempC)
-->Cloud Cover
-->Humidity
-->Temperature (tempC)
-->Sun Hours
-->Heat Index (HeatIndexC)
-->Precipitation (precipMM)
-->Pressure
-->Wind Speed (windspeedKmph)

Data Preprocessing
Loaded dataset and parsed date_time as an index.Checked for missing values and handled them using forward fill (fillna(method='pad')).Selected relevant numerical features for training.
Split data into training and testing sets (80% training, 20% testing).

Exploratory Data Analysis (EDA)
Plotted time series graphs for different parameters.Created scatter plots to visualize relationships between temperature and other features.Generated histograms to understand the data distribution.

Machine Learning Models Used
The following models were trained and evaluated:

Linear Regression

Decision Tree Regressor

Random Forest Regressor


Model Evaluation
Each model was evaluated using:
-->Mean Absolute Error (MAE)
-->Residual Sum of Squares (MSE)
-->R-Squared Score (R²)

Results:

Linear Regression

Variance Score: X.XX

R² Score: X.XX

Decision Tree Regressor

Variance Score: X.XX

R² Score: X.XX

Random Forest Regressor

Variance Score: X.XX

R² Score: X.XX

Dependencies
Python 3.x
NumPy
Pandas
Matplotlib
Scikit-Learn

How to Run
Install dependencies using pip install numpy pandas matplotlib scikit-learn.
Place kanpur.csv in the same directory as the script.
Run the script in Jupyter Notebook or a Python environment.

Conclusion
Random Forest Regressor provided the best performance among the models.
Future improvements can include hyperparameter tuning and incorporating additional weather parameters.

