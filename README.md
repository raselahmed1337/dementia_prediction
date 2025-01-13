## A novel integrated logistic regression model enhanced with recursive feature elimination and explainable artificial intelligence for dementia prediction.

### Abstract: 
Dementia is a major global health issue that significantly impacts millions of individuals, families, and societies worldwide, creating a substantial burden on healthcare systems. This study introduces a novel approach for predicting dementia by employing the Logistic Regression (LR) model, enhanced with Recursive Feature Elimination (RFE), applied to a unique dataset comprising 1000 patients, with 49.60% male and 50.40% female. The LR model, recognized for its simplicity and effectiveness in binary classification tasks, is optimized through RFE, a technique that iteratively eliminates less significant features to improve model performance. The model’s effectiveness was assessed using comprehensive metrics, including accuracy, precision, recall, F1-score, Matthews Correlation Coefficient (MCC), and Kappa score. Furthermore, SHapley Additive exPlanations (SHAP) values were employed to increase the interpretability of the model, providing insights into the most influential features for dementia prediction. To address the issue of overfitting, a standardization technique was implemented, which enhanced the model’s predictive performance. The findings of this study hold potential implications for early dementia detection, informing intervention strategies, and optimizing healthcare resource allocation.


[Full Paper Link](https://www.sciencedirect.com/science/article/pii/S2772442524000649)

**Dataset Collection** <br>
Dataset feature descriptions <br>
Diabetes Status (Binary): Indicates whether the patient has been diagnosed with diabetes (1 for yes, 0 for no).<br>
Alcohol Consumption (Continuous):	Represents the patient’s level of alcohol intake, which may provide insight into lifestyle habits.<br>
Heart Rate (Continuous):	Number of heartbeats per minute, serving as a vital sign of cardiovascular health.<br>
Blood Oxygen Saturation (Continuous):	Percentage of oxygen saturation in the blood, critical for assessing respiratory function.<br>
Body Temperature (Continuous):	Patient’s body temperature in Celsius, useful for identifying fever or hypothermia.<br>
Body Weight (Continuous):	Patient’s weight in kilograms, a basic health metric.<br>
MRI Timing (Continuous):	The delay in receiving an MRI scan, which may indicate the severity or progression of conditions.<br>
Prescribed Medication:	Specific drugs prescribed to the patient, relevant for treatment tracking.<br>
Medication Dosage (Continuous):	The prescribed dosage of medication in milligrams, important for dosage-effect analysis.<br>
Patient Age (Continuous):	Age of the patient, a crucial demographic detail.<br>
Educational Background:	Highest educational level attained by the patient, possibly influencing health literacy.<br>
Hand Dominance:	Patient’s dominant hand, potentially related to neurological factors.<br>
Patient Gender:	Gender of the patient, a basic demographic characteristic.<br>
Family Dementia History:	Whether there is a family history of dementia, a key risk factor.<br>
Smoking Habits	Indicates: the patient’s smoking status, a significant lifestyle factor.<br>
APOE_4 Allele:	Presence of the APOE_4 allele, a genetic marker linked to Alzheimer’s disease.<br>
Exercise Frequency:	The patient’s level of physical activity, indicating lifestyle effects on health.<br>
Depression Indicator:	Reflects whether the patient has been diagnosed with depression, which may relate to cognitive health.<br>
Cognitive Assessment Scores (Continuous):	Results from cognitive assessments, providing direct measures of cognitive ability.<br>
Medication Use History:	Tracks the patient’s history of medication usage, important for evaluating drug interactions.<br>
Dietary Habits:	Describes the patient’s dietary practices, a significant health factor.<br>
Sleep Assessment:	Evaluates the quality of the patient’s sleep, a critical health aspect.<br>
Chronic Conditions:	Records any chronic illnesses the patient has, important for studying comorbidities.<br>
Dementia Status (Binary):	The target variable, showing whether dementia is present (1) or absent (0).<br>

Dataset Reference:<br>
[1] https://www.kaggle.com/datasets/kaggler2412/dementia-patient-health-and-prescriptions-dataset/data <br>
[2] Gonzalez, C. I. (2024). Dementia Classification Approach Based on Non-Singleton General Type-2 Fuzzy Reasoning. Axioms, 13(10), 672. DOI: https://doi.org/10.3390/axioms13100672<br>

[NOTE]: We are not the owner of this dataset. However, the dataset sources added in the reference section. We are uploading the dataset and code here in this repo. for further study.


