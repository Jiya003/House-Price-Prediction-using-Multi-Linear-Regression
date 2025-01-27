# House-Price-Prediction-using-Multi-Linear-Regression
I have used Supervised Machine Learning -> Multi Linear Regression to predict real state houseprice predictions

This project focuses on predicting the price of a house per unit area based on various features such as house age, transaction date, proximity to public transport (MRT), and other geographical data. We use Multiple Linear Regression to build a predictive model.

### Dataset Description

The dataset used for this project contains the following features:

1. Transaction Date: The date on which the house transaction occurred. It is used to analyze trends over time and the effects of market changes.
2. House Age: The age of the house, which can influence its value. Older houses may depreciate in value unless they have been well-maintained or renovated.
3. Distance to the Nearest MRT Train Station: The distance from the house to the nearest Mass Rapid Transit (MRT) station. Proximity to public transport usually affects the value of a property.
4. Number of Convenience Stores: The number of convenience stores nearby. Proximity to amenities like convenience stores can increase the desirability and price of a property.
5. Latitude: The latitude of the house’s location, useful for determining its geographical position.
6. Longitude: The longitude of the house’s location, which, along with latitude, helps to identify the exact location on a map.
7. House Price of Unit Area: The target variable (Y), representing the price of the house per unit area. This is what we aim to predict using the independent features.


### Prerequisites

To run this project, you'll need the following libraries and tools installed:

1. Python: Make sure you have Python (version 3.x) is installed on your system.

2. Libraries:
   
   pandas: For data manipulation and analysis.
   numpy: For numerical computations.
   matplotlib: For creating visualizations like scatter plots and graphs.
   sklearn: For building the linear regression model and evaluating it using various metrics.

### To install
pip install pandas numpy matplotlib scikit-learn


### IDE/Environment:

1. You can use any Python IDE or text editor like VS Code, PyCharm, or Jupyter Notebook.

2. Alternatively, you can run this project on Google Colab for easy access to cloud-based computation.

3. Clone or download the repository containing the dataset and the script.

4. Ensure that the dataset (CSV file) is placed in the correct directory or is properly referenced in the script.

5. Run the Python script to train the Multiple Linear Regression model, which will predict house prices based on the given features.

6. After training, the model will evaluate its performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-Squared.

### Conclusion:

This project aims to help predict the price of houses based on various features, and the model can be extended with additional features or other regression techniques for improved accuracy.


