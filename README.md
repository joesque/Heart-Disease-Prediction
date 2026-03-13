# Heart Disease Prediction Model

In this project, I am using a dataset from Kaggle containing clinical data to predict heart attack occurances.

The dataset contains the following features:
1. **Age** : Age of the patient
2. **Sex** : Sex of the patient
3. **exang**: exercise induced angina
    - 1: yes
    - 0: no
4. **ca**: number of major vessels (0-3)
5. **cp** : Chest Pain type chest pain type
    - Value 1: typical angina
    - Value 2: atypical angina
    - Value 3: non-anginal pain
    - Value 4: asymptomatic trtbps : resting blood pressure (in mm Hg)
6. **chol** : cholestoral in mg/dl fetched via BMI sensor
7. **fbs** : fasting blood sugar > 120 mg/dl
    - 1: true
    - 0: false)
8. **rest_ecg** : resting electrocardiographic results
    - Value 0: normal
    - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria thalach : maximum heart rate achieved
9. **thalachh**: Maximum heart rate achieved during a stress test exng: Exercise induced angina 
  - 0: no
  - 1: yes
10. **oldpeak:** ST depression induced by exercise relative to rest (unit -> depression)
11. **slp:** Slope of the peak exercise ST segment
    - 0: Upsloping
    - 1: Flat
    - 2: Downsloping
12. **caa:** Number of major vessels (0-4) colored by fluoroscopy thall: Thalium stress test result 
  - 0: Normal
  - 1: Fixed defect
  - 2: Reversible defect
  - 3: Not described
13. **target** :
    - 0: less chance of heart attack
    - 1: more chance of heart attack

The workflow includes exploratory data analysis (EDA), visualisation, feature engineering such as handling missing values and outliers, building machine learning models to predict the likelihood of heart disease and finally, evaluating these models.
