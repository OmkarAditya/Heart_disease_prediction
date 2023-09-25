# Heart_disease_prediction using machine learning

A model based on **Classification Problem**.

## 'Heart_disease' directory contains
  * **Jupyter notebook** of all my data analysis, feature comparision, visualization, fitting the data into model, predicting the model, evaluating the model and improving the model using hyperparameter tuning
  * **Heart_disease.csv** contains the data in csv file format
  * **final_model.joblib** is the final model we got as conclusion

The original data came from the Cleavland data from the UCI Machine Learnign Repository https://archive.ics.uci.edu/dataset/45/heart+disease

This notebook looks into using various python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on medical attribute

1. Problem defination
2. Data
3. Evaluation
4. Modelling
5. Experimentation

## 1. Problem Defination

**statement**
> Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## 2. Data

The original data came from the Cleavland data from the UCI Machine Learnign Repository https://archive.ics.uci.edu/dataset/45/heart+disease

Kaggle 
https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset

## 3. Evaluation

> If we can reach 90% accuracy at predicting whether or not a patient has heart disease during thr proof of concept, we will pursue the project

## Some outcomes (others inside the jupyter notebook)

### Data analysis and visualization

### Various model comarision

### Evaluation metrics

### feature importance


## 4. Features

**Data dictionary (for reference)**

1. **age** (age in years)
2. **sex** (1 = male; 0 = female)
3. **chest pain type** (4 values)
    *  0: Typical angina: chest pain related to decrease supply in blood
    *  1: Atypical angina: chest pain not related to heart
    *  2: Non-anginal pain: typically esophageal spasms (non heart related) 
    *  3: Asymptomatic: chest pain not showing sign of disease
4. **trestbps** - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
5. **chol** - serum cholestoral in mg/dl
    * serum = LDL + HDL + .2 * triglycerides
    * above 200 is cause for concern
6. **fasting blood sugar** > 120 mg/dl (1 = true; 0 = false)
7. **resting electrocardiographic results** (values 0,1,2)
    * 0: Nothing to note
    * 1: ST-T Wave abnormality
        * can range from mild symptoms to severe problems
        * signals non-normal heart beat
    * 2: Possible or definite left ventricular hypertrophy
        * Enlarged heart's main pumping chamber
8.  **thalach** - maximum heart rate achieved
9.  **exang** - exercise induced angina (1 = yes; 0 = no)
10. **oldpeak** - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
11. **slope** - the slope of the peak exercise ST segment
    * 0: Upsloping: better heart rate with excercise (uncommon)
    * 1: Flatsloping: minimal change (typical healthy heart)
    * 2: Downslopins: signs of unhealthy heartthe slope of the peak exercise ST segment
12. **ca** - number of major vessels (0-3) colored by flourosopy
    * colored vessel means the doctor can see the blood passing through
    * the more blood movement the better (no clots)
13. **thal**: 0 = normal; 1 = fixed defect; 2 = reversable defect
14. **target** - have disease or not (1=yes, 0=no) (= the predicted attribute)
   
