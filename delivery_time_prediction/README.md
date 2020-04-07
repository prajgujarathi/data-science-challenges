# Food-delivery-Prediction-Model
PROBLEM STATEMENT
Before a consumer places an order on DoorDash, we show the expected delivery time. It is very important for DoorDash to get this right, as it has a big impact on consumer experience. Order lateness / underprediction of delivery time is of particular concern as past experiments suggest that underestimating delivery time is roughly twice as costly as overestimating it. Orders that are very early / late are also much worse than those that are only slightly early / late. In this exercise, you will build a model to predict the estimated time taken for a delivery. 

Concretely, for a given delivery you must predict the total delivery duration seconds, i.e., the time from 

● Start: the time consumer submits the order (`created_at`) to

● End: when the order will be delivered to the consumer (`actual_delivery_time`). 

To help with this, we have provided 

● historical_data.csv: table of historical deliveries (your training set) 

● data_to_predict.csv: data for deliveries that you must predict (label-free test set we will use for evaluation) 

● data_description.txt: description of all columns in historical_data.csv and details of data_to_predict.csv

Historical_data.ipynb is jupyter notebook, with training data preparation, cleaning, feature engineering and model creation
Prediction_data.ipynb is jupyter notebook, with test data preparation cleaning and prediction. 
Prediction.csv has prediction for delivery_id. 

Food_Delivery_Time_Prediction.docx is report created for this data challange. 

## Author

- **Prajakta Gujarathi** [LinkedIn](https://www.linkedin.com/in/prajakta-gujarathi/)
