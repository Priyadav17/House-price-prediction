# House-price-prediction  

We all have experienced a time when we have to look up for a new house to buy. But then the journey begins with a lot of frauds, negotiating deals, researching the local areas and so on.So to deal with this kind of issues Today we will be preparing a MACHINE LEARNING Based model, trained on the House Price Prediction Dataset. 




## ✨Importing Libraries and Dataset 

## here we are using 

- **Pandas** – To load the Dataframe
- **Matplotlib** – To visualize the data features i.e. barplot
- **Seaborn** – To see the correlation between features using heatmap

 ## ✨ Key Features of House Price Prediction Project
## Data Preprocessing:

- Handle missing values by filling or dropping them.

- Encode categorical features using One-Hot Encoding.

- Normalize numerical data for better model performance.

## Exploratory Data Analysis (EDA):

- Visualize correlations between numerical features using a heatmap.

- Analyze the distribution of categorical features with bar plots.

## Model Training:

- Train multiple regression models (SVR, Random Forest, Linear Regression, CatBoost).

- Split data into training (80%) and validation (20%) sets.

- Evaluate models using MAPE and R² score.

## Model Saving & Loading:

- Save the trained model within the Google Colab .ipynb notebook.

- Reload the model for future predictions by rerunning the notebook.

## Prediction & Evaluation:

- Predict house prices for single and multiple inputs.

- Display predicted prices for given input features.

- Compare different models to select the best-performing one.

  ## **🚀 Getting Started**
 ## Run the Script:
Execute the script to load the house price dataset, preprocess the data, train multiple regression models, and save the trained model within the Google Colab .ipynb notebook.

## View Results:
After training, the model evaluation metrics such as Mean Absolute Percentage Error (MAPE)  score will be displayed to compare model performance.

## Load Model for Prediction:
Rerun the notebook to reload the trained model and make predictions on new house price data, displaying the predicted prices based on input features. 🚀


## Results of House Price Prediction
## Model Performance Evaluation:

- Mean Absolute Percentage Error (MAPE): Measures the prediction error percentage for each model.

## Model Comparison:

- **SVR**: Provides smooth predictions but may struggle with large variations in prices.

- **Random Forest**: Handles non-linearity well and performs robustly on diverse datasets.

- **Linear Regression**: Works well for linear relationships but may underperform for complex price trends.

## Predictions on New Data:

- The trained model is tested on unseen data, and predicted house prices are displayed alongside actual values for validation.

## Visualization of Results:

- Loss & accuracy plots illustrate model performance trends.

- Scatter plots & histograms help analyze prediction distribution.







