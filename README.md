# Heart_Disease_Identification

In recent times, heart diseases remains the leading cause of death worldwide, but its nature and contributing factors have evolved over time. Some of the major factors leading to heart diseases can be:
* Unhealthy diet
* Physical inactivity
* High Blood Pressure
* High Cholestrol
* Smoking and Tobacco
* Alcohol Consumption
* Chronic Stress
* Sleep disorders, etc.

Identifying the presence of heart diseases at an early stage can help to prevent the severity and save the individual's life. This project aims to identify the presence of Heart Diseases in a patient based on various attributes. The Dataset for this project has been taken from [UCI Machine Learning Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease) provided from Cleveland Database. 

The attributes in the dataset is interpreted as:
- **age** (Feature): age of the patient in years
- **sex** (Feature): sex of the patient (1: Male, 0: Female)
- **cp** (Feature): chest pain type 
                - Value 1: typical angina
                - Value 2: atypical angina
                - Value 3: non-anginal pain 
                - Value 4: asymptomatic
- **trestbps** (Feature): resting blood pressure in `mm Hg` on admission to the Hospital
- **chol** (Feature): serum cholesterol in `mg/dl`
- **fbs** (Feature): fasting blood sugar > 120 mg/dl (1: Yes, 0: No)
- **restecg** (Feature): resting electrocardiographic results
                - Value 0: normal
                - Value 1: having ST-T wave abnormality 
                - Value 2: showing probable or definite left ventricualr hypertropy
- **thalach** (Feature): maximum heart rate achieved
- **exang** (Feature): exercise induced angina (1: Yes, 0: No)
- **oldpeak** (Feature): ST depression induced by exercise relative to rest
- **slope** (Feature): the slope of the peak exercise ST segment
                - Value 1: upsloping
                - Value 2: flat
                - Value 3: downsloping
- **ca** (Feature): number of major vessels (0-3) colored by flourosopy
- **thal** (Feature): blood disorder called "Thalassemia"
                - Value 0: null (dropped from the dataset previously)
                - Value 1: fixed defect (no blood flow in some part of the heart)
                - Value 2: normal blood flow
                - Value 3: reversible defect (a blood flow is observed but it is not normal)
- **num** (Target): diagnosis of heart disease (0: Yes, 1: No)