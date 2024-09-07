Cardiovascular diseases also known as heart diseases refer to any disorder that accounts for the malfunction of the heart and its blood vessels. According to the World Health Organization (WHO), about 17.9 million lives are lost annually to cardiovascular diseases which represents about 32 % of all global deaths. Common causes for these deaths are late diagnosis and detection of the diseases. This web app focused on a particular kind of cardiovascular disease which is congestive heart failure. This machine learning web model used a dataset of 299 heart failure patients (access dataset [here]([url](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5)  
The dataet used contained the medical records of 299 heart failure patients collected at the Faisalabad Institute of Cardiology and at the Allied Hospital in Faisalabad (Punjab, Pakistan), during April–December 2015 . The patients consisted of 105 women and 194 men, and their ages range between 40 and 95 years old . All 299 patients had left ventricular systolic dysfunction and had previous heart failures that put them in classes III or IV of New York Heart Association (NYHA) classification of the stages of heart failure 
This dataset contains 12 features that can be used to predict mortality by heart failure.

The 12 features are 
Age (years): This variable shows the patient’s age
Anemia (Boolean): is the decrease in red blood cells or hemoglobin
Creatinine_phosphokinase (mcg/L): is the level of creatinine phosphokinase in the blood.
Diabetes (Boolean): is a chronic disease that causes high blood sugar
Ejection fraction (%): is the percentage of blood leaving the heart at each contraction
High blood pressure (Boolean): is blood pressure that is relatively higher than normal blood pressure
Platelets (kiloplatelets/ml): are tiny blood cells that help your body stop bleeding by forming blood clots
Serum creatinine (mg/dL): is the amount of serum creatinine in the blood
Serum sodium (mEq/L): is the amount of serum sodium in the blood
Smoking (Boolean): To determine if the patient smokes or not
Sex (Binary): gender of the patient
Time (Days): This captures the follow up period
Death event (Boolean): which is the predictor or target variable.

After data cleaning, visualization and exploratory analysis to prepare the dataset, 4 key features were selected and they are Age, Serum Creatinine, Ejection Fraction and Serum Sodium, were selected for model development. 3 classification machine learning algorithms: Logistic Regression, Support Vector Machine and Random Forest Classifier were trained with the dataset and Random Forest was selected due to its better evaluation performance in comparison to the rest with an accuracy of about 78%.

The Heart Detect web app is therefore a machine learning web application model that uses Random Forest classification algorithm to predict the likelihood of survival for heart failure patients using data from age, serum creatinine levels, ejection fraction and serum sodium levels.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                
