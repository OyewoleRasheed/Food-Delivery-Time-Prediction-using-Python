# Food Delivery Time Prediction

This project focuses on predicting food delivery times using machine learning techniques in Python. It replicates and builds upon the work described [here](https://thecleverprogrammer.com/2023/01/02/food-delivery-time-prediction-using-python/).

## Project Overview

Food delivery companies like Zomato and Swiggy aim to estimate delivery times accurately to enhance customer satisfaction. This project uses real-world delivery data to train a machine learning model that predicts delivery times based on:

- Distance between restaurant and delivery location
- Delivery person's age and ratings
- Type of order and type of vehicle used

## Dataset

The dataset includes features such as:
- Delivery person ID, age, and ratings
- Restaurant and delivery location coordinates
- Type of order and vehicle
- Time taken (target variable)

## Key Steps

1. **Data Cleaning**: Verified no missing values.
2. **Feature Engineering**: Calculated distance between restaurant and customer using the haversine formula.
3. **Data Visualization**: Explored feature relationships using visualizations.
4. **Model Training**: Built and trained a machine learning model to predict delivery times.
5. **Evaluation**: Evaluated the model’s performance using standard metrics.

## Libraries Used

- `pandas`
- `numpy`
- `plotly`
- `scikit-learn`

## How to Run

1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy plotly scikit-learn
   ```
3. Run the Python script or Jupyter Notebook.

## Results

The model was able to predict delivery times with good accuracy, demonstrating the importance of distance and vehicle type among other factors.

## Acknowledgments

- [The Clever Programmer](https://thecleverprogrammer.com/) for the original tutorial and dataset source.
