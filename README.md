# Hospital-Readmission
**Problem Statement**
To identify the factors that lead to the high readmission rate of diabetic patients within 30 days post discharge and correspondingly to predict the high-risk diabetic-patients who are most likely to get readmitted within 30 days so that the quality of care can be improved along with improved patient’s experience, health of the population and reduce costs by lowering readmission rates. Also, to identify the medicines that are the most effective in treating diabetes.

**Dataset**
The data subset used for analysis covers 10 years of diabetes patient encounter data (1999 – 2008) among 130 US hospitals with over 100,000 diabetes patients. Moreover, all the encounters used for analysis satisfy five key criteria:
• The length of stay was comprised from 1 to 14 days.
• The inpatient underwent laboratory testing.
• The inpatient received medication during its stay.

**Final Model**
As we can see from the above results, LGBM and XGBoost are giving
better results after hyperparameter tuning. But the training and prediction time of XGBoost is far
more than that of LGBM. So XGBoost is not scalable and not suitable for production because it
will increase costs and time while giving similar results as LGBM which takes only 2-3 seconds
to train on this large dataset thus saving costs and time while giving the best results.

**Findings**
If the patient has the following characteristics, he has a high probability of being readmitted:
• High preceding year visits.
• If the patient is discharged to another medical facility or discharged to home with health
  services.
• High number of diagnoses.
• If the patient is given diabetes medicines.
• If the primary diagnosed disease was of circulatory system.
• If Metformin and/or insulin is not being given or the dosage is low.
• If secondary diagnosis was coming to be Diabetes.
• If A1C test was not performed.
