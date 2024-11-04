The data
The dataset named "Cleveland Heart Disease Dataset" comes from a study conducted in 1988 and originates from the UCI Machine Learning Repository. The dataset was split in two: a training and a testing set. The task is to get the best predictor and guess if a patient has a heart disease.

Features
The dataset is provided in the same format we have gotten it. Often the data needs to be cleaned and formatted, this step has already taken care of by the providers of the dataset. No column names appear in the original dataset, so you will need to add them on your own.

There are 14 columns:

age. The age of the patient.
sex. The gender of the patient. (1 = male, 0 = female).
cp. Type of chest pain. (1 = typical angina, 2 = atypical angina, 3 = non — anginal pain, 4 = asymptotic).
trestbps. Resting blood pressure in mmHg.
chol. Serum Cholestero in mg/dl.
fbs. Fasting Blood Sugar. (1 = fasting blood sugar is more than 120mg/dl, 0 = otherwise).
restecg. Resting ElectroCardioGraphic results (0 = normal, 1 = ST-T wave abnormality, 2 = left ventricular hyperthrophy).
thalach. Max heart rate achieved.
exang. Exercise induced angina (1 = yes, 0 = no).
oldpeak. ST depression induced by exercise relative to rest.
slope. Peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping).
ca. Number of major vessels (0–3) colored by flourosopy.
thal. Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect).
num. Diagnosis of heart disease (0 = absence, 1, 2, 3, 4 = present).
What to predict?
The last attribute num is the one we are trying to predict. You are supposed to provide a probability between 0 and 1 describing how confident your model is in predicting whether or not a patient has a heart disease.

