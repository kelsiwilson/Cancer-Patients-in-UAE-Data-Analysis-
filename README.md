# Cancer-Patients-in-UAE-Data-Analysis-
## Dataset Description
The dataset contains cancer patient records from healthcare institutions in the United Arab Emirates.

Age, Gender, Nationality, Emirate, Ethnicity

Cancer Type, Cancer Stage, Treatment Type, Outcome, Comorbidities

Smoking Status, Weight, Height (BMI calculated)

Diagnostic Date, Treatment Start Date

## Tools & Libraries Used

Python 3.X

Pandas, NumPy – Data loading, cleaning

Matplotlib, Seaborn – Visualizations

Scikit-learn – Predictive modeling and clustering

Jupyter Notebook – Code implementation and documentation

## Data Preprocessing
Handled missing data with appropriate  imputation.

Checking duplicate, checking info, checking null value

## Exploratory Data Analysis (EDA)
 Analyze recovery rates over the years and by cancer type

 Compared recovery rates across various cancer types.

 Assessed how smoking status impacted recovery.

 Identified the top 5 frequent cancers and their outcomes.



## Predictive Modeling

Objective: Predict Cancer Stage (I–IV)

Age, Gender, Nationality, Ethnicity, Smoking Status, Comorbidities, Cancer Type, BMI

The model used was a Random Forest Classifier

Evaluation: Confusion Matrix and Classification Report showed meaningful predictive power.

## Clustering Analysis

Group patients based on similar traits (excluding Cancer Stage & Outcome).

The method used was K-Means clustering with 3 clusters.

 Helped uncover high-risk or treatment-resistant profiles
