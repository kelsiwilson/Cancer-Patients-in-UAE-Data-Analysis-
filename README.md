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

## Data Preparation and Analysis Workflow

Load the Dataset: Imported the dataset into the Jupyter Notebook environment for analysis.

Inspected the dataset structure, including column names, data types, and dimensions (rows and columns).

Data Cleaning:

Checked for missing values using appropriate imputation techniques.

Identified and removed any duplicate entries.

Reviewed data types and summary statistics using .info() and .describe() functions.

Exploratory Data Analysis (EDA):

Analyzed recovery rates over different years and across various cancer types.

Investigated the impact of smoking status and comorbidities on patient outcomes.

Identified the top 5 most common cancer types and evaluated their recovery rates.

Visualization:

Used bar plots, count plots, and heatmaps to present key patterns and findings.

Predictive Modeling:

Built a classification model to predict cancer stages using demographic, lifestyle, and medical features.


 ## Insight
1) Smoking is associated with lower recovery and higher mortality.

2) Breast and lung cancers are the most common types.

3) Stage prediction performed well with basic demographic and health data.

4) Clustering revealed distinct patient subgroups for targeted care.

5) Leukemia and breast cancer had higher recovery rates.

6) Over 490 non-smokers and 305 smokers died due to under-treatment.

7) Recovery peaked in 2020 and dropped in 2024.

 ## Recommendation
   
. Patients with comorbidities and a history of smoking should be given priority
for regular cancer screenings and early diagnosis to improve outcomes.
· Introduce campaigns focused on smoking cessation and chronic disease management 
(e.g., diabetes, hypertension) to reduce cancer risks and support patient recovery.
· Hospitals should adopt predictive machine learning models
to assist oncologists in determining cancer stages, enabling more accurate and timely treatment decisions.
· Further analyze treatment-resistant and late-stage 
patient groups to develop customized treatment plans and ensure efficient resource allocation


