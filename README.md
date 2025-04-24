# 🚚 Food Delivery Time Prediction with LSTM

This project employs a Long Short-Term Memory (LSTM) neural network to predict food delivery times based on historical data. By analyzing factors such as delivery partner age, ratings, and the distance between the restaurant and the delivery location, the model aims to provide accurate delivery time estimates.

## 📌 Objective

Develop a predictive model using LSTM to estimate the time taken for food deliveries, enhancing transparency and efficiency for food delivery services.

## 📂 Dataset Overview

The dataset includes:

- **Delivery Partner Details**: ID, age, and ratings.
- **Location Data**: Latitude and longitude of restaurants and delivery locations.
- **Order Information**: Type of order and vehicle used.
- **Delivery Time**: Actual time taken for deliveries.

📎 [Dataset Source & Blog](https://thecleverprogrammer.com/2023/01/02/food-delivery-time-prediction-using-python/)

## 🧠 Approach

1. **Data Preprocessing**:
   - Load and inspect the dataset.
   - Check for null values and data types.

2. **Feature Engineering**:
   - Calculate the distance between restaurant and delivery location.
   - Select relevant features: delivery partner age, ratings, and distance.

3. **Model Building**:
   - Reshape input data to fit LSTM requirements.
   - Construct an LSTM model with two layers and dense output layers.
   - Compile the model using the Adam optimizer and mean squared error loss function.

4. **Model Training**:
   - Train the model over multiple epochs with a batch size of 1.

5. **Prediction**:
   - Input new data to predict delivery time.

## 🧰 Technologies Used

- Python
- Pandas & NumPy
- Keras (with TensorFlow backend)
- Plotly Express (for visualization)

## 📊 Results

The LSTM model is trained to predict delivery times based on input features. Sample prediction:

```python
Age of Delivery Partner: 29
Ratings of Previous Deliveries: 2.9
Total Distance: 6
Predicted Delivery Time in Minutes =  [[41.34929]]
```

## 🔮 Future Enhancements

- Incorporate additional features like weather and traffic conditions.
- Optimize the model architecture for better performance.
- Deploy the model as a REST API for integration with real-time systems.

## 🙏 Acknowledgments

Thanks to [The Clever Programmer](https://thecleverprogrammer.com/2023/01/02/food-delivery-time-prediction-using-python/) for providing the dataset and inspiration for this project.
