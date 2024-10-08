# Taxi_dispatch_system_using_data_mining
An intelligent taxi-dispatch system designed using the taxi trip records of yellow taxicabs in New York City

![MATLAB](https://img.shields.io/badge/MATLAB-R2023b-orange)


## Objective

* The main objective of this project is to create a model that predicts taxi demand around Manhattan and the airports region in New York City. 
* The demand is divided into three categories: High, Medium, and Low. The model will assign each region to one of the three categories on an hourly basis.
* One of the main focuses of the model is to accurately distinguish the high and medium-demand regions from the low-demand regions which would enable the taxicabs to focus on high-demand regions and avoid low-demand ones, thus improving efficiency and increasing profits.
* To explore the revenue (Fare) and cost (Duration and Distance) of each region to see if certain regions of the city are more profitable than others.
* To analyze the model performance to see how much loss was generated from the model's erroneous prediction.

## Challenges

* The main challenge is dealing with Big Data. The original taxicab dataset is huge with millions of taxi trip records. Moreover, the data is updated regularly on a monthly basis. The data for an entire year was used to train the ML model. The testing (prediction) was performed on the next year's same-month data.
* The data required quite a lot of preprocessing. Real-world datasets are quite messy and need processing to be able to be used for model training.
    

## Data 

Additional data was also collected from other sources to add information. This includes plane arrival schedules in nearby airports, weather information, and holiday information among others.

Taxi-trip data source: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Kaggle: https://www.kaggle.com/datasets/elemento/nyc-yellow-taxi-trip-data

### Note
MATLAB's "Classification Learner" app was utilized for model prediction.

## Screenshots

![Confusion Matrix](https://github.com/newaz-aa/Taxi_dispatch_system_using_data_mining/blob/main/Images/cost_test_raw.PNG)
