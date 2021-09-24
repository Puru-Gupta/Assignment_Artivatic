# Assignment_Artivatic
Helping bank by predicting the probability that a member will default.   
# Flight-Price-Prediction
### Flight-Price-Prediction

1. [Problem Statement ](#PROBLEM)
2. [File Descriptions](#files)
3. [Results](#results)
4. [Exploratory Data Analysis](#Exploratory)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Problem Statement <a name="PROBLEM"></a>

 
The Bank Indessa has not done well in the last 3 quarters. Their NPAs (Non Performing Assets) have reached all time high. It is starting to lose the confidence of its investors. As a result, it’s stock has fallen by 20% in the previous quarter alone.  
After careful analysis, it was found that the majority of NPA was contributed by loan defaulters. With the messy data collected over all the years, this bank has decided to use machine learning to figure out a way to find these defaulters and devise a plan to reduce them.<br>  
This bank uses a pool of investors to sanction their loans. <br><br>

For example: If any customer has applied for a loan of $20000, along with the bank, the investors perform due diligence on the requested loan application. Keep this in mind while understanding data.  
In this challenge, we need help this bank by predicting the probability that a member will default. 

## File Descriptions <a name="files"></a>

![image](https://user-images.githubusercontent.com/55012359/134719401-34abf38a-56ba-4c4c-96b0-cc4c023c8490.png)
![image](https://user-images.githubusercontent.com/55012359/134719454-2d4a6539-a86a-4e97-b5c6-2c5c2a5496b8.png)
![image](https://user-images.githubusercontent.com/55012359/134719621-4a132389-ec19-4966-a012-c5e340c6bdaf.png)

 
## Results<a name="results"></a>

The main findings of the code can be found below

## 3. Modelling and Evaluation
###**We will compare four different machine learning Cassification models:**

1 - Logistic Regression<br>
2 - Random Forest Classification<br>
3 - XGBoost<br>
4 - Deep neral network Tensorflow 2.0

* Metric - ROC_AUC used for selecting Model

## 4. Results
**Deep learning with keras tensorflow_AUC   =0.96**<br>
**RandomForest_AUC        = 0.922**<br>
**XGBoost_AUC             = 0.905**<br>
**Logistic_Regression_AUC = 0.88**<br>
**DTClassifier            = 0.87**

Final Model uswed for prediction is Deep learning with keras tensorflow

#### Feature correlation
![Feature correlation]
![heatmap]![image](https://user-images.githubusercontent.com/55012359/134720361-105eb609-40f3-4fea-a22f-f3264b365d46.png)
# Exploratory Data Analysis<a name="Exploratory"></a>
![source]![image](https://user-images.githubusercontent.com/55012359/134720440-910a91fd-e186-475f-a3a2-755f316ace95.png)
<br>
![image](https://user-images.githubusercontent.com/55012359/134720586-4ee9b295-c9af-4365-8ad0-28246b66fcf3.png)
<br>
![image](https://user-images.githubusercontent.com/55012359/134720635-5026422b-9f0f-4cd5-87a4-7d8189b13b59.png)
<br>
![image](https://user-images.githubusercontent.com/55012359/134720664-4e4adf32-1b51-4132-a387-f8de20722572.png)


## Data Modelling
A total of 5 different models were used for prediction cross validation were the primary metrics used for evaluating the models. 

**Deep learning with keras tensorflow_AUC   =0.96**<br>
**RandomForest_AUC        = 0.922**<br>
**XGBoost_AUC             = 0.905**<br>
**Logistic_Regression_AUC = 0.88**<br>
**DTClassifier            = 0.87**

- Based on AUC value, it can be observed that the Deep learning with keras tensorflow model have the highest variability Explained.<br>
![image](https://user-images.githubusercontent.com/55012359/134721209-58c6d3fc-cd6e-4ff9-b7bd-43b42ce51901.png)


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credited to Kaggle for availability of the data. You can find the License for the data and other descriptive information in the Kaggle available 
