# Predicting-Heart-Disease

The task is to predict whether a subject has heart disease based on 13 attributes. The "Heart Disease Data Set" can be found at https://archive.ics.uci.edu/ml/datasets/Heart+Disease. Each observation represents a patient, and there is a total of 303 observations.

I use a K Nearest Neighbors Classifier, Logistic Regression, and Random Forest Classifier on the data and determine feature importance. 

## Attributes

1. age

2. sex (1 = male; 0 = female)

3. cp: chest pain type (1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)

4. restbps: resting blood pressure (in mm Hg on admission to the hospital)

5. chol: serum cholesterol in mg/dl

6. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

7. restecg: resting electrocardiographic results -- 0 = normal -- 1 = having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) -- 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria

8. thalach: maximum heart rate achieved

9. exang: exercise induced angina (1 = yes; 0 = no)

10. oldpeak = ST depression induced by exercise relative to rest

11. slope: the slope of the peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping)

12. ca: number of major vessels (0-3) colored by flourosopy

13. thal (3 = normal; 6 = fixed defect; 7 = reversable defect)

14. num: diagnosis of heart disease (angiographic disease status) -- 0: < 50% diameter narrowing (no heart disease) -- 1-4: > 50% diameter narrowing (heart disease)
