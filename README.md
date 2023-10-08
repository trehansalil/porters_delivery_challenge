# Porters Delivery Challenge
This is more of an experiment around my knowledge on deep learning in the Neural Nets Space, here we will be understanding the space of Logistics and supply chain taking inspiration from the delhivery project.

# 
1. Basic Analysis
- Import the data and understand the structure of the data: usual exploratory analysis steps like checking the structure & characteristics of the dataset
- Data preprocessing
- Cleaning of data
- Feature engineering: Creating the target column time taken in each delivery from order timestamp (created_at) and delivery timestamp (actual_delivery_time)
- Getting hour of day from the order time and also the day of the week
- Understanding pandas datetime data type and what function it provides by default
- Get delivery time in minutes
- Handling null values
- Encoding categorical columns
- Data visualization and cleaning
- Visualize various columns for better understanding Countplots, scatterplots
- Check if the data contains outliers
- Removing outliers by any method
- Plotting the data again to see if anything has improved
- Split the data in train and test
- Creating a baseline model using random forest
- Checking its various metrics like MSE, RMSE, MAE
- Scaling the data for neural networks.
- Creating a simple neural network
2. Trying different configurations
- Understanding different activation functions, optimizers and other hyperparameters.
- Training the neural network for required amount of epochs
- Plotting the losses and checking the accuracy of the model
- Comparing the results of neural network and random forest