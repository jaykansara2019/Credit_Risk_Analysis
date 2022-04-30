# **Credit_Risk_Analysis**

## **Purpose**
The project aims to analyse the credit risk utilising the Supervised machine learning techniques. The following sampling techniques were used to develop the Supervised Machine Learning model.

***Oversampling***
- Naive Random Oversampling
- SMOTE Oversampling

***Undersampling***
- Cluster Centroid Undersampling

***Combination of Over and Under Sampling***
- SMOTEENN Sampling

In addition, the following classification methods were used to analyse credit risk.
- Balanced Random Forest Classifying
- Easy Ensemble Classifying

Confusion matrices were used to derive accuracy, precision and sensitivity scores.

## **Results**
For all six models, the results of the credit risk data are as below:

### **Naive Random Oversampling**
- Accuracy Score: 65.5%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 62%
- Recall Low Risk: 67%

### **SMOTE Oversampling**
- Accuracy Score: 63.8%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 67%
- Recall Low Risk: 61%

### **Cluster Centroid Undersampling**
- Accuracy Score: 50%
- Precision High Risk: 1%
- Precision Low Risk: 99%
- Recall High Risk: 53%
- Recall Low Risk: 47%

### **SMOTEENN Sampling**
- Accuracy Score: 62.3%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 69%
- Recall Low Risk: 56%

### **Balanced Random Forest Classifying**
- Accuracy Score: 67.8%
- Precision High Risk: 92%
- Precision Low Risk: 100%
- Recall High Risk: 36%
- Recall Low Risk: 100%


## **Easy Ensemble Classifying**
- Accuracy Score: 93%
- Precision High Risk: 9%
- Precision Low Risk: 100%
- Recall High Risk: 92%
- Recall Low Risk: 94%


## **Summary**

The ideal results we would expect from the model is to detect high-risk cases with high sensitivity. If we look at the recall/sensitivity score, the "Easy Ensemble Classifier' stands highest at 92%. The same is true for the overall accuracy score, which stands at 93%. To conclude, if we compare the results of all six methods, the Easy Ensemble Classifying seems the favourable choice.


