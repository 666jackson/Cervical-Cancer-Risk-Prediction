# Cervical-Cancer-Risk-Prediction
## Cervical Cancer Risk Prediction use Machine Learning

### Introduce
Cervical cancer is a cancer that occurs in the cervix. It is caused by the growth of abnormal cells and can invade or metastasize to other parts of the body.
More than 95% of cervical cancers are caused by sexually transmitted HPV, and most people infected with the HPV virus will not develop cancer. Cervical cancer typically develops from precancerous lesions that take 10 to 20 years. Cervical cancer can be divided into several types. 90% are squamous cell carcinomas and 10% are adenocarcinomas. Diagnosis is usually through Pap smear screening followed by further biopsy. Medical imaging is used to see if cancer has metastasized.

Our purpose is to use the Dataset to provide various bad lifestyle habits, multiple cancer risk factors, different physical diseases and various test results, etc., to predict whether this person will get or have a high probability of developing cervical cancer.

#### Step1 : Data Preproessing 
1. Fill in missing values
2. Numeric type conversion
3. Delete some necessary features and fields

#### Step2 : Data Visualize
1. Count the number of features
2. Statistical chart of normal and abnormal slicing results![image](https://github.com/666jackson/Cervical-Cancer-Risk-Prediction/assets/113584996/1e08db56-047f-4091-adab-26442fed2d14)
3. Full data discrete characteristic risk factor statistical chart![image](https://github.com/666jackson/Cervical-Cancer-Risk-Prediction/assets/113584996/712b2d37-efbd-4060-b5b9-12db1ce3258a)
4. Statistical chart of slice abnormal discrete characteristic risk factor![image](https://github.com/666jackson/Cervical-Cancer-Risk-Prediction/assets/113584996/5234df88-20c5-4da4-bdb4-d653d77b93a5)
5. Statistical chart comparing the number of sexually transmitted diseases in all test subjects and the number of test subjects with abnormal slices![image](https://github.com/666jackson/Cervical-Cancer-Risk-Prediction/assets/113584996/0b062c36-01ba-4f24-be0e-62b100468151)![image](https://github.com/666jackson/Cervical-Cancer-Risk-Prediction/assets/113584996/f187df15-8b6e-4cf8-afe7-90b8c539745c)
6. 
#### Step3 : Model selection and performance evaluation
1. Naïve Bayes Model![image](https://github.com/666jackson/Cervical-Cancer-Risk-Prediction/assets/113584996/8525a134-091b-4d2d-92de-7c49bcb1a130)
2. Decision Tree Model ![image](https://github.com/666jackson/Cervical-Cancer-Risk-Prediction/assets/113584996/16fa792f-5a6a-406a-9495-5a1663695c61)
3. Random Forest Model ![image](https://github.com/666jackson/Cervical-Cancer-Risk-Prediction/assets/113584996/8098f7fa-5ef7-40e1-8b00-e6f777d78bd7)

#### Step4 : 
Confusion matrix intent![image](https://github.com/666jackson/Cervical-Cancer-Risk-Prediction/assets/113584996/f3c9c60a-dcb0-4384-9122-0f3a5c94d7cb)

#### Results and discussion
Model selection: Random Forest model is the best, with the highest Recall value of 0.9
This represents a detection rate of up to 90% among all patients diagnosed with cervical cancer.
The effect of Naïve Bayes is also good, but because only discrete features are used, the precision value is low.
The precision values ​​using these three models are not high, with the highest being only 50%.
This means that only 50% of the patients tested positive using the model are actually cancer patients, and the misdiagnosis rate is high.






