# Rental
As I always like to play with new ideas, so there will be update of the code time to time with more or less features.
Data is from : Apartment rental offers in Germany in Kaggle
https://www.kaggle.com/datasets/corrieaar/apartment-rental-offers-in-germany

Using  machine learning techniques to predict the rental of a property in Cologne(Köln). Here is the outline of the process of the prediction:

1. Visualize and Initial Analysis of the dataset using stanadard procedures and building an interactive map using Follium.
2. Separate Cologne rental data with the features from the dataset.
3. Preprocess the data by cleaning it and formatting it in a way that is suitable for modeling. This involve handling missing values, converting data types, and scaling the data.
4. Split the data into training and test sets. The training set will be used to fit the model, while the test set will be used to evaluate its performance.
5. Choose an appropriate machine learning algorithm or model for rental prediction. There are many options to choose from, such as linear regression, random forest, MLP Regressor, XGBoost, ADABoost etc.
6. Train the model on the training set by fitting it to the data.
7. Evaluate the model's performance on the test set by comparing the predicted rental prices to the actual rental prices.
8. Fine-tuned the model using RandomSearchCV by repeating steps 5 and 6 to find best parameters to estimate.
9. By giving your required characteristics you can now see a prediction of the approximate rent you need to pay.

Future Work:
1. Fine tuning using GridSearchCV for better parameter tuning.
2. Apply new algorithms to see is there any change in prediction.
