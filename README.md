OVERVIEW OF THE PROJECT
Strokes are a leading cause of disability and death globally according to the W.H.O. Over 9% of victims are initially misdiagnosed which increases to 24% - 60% when symptoms are transient. Early detection saves lives and reduces long-term complications. Manual risk assessment is time-consuming and error-prone.

The objective of the project is to develop and evaluate a ML-based classification model to predict stroke risk accurately and efficiently by identifying most significant factors for stroke risk.


DATASET DETAILS
Link: https://www.kaggle.com/datasets/teamincribo/stroke-prediction?select=stroke_prediction_dataset.csv

The dataset used is the "stroke prediction dataset" (INCRIBO, Kaggle) which has 21 input features + target (EX: age, hypertension, bmi, glucose levels). The target is the 'stroke' column. The dataset consists of 15,000 records in tabular form with a mix of categorical and numerical features. It contains diverse feature types (lifestyle, clinical, demographic), real-world relevance in healthcare, data quality and simplicity and aligns with the problem statement and project requirements.

One of the main issues is the presence of missing values which we aim to tackle in the Machine Learning Pipeline, along with data cleaning, encoding, scaling, and data splitting (for training and testing).


GROUP MEMBERS
1. Handle Missing Data  -  Arif F.  -  IT24102506
2. Encode Categorical Variables  -  Perera J. M. C. S.  -  IT24103891
3. Outlier Detection & Removal  -  Kothalawala K. P.  -  IT24103969
4. Normalization/Scaling  -  Kavindi R. D. K.  -  IT24103138
5. Feature Engineering (Blood Pressure & Cholesterol)  -  Darmasena O. K. M. S.  -  IT24610813
6. Feature Engineering (Symptoms)  -  Dias A. A. L.  -  IT24103862


HOW TO RUN CODE
- On Jupyter Notebook  
- Libraries used: pandas, numpy, matplotlib, seaborn, scikit-learn 

1. Unzip the folder.
2. Navigate to `notebooks/`.
3. To view individual contribution, open the notebook that corresponds to a members IT number.
4. To see the full pipeline, open `group_pipeline.ipynb`.
5. Outputs, cleaned dataset, and EDA visualizations are saved in the `results/` folder.  

Each group member contributed to one preprocessing technique.  
The final group pipeline was built by combining individual contributions.  

