# Comprehensive Survival Analysis and Prediction of Advanced Heart Failure: Leveraging AI for Accurate Prognosis and Risk Assessment
# ABSTRACT
Heart failure is a condition where the heart is unable to function effectively, leading to insufficient blood circulation. It falls under the category of cardiovascular diseases, which are disorders of the heart and blood vessels. It is a major global cause of death, with millions of deaths recorded annually. The condition is primarily caused by structural changes in the cardiac muscles, particularly in the left ventricle, resulting in weakened muscle contraction.
This study aims to conduct a comprehensive survival analysis and prediction for 299 patients classified as class III/IV heart failure with left ventricular systolic dysfunction. Survival analysis involves studying the impact of various factors on the survival of subjects over a period of time. 
The analysis identified ejection fraction, serum creatinine, time, and age as highly significant risk factors in advanced stages of heart failure. Age and increased serum creatinine levels were found to have a negative effect on survival chances. On the other hand, higher ejection fraction levels were associated with improved survival, with a unit increase resulting in a decrease in the probability of a death event by approximately 5.2%. Mortality rates were observed to be higher in the initial days post-diagnosis, gradually decreasing over time. Hypertension and anemia were also identified as high-risk factors.

Machine learning classification models were developed for survival prediction using the most significant variables from the survival analysis. Models such as random forest & Logistic Regression were implemented and showed promising performance. However, the availability of more data would enhance the stability and robustness of these models.

Smart solutions utilizing AI can play a crucial role in reducing the risk of heart failure by providing accurate prognosis, survival projections, and risk predictions. By leveraging technology and data, healthcare disparities can be addressed, care plans can be improved, and patient outcomes can be enhanced. Smart health AI solutions have the potential to revolutionize healthcare policies, enable physicians to go beyond traditional practices, and increase overall patient satisfaction levels.

#DATASET

This dataset contains the medical records of 299 patients who had heart failure, collected during their follow-up period, where each patient profile has 13 clinical features.
Attribute Information:
Thirteen (13) clinical features:

- age: age of the patient (years)
- anaemia: decrease of red blood cells or hemoglobin (boolean)
- high blood pressure: if the patient has hypertension (boolean)
- creatinine phosphokinase (CPK): level of the CPK enzyme in the blood (mcg/L)
- diabetes: if the patient has diabetes (boolean)
- ejection fraction: percentage of blood leaving the heart at each contraction (percentage)
- platelets: platelets in the blood (kiloplatelets/mL)
- sex: woman or man (binary)
- serum creatinine: level of serum creatinine in the blood (mg/dL)
- serum sodium: level of serum sodium in the blood (mEq/L)
- smoking: if the patient smokes or not (boolean)
- time: follow-up period (days)
- [target] death event: if the patient deceased during the follow-up period (boolean)
