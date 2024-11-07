# Lung Cancer Prediction Project

## Project Overview
This project involves an in-depth analysis and prediction of Cancer patient's insights into patient's categorical data. The analysis leverages various visualization techniques to represent data effectively and make informed decisions.

## Table of Contents
- [Data Overview](#data-overview)
- [Analysis Points](#analysis-points)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [Future Work](#future-work)

## Data Overview
The dataset includes various columns such as:
- Age
- Gender
- Air Pollution
- Alcohol Use
- Dust Allergy
- Occupational Hazards
- Genetic Risk
- Chronic Lung Disease
- Balanced Diet
- Obesity
- Smoking
- Passive Smoker
- Chest Pain
- Coughing of Blood
- Fatigue
- Weight Loss
- Shortness of Breath
- Wheezing
- Swallowing Difficulty
- Clubbing of Finger Nails

## Analysis Points
- **Probability Level:** Calculate the likelihood of certain outcomes, such as survival rate, based on various risk factors in the dataset. This helps estimate the probability of survival or risk for different individuals and categories.
-  **Analysis of Health Risk:** Identify which factors significantly influence lung cancer mortality risk among categories.
-  **Analysis with KNN Accuracy:** Measure the accuracy of the KNN classifier in predicting survival status based on patient health data.
-  **Analysis with Decision Tree Classifier:** Identify important health features that influence survival and assess the classifier’s accuracy in predicting survival outcomes.
-  **Analysis with Random Forest Classifier:** Improve predictive accuracy and robustness by using an ensemble of Decision Trees with the Random Forest classifier.
-  **Analysis with AdaBoost Classifier:** Increase the model’s predictive power by focusing on instances that are hard to classify correctly.

## Visualizations

### Probability Level
![image](https://github.com/user-attachments/assets/d6e7145f-63de-4a7e-b97e-371e7d6285aa)
### Heatmap of Health Risks
![image](https://github.com/user-attachments/assets/a04f4f63-46bb-43e8-81d2-c0f6493893fd)
### Age Distribution by Chronic Lung Disease
![image](https://github.com/user-attachments/assets/7a3b263c-316c-4df5-87a6-5490c134471e)
### Chronic Lung Disease Prevalence by Occupational Hazards
![image](https://github.com/user-attachments/assets/733b85cf-4147-48bb-9ee1-cc3e39af96fe)
### Histograms
![image](https://github.com/user-attachments/assets/67e7b86b-5f9e-4d6b-ba3b-4f82e71045e7)
### Correlation Between The Features
![image](https://github.com/user-attachments/assets/24396def-79a3-432f-9f9e-d0bf61c8e406)
### Visualization of the Decision Tree
![image](https://github.com/user-attachments/assets/0c0a787e-b203-4a41-a393-aea7d0089eb6)
### Confusion Matrices of Testing Model
![image](https://github.com/user-attachments/assets/ecc51fbe-9822-4faf-9ee1-49d18569e4e0)

## Conclusion
This project provides valuable insights into the factors affecting cancer mortality and patient survival. By analyzing key health risk factors such as age, smoking status, air pollution, genetic risk, and other health conditions, we can better understand the complex interactions contributing to survival outcomes. Probability analysis highlights the relative risks associated with these variables, while health risk analysis identifies critical contributors to patient prognosis.

Applying machine learning models, including K-Nearest Neighbors (KNN), Decision Tree, Random Forest, and AdaBoost classifiers, demonstrates the potential for predictive analytics in healthcare. These models offer varied perspectives on survival prediction accuracy, with ensemble methods like Random Forest and AdaBoost showing strong performance by leveraging multiple weak learners to provide robust predictions. Each model brings unique strengths, from the interpretability of Decision Trees to the adaptability of AdaBoost in handling complex cases.

While these results are promising, there is potential for further enhancement through advanced methods and additional data. Integrating survival analysis, deep learning, and explainable AI techniques could significantly improve the model's accuracy and interpretability. Moreover, incorporating broader factors like socioeconomic status, environmental influences, and genetic data would provide a more holistic view of patient outcomes, making predictive tools more reliable across diverse populations.

In conclusion, this analysis underscores the importance of both traditional statistical methods and machine learning in assessing health risks and predicting survival outcomes for lung cancer patients. As healthcare increasingly adopts data-driven approaches, such models hold promise for improving early detection, personalized treatment, and ultimately, patient survival.

## Future Work
Further analysis could include:
- **Analysis with AdaBoost Classifier:** Create more sophisticated features that capture interactions between risk factors.
- **Integration of Deep Learning Models:** Leverage the ability of deep learning models to capture complex patterns and relationships in large datasets.
- **Use of Survival Analysis Techniques:** Apply survival analysis methods to model time-to-event data, providing insights not just into survival but also into the duration of survival after diagnosis.
- **Explainable AI for Model Interpretability:** Enhance the interpretability of complex models to make predictions more transparent and understandable for medical professionals.
- **Cross-Validation with External Datasets:** Validate the generalizability of the model by applying it to other datasets from different regions or demographics.
- **Implementation of Real-Time Predictive Tools:** Develop a tool that can predict survival probability or health risk in real-time based on patient inputs.
- **Assessment of Socioeconomic and Environmental Factors:** Incorporate socioeconomic and environmental variables, which often impact health outcomes and are critical for comprehensive health risk analysis.
- **Longitudinal Study for Monitoring Health Progress:** Establish a long-term study to observe changes in health risk factors and survival over time.
- **Optimization of Hyperparameters through Automated Tuning:** Improve model performance by optimizing hyperparameters in an efficient, systematic way.
- **Inclusion of Genetic and Biomarker Data:** Enhance model precision by incorporating genetic and biomarker data, which can be highly indicative of cancer progression and survival.

## Dataset Source
Kaggle: [kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link/data](https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link/data)
