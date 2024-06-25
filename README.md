# supervised_ml_urinary_biomarkers_classification
Supervised Machine Learning Final Project - Urinary Biomarkers for Pancreatic Cancer Classification

Introduction:

Urinary biomarkers are highly effective predictors for early-stage pancreatic cancer, a feature that is extremely important for a high-mortality disease. This project aims to employ supervised machine learning algorithms Logistic Regression, Random Forest Classifier, and Support Vector Machine (SVM) to perform multiclass classification of pancreatic cancer stages using biomarker data from the Debernardi et al. 2020 study (although data was found via Kaggle). The goal is to accurately predict whether a patient has a control, benign, or PDAC (pancreatic ductal adenocarcinoma) diagnosis. By developing reliable models for early detection and classification of pancreatic cancer stages based on non-invasive biomarkers, the project aims to contribute to improved patient outcomes for this dangerous and increasingly common form of cancer. 

Data source: 
Debernardi, S., et al. (2020). "A diagnostic biomarker panel for the early detection of pancreatic cancer using both plasma and urinary samples." PLOS Medicine. [(https://www.kaggle.com/datasets/johnjdavisiv/urinary-biomarkers-for-pancreatic-cancer/data)]

Structure:
1. Data preprocessing
2. Exploratory Data Analysis (EDA)
3. Model Training and Evaluation, including Random Forest Classifier, Support Vector Machines (SVM), and Logistic Regression
4. Analysis and Dicussion of Conclusions

Conclusion:

The analysis of pancreatic cancer classification models revealed the Random Forest classifier as the top performer beating both Logistic Regression and Support Vector Machine (SVM) approaches. With an accuracy of 0.69 and an F1 score of 0.70, Random Forest demonstrated superior and consistent performance across various evaluation metrics. Its robustness was further confirmed through cross-validation, showing stable results across different data splits. In contrast, while Logistic Regression achieved moderate and basic results, it exhibited higher variance, suggesting sensitivity to data partitioning. The SVM model very notably underperformed, indicating its ineffectiveness for this particular dataset without significant (and impractical) adjustments. The Random Forest model's effectiveness was particularly evident in its ability to identify Pancreatic Ductal Adenocarcinoma (PDAC), as shown by high true positive rates in the confusion matrix and ROC curve results. The area under the curve (AUC) values, especially the 0.97 for PDAC, underscored the model's strong discriminative power. Feature importance analysis highlighted 'REG1A', 'LYVE1', and 'TFF1' as key contributors to the model's decision-making process, providing valuable insights for future research directions. Overall, the Random Forest classifier emerges as the recommended best and primary model for this cancer dataset. Its ideal performance and robustness make it a strong candidate for deployment in clinical or research/academic settings where accurate classification of the cancer stages is crucial. While Logistic Regression could potentially benefit from further tuning, the SVM approach may require significant modifications to be effective. Future work could explore more advanced techniques or incorporate additional data, as well as investigate more intricate/sophistcated models to further enhance performance in cancer classification.
