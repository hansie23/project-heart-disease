# project-heart-disease
Classification problem

## Predicting heart disease using machine learning
### Approach:

- Problem definition:<br>
        - Given clinical parameters about a patient, can we predict whether or not they have heart disease?
    
- Data:<br>
        - The original data came from the Cleaveland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/heart+disease <br>
    There is also a version of it available on Kaggle. https://www.kaggle.com/ronitf/heart-disease-uci
    
- Evaluation:<br>
        - If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.
    
- Features:<br>
        - Different information about each of the features in the data can be found here.

    1. age: age in years
    2. sex: sex (1 = male; 0 = female)
    3. cp: chest pain type

        Value 1: typical angina   
        Value 2: atypical angina
        Value 3: non-anginal pain
        Value 4: asymptomatic
    4. trestbps: resting blood pressure (in mm Hg on admission to the hospital)
    5. chol: serum cholestoral in mg/dl
    6. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
    7. restecg: resting electrocardiographic results
        Value 0: normal
        Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
        Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
    8. thalach: maximum heart rate achieved
    9. exang: exercise induced angina (1 = yes; 0 = no)
    10. oldpeak = ST depression induced by exercise relative to rest
    11. slope: the slope of the peak exercise ST segment
        Value 1: upsloping
        Value 2: flat
        Value 3: downsloping
    12. ca: number of major vessels (0-3) colored by flourosopy
    13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
    14. target: diagnosis of heart disease (angiographic disease status)(the predicted attribute)
        Value 0: < 50% diameter narrowing (no)
        Value 1: > 50% diameter narrowing (yes)
        (in any major vessel: attributes 59 through 68 are vessels)
    
- Modelling:
        - Train on training set and test on test set.
    Trying 3 ML models:
    1. Logistic Regression
    2. K-Nearest Neighbours Classifier
    3. Random Forest Classifier
