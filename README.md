# Stroke-Prediction-With-Machine-Learning
## Intorduction
In this study, we will take a closer look at stroke. First of all what is stroke ? Stroke is a lifethreatening medical condition that happens when the blood supply to part of the brain is cut off.
Although it has decreased in recent years, it is still important medical issue. A person who has had a
stroke requires immediate treatment. The main risk factor for stroke is high blood pressure. Other risk factors include tobacco
smoking, obesity, high blood cholesterol and many more. For this reason, it is important to estimate the risk of
stroke and necessary precautions should be taken. In this study we are using a dataset from kaggle.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters.

## Problem
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death
globally, responsible for approximately 11% of total deaths. In this study we are trying to predict the possibility of having a stroke in the future.

## Dataset
We are using a stroke prediction dataset from kaggle.com. In this dataset we have 12
attribute and more than 5000+ data.
These attributes are
* id: unique identifier
* gender: "Male", "Female" or "Other"
* age: age of the patient
* hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
* heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart
disease
* ever_married: "No" or "Yes"
* work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
* Residence_type: "Rural" or "Urban"
* avg_glucose_level: average glucose level in blood
* bmi: body mass index
* smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"
* stroke: 1 if the patient had a stroke or 0 if not

In this data set we have numerical attributes such as 'age', 'avg_glucose_level' and 'bmi'. Also we
have categorical attributes such as 'gender', 'Residence_type' and 'work_type'.


Default Parameters             |  Best Parameters
:-------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/45359225/189525693-ae37ee52-1b9b-47ed-9a9b-683793e2513b.png)  |  ![image](https://user-images.githubusercontent.com/45359225/189525712-463893ad-277b-48c4-97de-c8020096c90e.png)


|               | Algorithm     | Accuracy|
| ------------- |:-------------:| -----:|
| 6      | BNB | 67.090532 |
| 0      | LR  | 83.253464 |
| 1      | SVM | 83.356262 |
| 3      | GNB | 84.660572 |
| 2      | KNN | 89.018762 |
| 4      | DT  | 90.803699 |
| 7      | XGB | 93.239907 |
| 5      | RF  | 93.926367 |
	

