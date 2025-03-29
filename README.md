# House-price-prediction  
We all have experienced a time when we have to look up for a new house to buy. But then the journey begins with a lot of frauds, negotiating deals, researching the local areas and so on.So to deal with this kind of issues Today we will be preparing a MACHINE LEARNING Based model, trained on the House Price Prediction Dataset. 

You can download the dataset from https://media.geeksforgeeks.org/wp-content/uploads/20240905183434/HousePricePrediction.xlsxlink.


## ✨Importing Libraries and Dataset 

## here we are using 

- **Pandas** – To load the Dataframe
- **Matplotlib** – To visualize the data features i.e. barplot
- **Seaborn** – To see the correlation between features using heatmap

  ## Project Overviews
- **Data Preparation**: Load dataset, handle missing values, encode categorical features, and normalize numerical data.

- **Model Architecture**: Use multiple regression models (SVR, Random Forest, Linear Regression, CatBoost).

- **Training**: Split data into training (80%) and validation (20%), fit models on training data.

- **Testing**: Predict on validation set, evaluate with metrics like MAPE(Mean absolute Percentage error) .

- **Model Saving**: Model is saved within the Google Colab .ipynb notebook for future reference..

- **Model Loading**: Rerun the notebook to reload and use the trained model..

- **Result**: Compare models based on accuracy metrics and select the best one for deployment. 🚀

  ## **🚀 Getting Started**
 ## Run the Script:
Execute the script to load the house price dataset, preprocess the data, train multiple regression models, and save the trained model within the Google Colab .ipynb notebook.

## View Results:
After training, the model evaluation metrics such as Mean Absolute Percentage Error (MAPE)  score will be displayed to compare model performance.

## Load Model for Prediction:
Rerun the notebook to reload the trained model and make predictions on new house price data, displaying the predicted prices based on input features. 🚀




