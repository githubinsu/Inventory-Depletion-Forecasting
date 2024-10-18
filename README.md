# Inventory Depletion Forecasting and Alert System using Exponential Weighted Moving Average (EWMA)

The provided code is for managing inventory using Exponential Weighted Moving Average (EWMA). 

Apply EWMA: It applies the EWMA model on the daily usage data of each product. The EWMA gives more weight to the recent data, hence, it is a good model for predicting inventory depletion.
Predict depletion: For each product, it calculates the expected days until the inventory runs out based on the last inventory and the last EWMA value.
If the inventory is expected to run out in 5 days or less, an alert message will be displayed, along with a recommendation for the optimal restock quantity.
