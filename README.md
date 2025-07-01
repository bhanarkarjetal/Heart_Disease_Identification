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
- **sex** (Feature): sex of the patient 
    - Value 1: Male
    - Value 0: Female
- **cp** (Feature): chest pain type 
    - Value 1: typical angina
    - Value 2: atypical angina
    - Value 3: non-anginal pain 
    - Value 4: asymptomatic
- **trestbps** (Feature): resting blood pressure in `mm Hg` on admission to the Hospital
- **chol** (Feature): serum cholesterol in `mg/dl`
- **fbs** (Feature): fasting blood sugar > 120 mg/dl 
    - Value 1: Yes
    - Value 0: No
- **restecg** (Feature): resting electrocardiographic results
    - Value 0: normal
    - Value 1: having ST-T wave abnormality 
    - Value 2: showing probable or definite left ventricualr hypertropy
- **thalach** (Feature): maximum heart rate achieved
- **exang** (Feature): exercise induced angina
    - Value 1: Yes
    - Value 0: No
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
- **num** (Target): diagnosis of heart disease 
    - Value 1: Yes
    - Value 0: No

*(If you are interesed in knowing briefy about the medical terms used in the attributes, you can read it here, otherewise, you can move to the next section)*

- ***Angina***: *Chest pain caused by reduced blood flow to the heart muscle (due to narrowed arteries)*
    - *Typical angina: predictable chest pain during exertion or stress, relieved by rest*
    - *Atypical angina: less predictable, not always triggered by exertion*
    - *Non-anginal pain: chest pain not related to heart issues (e.g. muscular, gastrointestinal)*
    - *Asymptomatic: no chest pain even if heart disease is present (often seen in diabetics or elderly)*

- ***Resting Blood Pressure***: *Blood pressure measures in mm Hg when the patient is at rest. High blood pressure (hypertension) increases the workload on the heart and is a major risk factor for heart diseases.*

- ***Fasting Blood Sugar > 120 mg/dL***: *Indicates elevated blood glucose (possible diabetes or prediabetes). High blood sugar damages blood vessels and nerves, increasing heart disease risk.*

- ***Resting Electrocardiographic Results (ECG/EKG)***: *Assesses heart’s electrical activity at rest:*
    - *Normal: No signs of damage or abnormal rhythm.*
    - *ST-T wave abnormality: Suggests ischemia (inadequate blood flow to the heart) or previous heart attack.*
    - *Probable/definite left ventricular hypertrophy (LVH): Thickening of the heart's left ventricle wall due to high BP or heart disease (a strong predictor of cardiovascular risk).*

- ***Maximum Heart Rate Achieved***: *higher values during stress testing indicate better cardiovascular fitness. Inability to reach a high heart rate can signal blocked arteries or poor heart function.*

- ***Exercise-Induced Angina***: *Chest pain during exercise due to restricted blood flow to heart muscles. Indicates underlying coronary artery disease.*

- ***ST Depression (in mm)***: *The difference in the ST segment of the ECG during exercise vs rest. ST depression during exercise suggests myocardial ischemia (lack of oxygen in heart muscle).*

- ***Slope of ST Segment***: *Describes the shape of the ST segment, which helps assess cardiac stress response*
    - *Upsloping: Usually normal or less concerning.*
    - *Flat: May indicate ischemia.*
    - *Downsloping: Strongly indicates ischemia and possible heart disease.*

- ***Number of Major Vessels Colored by Fluoroscopy***: *Indicates how many major coronary arteries are visible during imaging. More vessels with blockage (0–3 scale) means higher severity of heart disease.*

- ***Thalassemia or Heart Perfusion Defects***: *Describes the blood flow in the heart muscle.*
    *Fixed defect: Permanent lack of blood flow — scar tissue from old heart attack.*
    *Normal: No blood flow issues.*
    *Reversible defect: Blood flow is impaired during stress but normal at rest, indicates reversible ischemia, treatable with medication or surgery.*

