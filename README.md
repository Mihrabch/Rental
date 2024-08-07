# Rental
Where is the data from?
The data was scraped from Immoscout24, the biggest real estate platform in Germany. Immoscout24 has listings for both rental properties and homes for sale, however, the data only contains offers for rental properties.
The scraping process is described in this blog post and the corresponding code for scraping and minimal processing afterwards can be found in this Github repo.
At a given time, all available offers were scraped from the site and saved. This process was repeated three times, so the data set contains offers from the dates 2018-09-22, 2019-05-10 and 2019-10-08.

Content
The data set contains most of the important properties, such as living area size, the rent, both base rent as well as total rent (if applicable), the location (street and house number, if available, ZIP code and state), type of energy etc. It also has two variables containing longer free text descriptions: description with a text describing the offer and facilities describing all available facilities, newest renovation etc. The date column was added to give the time of scraping.Apartment rental offers in Germany in Kaggle
https://www.kaggle.com/datasets/corrieaar/apartment-rental-offers-in-germany

Acknowledgements
The data belongs to www.immobilienscount24.de and is for research purposes only. The data was created with .

Use  machine learning techniques to predict the rental of a property in Cologne(Köln). Here is the outline of the process of the prediction:

1. Visualize and Analyse the data using stanadard procedures and develop an interactive map using Follium.
2. Separate Cologne (city) rental data.
3. Preprocess the data to make it suitable for modeling. This involves handling missing values, converting types, and scaling.
4. Split into training and test set. The training set will be used to fit the model, while the test set will be used to evaluate its performance.
5. Choose appropriate machine learning algorithms or models for rent prediction.
6. Train on the training set and evaluate the performance on the test set by comparing the predicted rent to the actual rent.
8. Fine-tune the model using RandomSearchCV by repeating steps 5 and 6 to optimize the prediction.
9. Develop a framework based on the model to estimate rent in Cologne after anyone fill in their requirements



Conclusion:
1.Evaluation of Algorithms:
Five different machine learning algorithms were employed to identify the most effective one for predicting rent prices: Decision Tree Regressor, Random Forest Regressor, AdaBoost Regressor, ML Regressor, and XGBoost Regressor. This comprehensive approach ensures that the chosen model is the best fit for the data and provides accurate predictions.

2.Performance of XGBoost and Random Forest:
Among the evaluated algorithms, XGBoost Regressor and Random Forest Regressor demonstrated superior performance. They consistently delivered more accurate and reliable predictions compared to the other models, making them the top choices for this task.

3.User Interaction for Rent Estimation:
At the end of the project, users are prompted to fill in their specific requirements and preferences. Based on the input provided, the system will utilize the best-performing algorithm to estimate the possible rent, offering a tailored prediction for each user.

Recommendation:
1. Enhance the model's predictive power by incorporating additional features such as proximity to public transport, school ratings, crime rates, and local amenities. This comprehensive feature set can lead to more accurate rent predictions.
2. Use one hot encoding.
3. Extend the framework to include data from multiple cities, allowing for the assessment of its effectiveness in different urban environments. This will help validate the model's generalizability and robustness across various regions.
4. Apply new algorithms to see is there any change in prediction.
