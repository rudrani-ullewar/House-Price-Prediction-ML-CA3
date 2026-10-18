House Price Prediction Using Machine Learning

1. Project Title

House Price Prediction Using Machine Learning – CA3

2. Problem Statement

The objective of this project is to predict house prices based on different property features using machine learning algorithms.

3. Dataset

The dataset is from the Kaggle House Prices: Advanced Regression Techniques competition. It contains information about residential properties, including their size, quality, location-related features, and other characteristics.

Files included:

* train.csv – Training data containing property features and sale prices.
* test.csv – Test data used to generate house price predictions.
* sample_submission.csv – Sample format for submitting predictions.
* data_description.txt – Description of the dataset features.

4. Methodology

The project follows these steps:

1. Load and understand the dataset.
2. Perform data preprocessing and handle missing values.
3. Encode categorical features and prepare numerical features.
4. Split the training data into training and validation sets.
5. Train and evaluate Linear Regression and Random Forest Regression models.
6. Compare model performance using MAE, RMSE, and R² score.
7. Use the best-performing model to predict house prices for the test dataset.

5. Results

The models were evaluated using the following metrics:

Model	MAE	RMSE	R² Score
Linear Regression	20466.13	31294.99	0.8723
Random Forest Regression	17394.56	28396.30	0.8949

Random Forest Regression performed better on the validation data, with a lower MAE and RMSE and a higher R² score.

6. Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook / Google Colab
* Matplotlib and Seaborn (if used in the notebook)

7. How to Run the Project

1. Download or clone this repository.
2. Open House_Price_Prediction_CA3.ipynb in Google Colab or Jupyter Notebook.
3. Make sure the required dataset files are available.
4. Run the notebook cells in order to preprocess the data, train the models, evaluate performance, and generate predictions.

8. Conclusion

The project demonstrates how machine learning can be used to predict residential house prices. Based on the validation results, Random Forest Regression achieved better performance than Linear Regression.

9. References

* Kaggle – House Prices: Advanced Regression Techniques: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
* Scikit-learn documentation: https://scikit-learn.org/
* Pandas documentation: https://pandas.pydata.org/
