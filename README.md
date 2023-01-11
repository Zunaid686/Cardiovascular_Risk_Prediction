# Cardiovascular_Risk_Prediction

![image](https://user-images.githubusercontent.com/101803400/211762760-694a8ffc-d048-43ba-85db-17dc528c3aa2.png)





### Problem Statement: The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

Sex: male or female("M" or "F")

Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous) Behavioral

Is_smoking: whether or not the patient is a current smoker ("YES" or "NO")

Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.) Medical( history)

BP Meds: whether or not the patient was on blood pressure medication (Nominal)

Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)

Prevalent Hyp: whether or not the patient was hypertensive (Nominal)

Diabetes: whether or not the patient had diabetes (Nominal) Medical(current)

Tot Chol: total cholesterol level (Continuous)

Sys BP: systolic blood pressure (Continuous)

Dia BP: diastolic blood pressure (Continuous)

BMI: Body Mass Index (Continuous)

Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)

Glucose: glucose level (Continuous) Predict variable (desired target) 10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”) - DV



## EDA Conclusions

• Slightly more males are suffering from CHD than females .

• The people who has high BMI are at risk of CHD . 

• The people with hypertension are at high risk of CHD 

• The percentage of people who have CHD is almost equal between smokers and non-smokers .

• The uneducated people or the people with basic education are at high risk of CHD compared with well educated .


### Imbalance Dataset

I noticed that most of data is labelled as 0(having risk of coronary heart disease) about 90% and very few data is labelled as 1(don't have coronary heart disease). This means that their high <b> class imbalance </b>  for  solving this problem we having a technique called <b> SMOTE Technique </b> which created random samples to over come the class imbalance.


### Best Performing Algorithms

Support Vector Machines(SVM)

Adaboost

Random Forest
