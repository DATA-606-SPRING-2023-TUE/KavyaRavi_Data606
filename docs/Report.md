# Diabetes Prediction for Pregnant Women and General Population

1. PPT Link: https://docs.google.com/presentation/d/1g-lk28j1BySQKMQ4WP_yZVF_0u-S_hzC6M9iPuj2_Lo/edit#slide=id.gd251bb473_0_600
2. YouTube Video Link: https://www.youtube.com/watch?v=fyHyX9l8FJ4

# Contents:
1. Introduction.
2. Datasets.
3. Abstract.
4. Methodology.
5. Data Visualizations.
6. Feature Engineering and Machine Leaning Models.
7. Conclusion.

# 1. Introduction

Diabetes, a chronic metabolic disorder characterized by elevated blood sugar levels, has emerged as a significant global health concern. The prevalence of diabetes has been steadily increasing worldwide, posing a substantial burden on individuals, families, healthcare systems, and society as a whole. Given its severe health consequences and the associated economic impact, understanding the factors influencing diabetes onset and progression is crucial.

This project report delves into the analysis and prediction of diabetes using two distinct datasets: the Pregnant Women Diabetes Dataset and the General Population Diabetes Dataset. The aim of this study is to identify potential risk factors and develop predictive models for early detection and intervention.

Why is this project about diabetes important?

Public Health Significance:
Diabetes affects millions of individuals globally, contributing to increased morbidity, mortality, and reduced quality of life. By conducting an in-depth analysis of diabetes data, this project aims to contribute to the existing body of knowledge on diabetes risk factors, management strategies, and early detection methods. The findings can help healthcare professionals, policymakers, and researchers develop targeted interventions and preventive measures to reduce the incidence and impact of diabetes.

Pregnancy-Specific Challenges:
Pregnancy adds a layer of complexity to diabetes management, as the hormonal and physiological changes that occur during this period can influence blood sugar regulation. Pregnant women with diabetes are at higher risk of adverse maternal and fetal outcomes. By focusing on the pregnant women diabetes dataset, this project aims to identify specific risk factors, optimize diabetes management strategies during pregnancy, and improve overall maternal and neonatal health.

Comparative Analysis:
Comparing the pregnant women diabetes dataset with the general population diabetes dataset allows for a comprehensive examination of the similarities and differences between these two cohorts. Understanding these distinctions can aid in tailoring healthcare interventions and developing personalized treatment plans for pregnant women with diabetes, thus optimizing their health outcomes.

Predictive Modeling:
The utilization of predictive modeling techniques enables the identification of potential early indicators and risk factors associated with diabetes development in both pregnant women and the general population. By leveraging advanced data analysis and machine learning algorithms, this project aims to develop accurate prediction models that can assist healthcare providers in identifying individuals at risk, initiating timely interventions, and improving long-term prognosis.

In conclusion, this project serves as a comprehensive exploration of diabetes analysis and prediction using two distinct datasets. By shedding light on the unique challenges faced by pregnant women with diabetes and the general population, we hope to contribute to the development of effective preventive measures, personalized interventions, and improved healthcare outcomes for individuals affected by this pervasive chronic condition.







# 2. Datasets

We have 2 different datasets in this project. One dataset is specifically about pregnant women and other dataset is about general population with/without diabetes.
Both these datasets have different attributes and significance. The pregnant women dataset have following attributes.

1. Pregnancies: Number of times pregnant.
2. Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3. Blood Pressure: Diastolic blood pressure (mm Hg)
4. SkinThickness: Triceps skin fold thickness (mm)
5. Insulin: 2-Hour serum insulin (mu U/ml)
6. DiabetsPedigreeFunction: A function that calculates the probability of having diabetes according to one's descendants
7. BMI: Body mass index (weight in kg/(height in m)^2)
8. Age: Age (years)
9. Outcome: Class variable (0 or 1)

On the other hand, the general population dataset has following attributes:
1. Diabetes_01 : Whether the patient is diabetes or not. O indicates non-diabetic.
2. HighBP: Whether or not the Blood Pressure of the Patient is high.
3. HighChol: Whether or not the cholestrol of the patient is high.
4. BMI: Body Mass Index (weight in kg/(height in m)^2)
5. Smoker: Whether the patient is smoker or not.
6. Stoke:
7. HeartDisease: coronary heart disease (CHD) or myocardial infarction (MI) 0 = no 1 = yes
8. PhysActivity:physical activity in past 30 days - not including job 0 = no 1 = yes
9. Fruits: Consume Fruit 1 or more times per day 0 = no 1 = yes
10. Veggies: Consume Vegetables 1 or more times per day 0 = no 1 = yes
11. HvyAlcoholCons: Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week) 0 = no
12. AnyHealthcare : Have any kind of health care coverage, including health insurance, prepaid plans such as
13. NoDocbcCost: Was there a time in the past 12 months when you needed to see a doctor but could not because of cost? 0 = no 1 = yes
14. GenHlth: General your health is: scale 1-5 1 = excellent 2 = very good 3 = good 4 = fair 5 = poor
15. MenHlth:  stress, depression, and problems with emotions
16. PhysHlth: Physical illness and injury, for how many days during the past 30
17. DiffWalk:Do you have serious difficulty walking or climbing stairs? 0 = no 1 = yes
18. Sex: Male or Female
19. Education: Educated or Not
20. Age: Age of the patient
21. Income: Income of the patien

# 3. Abstract
The motivation behind this project was to gain hands-on experience in developing a complete machine learning project. Additionally, the growing health issue of diabetes, caused by sedentary lifestyles, inspired the project. Early detection of diabetes through proper medical treatment can prevent severe health complications. By utilizing technology, such as machine learning, a predictive model can be built to determine if a patient has diabetes. This project not only provides a learning opportunity but also has the potential to benefit society.


# 4. Methodology: 
There are many different methods for using machine learning algorithms for diabetes prediction. The following is an overview of the typical stages required in creating a machine learning model for diabetes prediction:

1.Data Gathering: The first step is to gather appropriate data for training the model. This includes diabetes datasets discussed in introduction section.

2.Data Preprocessing: After collecting the data, it must be preprocessed to ensure its quality and effectiveness for training the machine learning model. Data cleaning,removing outliers, dealing with missing numbers, and normalizing or scaling the data are all part of this stage.

3.Feature Selection: The most relevant features or variables from the dataset are selected in this step. This can include statistical analysis, domain knowledge, and correlation analysis to determine which features have the most effect on diabetes prediction.

4.Model Selection: Trying out many different models on the dataset and determine which models give highest level of accuracy.

5.Model Evaluation: The trained model's performance is evaluated using the validation set. 

# 5. Data Visualizations:
 
## Dataset 1: Pregnant Women Dataset.
![image](https://github.com/DATA-606-SPRING-2023-TUE/KavyaRavi_Data606/assets/40602114/faf8b257-1144-4aa6-85c2-dc718f11163b)

 ### Inference: 35% of the population in this dataset in diabetic
 
 <br>
 ### Pregnancies VS Diabetes
 ![image](https://github.com/DATA-606-SPRING-2023-TUE/KavyaRavi_Data606/assets/40602114/96588e27-aa62-4a2a-ad0f-0c6165a56320)
### Inference: Number of Pregnancies is directly proportinal to diabetes
 
 

### BloodPressure VS Diabetes
![image](https://github.com/DATA-606-SPRING-2023-TUE/KavyaRavi_Data606/assets/40602114/c7fb34c5-8b1d-41bc-aea7-5959157f190e)
 
 
 
### BMI VS Diabetes
![image](https://github.com/DATA-606-SPRING-2023-TUE/KavyaRavi_Data606/assets/40602114/f9be3148-7e2d-4012-96ac-9fb12594721f)
### Inference: Blood Pressure and BMI are directly proprtinal to diabets
 
 
 
## Dataset 2: General Population Dataset.
 
### Patient Profile
![image](https://github.com/DATA-606-SPRING-2023-TUE/KavyaRavi_Data606/assets/40602114/ad6a7bae-1af4-492c-9f04-40cf506aa736)

 
 ### Patient Health Evaluation
![image](https://github.com/DATA-606-SPRING-2023-TUE/KavyaRavi_Data606/assets/40602114/a95a5835-8f08-4942-a772-d552ab270e7c)
![image](https://github.com/DATA-606-SPRING-2023-TUE/KavyaRavi_Data606/assets/40602114/bf79179a-3bf2-45bb-9f1b-f29a3cf7a10d)

 
 
### Patient Habit Evaluation
![image](https://github.com/DATA-606-SPRING-2023-TUE/KavyaRavi_Data606/assets/40602114/dc84cb68-53f2-4fd1-ae2f-528a54a09060)

# 6. Machine Learning Models.

 For Dataset 1, we trained three different Models and following are their prediction accuracy scores.
 1. Support Vector Machine (SVM): Achieved a prediction accuracy of 77.04%.
 2. Support Vector Classifier (SVC): Demonstrated a prediction accuracy of 76.623%.
 3. Logistic Regression Model: Attained a prediction accuracy of 75.97%.

 
 For Dataset 2, we trained three different models and following are their prediction accuracies:
 1. Logistic Regression: Demonstrated an impressive prediction accuracy of 97.87%.
 2. Random Forest: Achieved a remarkably high prediction accuracy of 99.88%.
 3. Decision Tree: Attained a commendable prediction accuracy of 99.83%.

# 7. Conclusion: 

In conclusion, our analysis of the two datasets revealed varying performance among different prediction models for diabetes. For Dataset 1 (Pregnant Women Diabetes Dataset), the SVM model achieved the highest accuracy of 77.04%, followed by SVC (76.623%) and Logistic Regression (75.97%). For Dataset 2 (General Population Diabetes Dataset), the Random Forest and Decision Tree models demonstrated exceptional accuracy, with scores of 99.88% and 99.83%, respectively, outperforming Logistic Regression (97.87%). These findings highlight the importance of selecting appropriate models based on the dataset and population under study. Accurate prediction of diabetes outcomes can enable early intervention and improve healthcare strategies for individuals affected by diabetes.


```python

```
