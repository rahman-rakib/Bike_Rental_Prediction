This project aims at predicting bike rental rate based on weather and holiday information. 
The dataset contains hourly count of public bikes rented in Seoul Bike Sharing System, 
along with the corresponding weather data and holidays information, and is available at: 
https://archive.ics.uci.edu/ml/machine-learning-databases/00560/SeoulBikeData.csv

After extensive feature engineering of raw data, an r2_score > 0.87 achieved by training a 
neural network with appropriate learning rate. Linear Regression does not give good results
indicating non-linearity in the problem. We use Keras and TensorFlow, and tried five different
learning rate values: 1e-1, 1e-2, 1e-3, 1e-4, 1e-5, to find the optimal one for given 10_000
training epochs.   