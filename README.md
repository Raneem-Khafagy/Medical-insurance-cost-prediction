# Medical insurance cost prediction

## Abstract
A health insurance business can only make money if it collects more than it spends on its beneficiaries' medical care. On the other hand, while some conditions are more common in certain segments of the population, estimating medical costs is challenging because the majority of money comes from people with rare conditions.
The goal of this project is to accurately predict insurance prices based on people's data, such as age, BMI, smoking status, and so on.

This was a Community prediction kaggle Competition [Emotion Detection From Facial Expressions](https://www.kaggle.com/competitions/emotion-detection-from-facial-expressions/overview)

## Data
I used [Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance) 
**[age, gender,	bmi,	children,	smoking state, region, charges]** 
I worked with a total of 1337 data point 1069 for trainig, another 268 for validation and 134 for evaluation.


## Model 
 I used linear regression model consisting of two layers 1st one is 128 node and the other is 64, performance of the model is scored using cosine_similarity: 0.9776 with  MSE loss: 0.0075



