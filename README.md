# Random-Forest
In this notebook you will make a random forest. A random forest is a collection of random-ish decision trees. This model essentially combines the output of multiple decision trees to reach a particular prediction. Most jargon in Machine Learning is just ugly, imo. But Random Forest sounds nice to me, a little poetic. If I were a singer-songwriter, I could imagine titling my album after random forests.

In this Notebook we will revisit the Cleaveland Heart Disease Dataset, this time we will use a Random Forest to make our predictions rather than just using a single Decision Tree. Below is a summary of the variables that this dataset contains.

#3 Age: age in years
#4 Sex: sex (1 = male; 0 = female)
#9 Chest_pain_type
Value 1: typical angina
Value 2: atypical angina
Value 3: non-anginal pain
Value 4: asymptomatic
#10 At_rest_bp: resting blood pressure (in mm Hg on admission to the hospital)
#12 Cholesterol: serum cholestoral in mg/dl
#16 Fast_blood_sug: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
#19 Rest_ecg: resting electrocardiographic results
Value 0: normal
Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
#32 Maxhr: thalach: maximum heart rate achieved
#38 Exer_angina: exang: exercise induced angina (1 = yes; 0 = no)
#40 Oldpeak: ST depression induced by exercise relative to rest
#41 Slope: the slope of the peak exercise ST segment
Value 1: upsloping
Value 2: flat
Value 3: downsloping
#44 Ca: number of major vessels (0-3) colored by flourosopy
#51 Thal: Thallium or stress test 3 = normal; 6 = fixed defect; 7 = reversable defect. See this website for more info on the thallium or stress test.
#58 Diag: num: diagnosis of heart disease (angiographic disease status)
Value 0: no vessel with 50% diameter narrowing
Value 1: one vessel with 50% diameter narrowing
Value 2,3,4: 2,3,4 vessels with 50% diameter narrowing
