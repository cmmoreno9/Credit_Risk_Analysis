# Credit Risk Analysis

![image](https://github.com/cmmoreno9/Credit_Risk_Analysis/blob/e0f9d4c793552bd38de942e0c03a343b8456e7eb/screenshots/credit-risk-197344-zsOma8Hj.jpeg)

Apply machine learning tecniques to identify high and low credit risk. Need to employ a multitude of techniques to train and evaluate the models needed for credit risk analysis. Interpretation will take place in utilizing  decision tree, logistic regression, random forest, and support vector machine algorithms.

# Results 

## Naive Random Oversampling
- Precision high for low-risk, but is inadequate for high-risk
- Balanced accuracy = ~ 0.674
- Recall = .74/.61 

![image](https://github.com/cmmoreno9/Credit_Risk_Analysis/blob/3dc7fa3506d0d346aac8c1f11285635d0cfbf63b/screenshots/Screen%20Shot%202022-07-15%20at%207.01.05%20PM.png)

## SMOTE Oversampling 
- Precision high for low-risk, but is inadequate for high-risk
- Balanced accuracy = ~ 0.662
- Recall = .63/.69

![image](https://github.com/cmmoreno9/Credit_Risk_Analysis/blob/3dc7fa3506d0d346aac8c1f11285635d0cfbf63b/screenshots/Screen%20Shot%202022-07-15%20at%207.11.03%20PM.png)

## Undersampling
- Precision high for low-risk, but is inadequate for high-risk
- Balanced accuracy =  ~ 0.545
- Recall = .69/.40 

![image](https://github.com/cmmoreno9/Credit_Risk_Analysis/blob/3dc7fa3506d0d346aac8c1f11285635d0cfbf63b/screenshots/Screen%20Shot%202022-07-15%20at%207.11.13%20PM.png)

## Combination (Over & Under Sampling)
- Precision high for low-risk, but is inadequate for high-risk
- Balanced accuracy = ~ 0.645
- Recall = 0.72/0.57

![image](https://github.com/cmmoreno9/Credit_Risk_Analysis/blob/3dc7fa3506d0d346aac8c1f11285635d0cfbf63b/screenshots/Screen%20Shot%202022-07-15%20at%207.11.23%20PM.png)

## Ensemble Classifiers


# Summary 

Overall, it is clear to see that the precision between all four samples are extremely similar. Additionally the high accuracy score fell between mid 50s and 60s. The highest accuracy score reached about 0.67. However, based on the recall score, which must be between 0-1, the SMOTE oversampling may be the best option as the other models are above 1. 

