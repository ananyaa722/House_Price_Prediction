House Price Prediction

Machine Learning Internship Task 2 – Prodigy InfoTech

Project Overview

This project focuses on predicting house prices using Python and Machine Learning techniques. A Linear Regression model is trained on housing data to estimate house values based on different features.

Dataset

The project uses the California Housing Dataset, which contains information about housing areas.

The dataset includes the following features:

- MedInc – Median income
- HouseAge – Average house age
- AveRooms – Average number of rooms
- AveBedrms – Average number of bedrooms
- Population – Population of the area
- AveOccup – Average household occupancy
- Latitude – Geographical latitude
- Longitude – Geographical longitude
- MedHouseVal – Median house value (target variable)

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Project Workflow

1. Loaded and explored the dataset.
2. Checked dataset information and missing values.
3. Performed data preprocessing.
4. Visualized housing data using graphs.
5. Split the dataset into training and testing sets.
6. Trained a Linear Regression model.
7. Evaluated the model using performance metrics.
8. Compared actual and predicted house values.
9. Visualized prediction errors and feature coefficients.

Model Used

Linear Regression

Linear Regression is a supervised machine learning algorithm used to predict continuous values. In this project, it is used to estimate house values based on the available housing features.

Results

- Training samples: 16,512
- Testing samples: 4,128
- Mean Absolute Error (MAE): 0.5332
- R-squared Score (R²): 0.5758

The model was evaluated by comparing actual house values with predicted values. The results and visualizations help demonstrate how well the model estimates housing prices.

Note: The target values are measured in units of $100,000.

Files

- "House_Price_Prediction.ipynb" – Jupyter Notebook containing the project code, analysis, model training, evaluation, and visualizations.

How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run the cells in order.
3. Make sure the required Python libraries are installed.
4. Review the output graphs and model evaluation results.

Install the required libraries using:

pip install pandas numpy matplotlib seaborn scikit-learn

Conclusion

This project demonstrates the use of Linear Regression for house price prediction. It covers data exploration, preprocessing, visualization, model training, and evaluation using Python and machine learning libraries.

The project helped develop practical understanding of the machine learning workflow and regression techniques.
