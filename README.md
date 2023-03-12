# Yes-Bank-Stock-Price-Prediction---ML-model
## Introduction
Yes Bank Limited is an Indian private sector bank headquartered in Mumbai, India and was founded by Rana Kapoor and Ashok Kapur in 2004. It offers wide range of differentiated products for corporate and retail customers through retail banking and asset management services. On 5 March 2020, in an attempt to avoid the collapse of the bank, which had an excessive amount of bad loans, the Reserve Bank of India (RBI) took control of it. To determine the yes bank stock value on national stock exchange by making the machine learning model of regression. The efficient market hypothesis recommends that the stock cost mirror all right now accessible data and any value change that are not founded on a recently uncovered data subsequently are unpredictable. We have to build a model that predicts the stock's future price.

## Problem Statement
![download](https://user-images.githubusercontent.com/118215277/224531650-fddbeaa4-1150-4a3c-8c2d-4eb6c6e3f1c9.png)

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

## EDA
1. Line chart


![download (1)](https://user-images.githubusercontent.com/118215277/224532062-3a7e644a-6872-4add-b663-b9e3b0577385.png)

2. Scatter Plot

![download](https://user-images.githubusercontent.com/118215277/224532131-3ec22fc0-7705-4c6f-a987-32802470a5bb.png)

3. Distribution plot

![download (2)](https://user-images.githubusercontent.com/118215277/224532176-f59e100f-f00b-4cf7-8642-dd04565621d8.png)

4. Box plot

 ![download (3)](https://user-images.githubusercontent.com/118215277/224532182-65e72e7f-9c4f-4dda-83e9-922a62ab9bd8.png)

5. Heatmap

![download (4)](https://user-images.githubusercontent.com/118215277/224532190-07c8e592-26a1-4734-9f7b-41c9e0639416.png)


## Models
1. Linear Regression

![download (5)](https://user-images.githubusercontent.com/118215277/224532345-cda42c42-1f6c-4bca-80ca-190134bb2215.png)

2. Lasso Regression

![download (6)](https://user-images.githubusercontent.com/118215277/224532359-ae2a9405-7f28-4ce5-9990-6df0c85b55a1.png)

3. Ridge Regression

![download (7)](https://user-images.githubusercontent.com/118215277/224532364-ba120614-2e7e-4174-b312-572525a42ace.png)

4. ElasticNet Regression

![download (8)](https://user-images.githubusercontent.com/118215277/224532369-f954905f-13e1-47a6-8255-99e1b3acf6ed.png)

## Conclusion
There is increase in trend of Yes Bank's stock's Close,Open,High,Low price till 2018 and then sudden decrease.

We observed that open vs close price graph concluded that after 2018 yes bank's stock hitted drastically.

We saw Linear relation between the dependent and independent values.

There was alot of multicollinearity present in data.

Target variable(dependent variable) strongly dependent on independent variables

We get maximum accuracy of 99%.

Linear regression and Ridge regression get almost same R squared value

Lasso model shows lowest R squared value and high MSE,RMSE,MAE,MAPE
