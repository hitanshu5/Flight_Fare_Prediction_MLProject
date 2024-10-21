# Flight_Fare_Prediction_MLProject
Table of Contents
1. Project Objective
2. Dataset Description
3. Preparing data for Analysis
4. Visualizations
5. Conclusion

# Project Objective
This project uses machine learning techniques to predict the prices of flights within India based on various factors such as airline, departure time, duration, and more. The model provides insights into how different parameters affect flight prices, helping users make more informed booking decisions. It leverages popular Python libraries like Pandas, Scikit-Learn, and Matplotlib for data processing, model training, and visualization.

# Dataset Description
This dataset contains 10,684 rows of flight data for flights within India, including information such as airline, journey date, source, destination, route, departure and arrival times, flight duration, total stops, additional info, and ticket prices. It provides a rich set of features to analyze and predict flight prices based on various factors.

# Preparing data for Analysis
Before building the flight price prediction model, the dataset was cleaned and prepared for analysis. Exploratory Data Analysis (EDA) was conducted to understand data distributions and relationships between features. Missing values were handled appropriately, and categorical variables were converted to numerical form using one-hot encoding. Outliers in the dataset were identified and removed to improve model performance.

# Visualiation 
Different plots were made in order to gain meaningful insights from the cleaned data.
- Flight Price Distribution by Airline

![image](https://github.com/user-attachments/assets/bc6dae3f-eec1-4575-8303-739e7b03b079)

- Flight Price Trends over time (month)
- Distribution of flight duration
- Effect of total stops on flight price
- plotting depaarture time against flight price 

# Conclusion
After training and tuning multiple models for flight price prediction, the Random Forest Regressor was selected for its optimal performance, achieving 96.25% accuracy on the training data and 78.34% on the test data. The model was successfully deployed using Flask, with a custom-built frontend for user interaction, allowing seamless flight price predictions based on input features.

![image](https://github.com/user-attachments/assets/491be902-781e-4c79-b7a1-e669f9c38351)

Output
![image](https://github.com/user-attachments/assets/9d251a94-33ec-4331-937b-6a4063ed91e6)
