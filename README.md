# Rental
As I always like to play with new ideas, so there will be update of the code time to time with more or less features.
Data is from : Apartment rental offers in Germany in Kaggle
https://www.kaggle.com/datasets/corrieaar/apartment-rental-offers-in-germany

Use  machine learning techniques to predict the rental of a property in Cologne(Köln). Here is the outline of the process of the prediction:

1. Visualize and Analyse the data using stanadard procedures and develop an interactive map using Follium.
2. Separate Cologne (city) rental data.
3. Preprocess the data to make it suitable for modeling. This involves handling missing values, converting types, and scaling.
4. Split into training and test set. The training set will be used to fit the model, while the test set will be used to evaluate its performance.
5. Choose an appropriate machine learning algorithms or models for rental prediction.
6. Train on the training set and evaluate the performance on the test set by comparing the predicted rent to the actual rent.
8. Fine-tune the model using RandomSearchCV by repeating steps 5 and 6 to optimize the prediction.
9. By providing required values one can get the approximate rent from the framework for cologne.

Future Work:
1. Fine tuning using GridSearchCV for better parameter tuning.
2. Apply new algorithms to see is there any change in prediction.
