# Interpretable machine learning predicts cardiac resynchronization therapy responses from personalized biochemical and biomechanical features
This is the Repository for ML Prediction of Cardiac Resynchronization Therapy Outcome from the SMART-AV clinical trial. The paper can be found at https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-022-02015-0
### Background
Cardiac Resynchronization Therapy (CRT) is a widely used, device-based therapy for patients with left ventricle (LV) failure. Unfortunately, many patients do not benefit from CRT, so there is potential value in identifying this group of non-responders before CRT implementation. Past studies suggest that predicting CRT response will require diverse variables, including demographic, biomarker, and LV function data. Accordingly, the objective of this study was to integrate diverse variable types into a machine learning algorithm for predicting individual patient responses to CRT.

### Methods
We built an ensemble classification algorithm using previously acquired data from the SMART-AV CRT clinical trial (n = 794 patients). We used five-fold stratified cross-validation on 80% of the patients (n = 635) to train the model with variables collected at 0 months (before initiating CRT), and the remaining 20% of the patients (n = 159) were used as a hold-out test set for model validation. To improve model interpretability, we quantified feature importance values using SHapley Additive exPlanations (SHAP) analysis and used Local Interpretable Model-agnostic Explanations (LIME) to explain patient-specific predictions.

### Results
Our classification algorithm incorporated 26 patient demographic and medical history variables, 12 biomarker variables, and 18 LV functional variables, which yielded correct prediction of CRT response in 71% of patients. Additional patient stratification to identify the subgroups with the highest or lowest likelihood of response showed 96% accuracy with 22 correct predictions out of 23 patients in the highest and lowest responder groups.

### Conclusion
Computationally integrating general patient characteristics, comorbidities, therapy history, circulating biomarkers, and LV function data available before CRT intervention can improve the prediction of individual patient responses.

### Data Availability
Data can be available upon request from Professor ***Frank G. Spinale cvctrc@uscmed.sc.edu***
