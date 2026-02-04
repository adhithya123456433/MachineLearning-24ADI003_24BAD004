Scenario 1- Ocean Water Temperature Prediction Using Linear Regression
This scenario is to predict ocean water temperature using environmental and geographical parameters.
The CalCOFI oceanographic dataset is used as the data source.
Water temperature T_degC is considered as the target variable.
Input features include depth, salinity, oxygen level, latitude, and longitude.
Relevant numerical features are selected for model training.
Missing values in the dataset are handled using mean or median imputation.
Feature scaling is applied using StandardScaler to normalize the data.
The dataset is split into training and testing sets.
A Linear Regression model is trained using the training data.
Predictions are generated for the test dataset.
Model performance is evaluated using MSE, RMSE, and R² score.
Actual versus predicted temperature values are visualized.
Residual error distribution is plotted to analyze prediction errors.
Ridge and Lasso regression techniques are applied to improve model performance.

Scenario 2- LIC Stock Price Movement Classification Using Logistic Regression
This scenario focuses on predicting the daily movement of LIC stock prices.
A binary target variable called price movement is created.
If the closing price is higher than the opening price, the label is set to 1.
If the closing price is lower than or equal to the opening price, the label is set to 0.
Input features include open price, high price, low price, and trading volume.
Essential Python libraries are imported for data processing and modeling.
The dataset is loaded into a Pandas DataFrame.
Missing values are handled using forward fill or statistical imputation.
Feature scaling is performed using StandardScaler.
The data is split into training and testing sets.
A Logistic Regression classifier is trained on the training data.
Predictions are made on the test dataset.
Model performance is evaluated using accuracy, precision, recall, and F1-score.
A confusion matrix is used to analyze classification results.
The ROC curve is plotted to evaluate model discrimination ability.
