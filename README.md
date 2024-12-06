# Identifying Predictors of Medical Charges for Healthcare Insurance

Target Audience: Cross-functional team of data and actuarial scientists at Healthcare Insurance Company

Objective: To communicate the findings of Phase 1 of an internal project aimed at identifying key predictors of medical charges. This information will be used to develop a predictive model in Phase 2.

Relevance: By accurately predicting future medical costs, we can set premiums that are both fair and profitable. Identifying high-risk individuals allows us to tailor coverage and pricing to specific needs.

Results: A [Storyboard](https://public.tableau.com/app/profile/cecilia.moura/viz/HealthInsuranceAnalysisStoryboard/Story1?publish=yes) was created to communicate the results and final recommendation.
Three main predictors were identified: Age>42 years old, BMI > 30 and smoking. Isolated, the correlation between BMI and age to medical charges is weak, while smoking is the most significant factor related to high medical charges, with smokers paying nearly 4 times more than non-smokers. Smoking associated to obesity raised this rate to 4.7 times. 
There is only a small difference between the mean charges of male and females, with males having charges 11% higher than females. But, males also smoke more than females (The percentage of male smokers is 6.3% higher than the percentage of female smokers.), which could be the real reason why males have slightly higher medical charges than females.  
No other significant difference was found.
![corr_plot](https://github.com/user-attachments/assets/2369305c-1823-493b-9bf6-f02b17cabf6f)
Bellow: Scatterplots showing non-linear correlation between BMI, Age and Medical Charges
![bmi_vs_charges_scatterplot](https://github.com/user-attachments/assets/45b35b7e-2bc5-4592-968d-589baf680490)

![age_vs_charges_scatterplot](https://github.com/user-attachments/assets/62a443eb-15f1-4c48-be03-e5b4ae9bc732)

Plot Age vs. Charges. 
![Screenshot 2024-12-06 at 3 03 38 PM](https://github.com/user-attachments/assets/e2f23e9e-c9e2-4326-83ce-796306bf29fb)


Final recommendation: The complex interplay between BMI, age and smoking suggests that random forest modeling would be suitable for the next phase of this project.


**This is an educational project, developed to fullfill achievement 6.7 of the Data Analysis program of Career Foundry. Data used here was downloaded from Kaggle [here](https://www.kaggle.com/datasets/mirichoi0218/insurance?resource=download) in October of 2025.**
