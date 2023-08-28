## Analysis objective
Detect whether a specific flight has the potential to be delayed or not.

## The dataset
- This dataset contains multi-year data from 2009 to 2018.
- The dataset is nearly 7 GB in size, with almost 68 million rows. For this reason, I utilized Apache Spark and MLib.
- Data source via Kaggle: https://www.kaggle.com/datasets/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018

## Challenge of flights
The challenge itself was to detect, through machine learning models, whether a flight is more likely to be canceled or not. My final model was inform the percentage possibility to delay each flight.
With this model, airlines can use to make better decisions to take preemptive actions that do not impact passengers.
My regression model prediction is fluctuating around 65 points in relation to the actual value. Can be improved adding more data from the previous years also.
