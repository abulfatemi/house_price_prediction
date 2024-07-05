# house_price_prediction
This project demonstrates a machine learning approach to predict house prices using a Random Forest Regressor. The goal is to build a model that accurately predicts house prices based on features such as location, size, amenities, etc

The project is structured as follows:

Data Preprocessing:
   Removing categorical features columns that have unique value in validation data but not in training data.
   Missing values in numerical features are imputed using a constant value.
   Missing values in categorical features are imputed with the most frequent value and then encoded using one-hot encoding.
Modeling:
   Pipeline integrates data preprocessing steps and model training, ensuring consistency and efficiency in handling the data 
   and training the model.
   A Random Forest Regressor from scikit-learn is used for predicting house prices.
   Hyperparameters of the model can be adjusted for optimization.
Evaluation:
  Mean Absolute Error (MAE) is used as the evaluation metric to assess model performance.
