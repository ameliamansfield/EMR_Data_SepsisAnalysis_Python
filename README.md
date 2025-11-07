# EMR_Data_SepsisAnalysis_Python
EMR Data Sepsis Analysis in Python

Early Prediction of Sepsis from Clinical Data: The PhysioNet/Computing in Cardiology Challenge 2019

Sepsis remains one of the leading causes of mortality and healthcare expenditure worldwide. This Python code addresses the urgent need for early and objective detection by transforming complex electronic medical record (EMR) data into an actionable, real-time predictive score. This project is a nod to The PhysioNet/Computing in Cardiology Challenge 2019, and analyzes vitals, lab results and patient history of female ICU admits in order to find Sepsis indicators 6-hours before.

This machine learning pipeline employs an XGBoost classifier trained on a database containing 500,000+ entries of patient-level data from the eICU Collaborative Research Database. The model predicts the onset of sepsis using a set of features engineered from raw vital signs, laboratory results, and patient history, all aggregated within the critical first six hours of ICU admission.

For hospitals, deploying this model as an early warning system can reduce hospital-acquired complications, shorten length of stay, and lower treatment costs by enabling earlier initiation of the Sepsis Six protocol. This not only supports compliance with quality metrics but also enhances patient outcomes.

Beyond clinical applications, accurate early prediction of sepsis offers valuable insights for Health Economics and Outcomes Research (HEOR). It enables pharmaceutical and healthcare organizations to better quantify the real-world value of interventions that prevent or mitigate sepsis progression.
