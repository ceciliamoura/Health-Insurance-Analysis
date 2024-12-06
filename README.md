# Identifying Predictors of Medical Charges for Healthcare Insurance

Target Audience: Cross-functional team of data and actuarial scientists at Healthcare Insurance Company

Objective: To communicate the findings of Phase 1 of an internal project aimed at identifying key predictors of medical charges. This information will be used to develop a predictive model in Phase 2.

Relevance: By accurately predicting future medical costs, we can set premiums that are both fair and profitable. Identifying high-risk individuals allows us to tailor coverage and pricing to specific needs.

Results: A Storyboard was created to communicate the results and final recommendation.
Three main predictors were identified: Age>42 years old, BMI > 30 and smoking. Isolated, the correlation between BMI and age to medical charges is weak, while smoking is the most significant factor related to high medical charges, with smokers paying nearly 4 times more than non-smokers. Smoking associated to obesity raised this rate to 4.7 times. 
There is only a small difference between the mean charges of male and females, with males having charges 11% higher than females. But, males also smoke more than females (The percentage of male smokers is 6.3% higher than the percentage of female smokers.), which could be the real reason why males have slightly higher medical charges than females.  
No other significant difference was found.

Final recommendation: The complex interplay between BMI, age and smoking suggests that random forest modeling would be suitable for the next phase of this project.
