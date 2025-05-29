# Skin Disorder Prediction

## Overview

This project focuses on predicting various types of skin disorders using structured clinical and histopathological data. By applying machine learning techniques, we aim to identify patterns in skin disorder symptoms and accurately classify the type of disorder to assist in early diagnosis and treatment planning.

## Objective

To develop a predictive model that classifies six types of skin disorders by analyzing 34 attributes and identifying influential clinical and histopathological factors that contribute to the disorder type.

## Healthcare Context

Potential causes of skin disorders include:

* Inflammatory Responses
* Keratinization and Epidermal Abnormalities
* Immune-Mediated and Autoimmune Factors

This project belongs to the **Healthcare** domain and emphasizes early detection through data-driven approaches.

## Dataset Details

The dataset includes:

* 12 Clinical Attributes (e.g., Erythema, Scaling, Itching, Family History)
* 21 Histopathological Attributes (e.g., Hyperkeratosis, Parakeratosis, Munro Microabscess)
* 1 Linear Attribute (Age)
* Target Class: Six skin disorder classes (1: Psoriasis, 2: Seborrheic Dermatitis, 3: Lichen Planus, 4: Pityriasis Rosea, 5: Chronic Dermatitis, 6: Pityriasis Rubra Pilaris)

## Exploratory Data Analysis (EDA) Insights

### Symptom Severity

* 25 out of 32 symptoms have a majority of severity level 0.

### Family History

* Most individuals do not have a family history of these skin conditions.

### Class Distribution

* Class 1 (Psoriasis) has the most cases.
* Class 6 (Pityriasis Rubra Pilaris) has the fewest.

### Key Symptom Combinations

**Psoriasis:** Munro Microabscess + Hyperkeratosis + Parakeratosis (9 confirmed cases)

**Lichen Planus:** Polygonal Papules + Saw-Tooth Appearance + Band-like Infiltrate (63 confirmed cases)

**Chronic Dermatitis:** Itching + Fibrosis + Inflammatory Mononuclear Infiltrate (22 confirmed cases out of 24 with these symptoms)

**Pityriasis Rubra Pilaris:** Follicular Papules + Perifollicular Parakeratosis + Hyperkeratosis (2 confirmed cases)

## Machine Learning Approach

* Data Preprocessing: Handling missing values, scaling, encoding.
* Models Used: Logistic Regression, Decision Tree, Random Forest, KNN, SVM, XGBoost.
* Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix.

## Results

* **Random Forest Classifier** achieved the highest accuracy of **97.8%**, minimizing misclassifications.
* It successfully captured key patterns across all disorder classes.

## Conclusion

This project demonstrates how structured medical data combined with machine learning can significantly enhance the diagnostic process for skin disorders. The Random Forest model, in particular, proved to be robust and effective, making it a strong candidate for real-world deployment in clinical settings.

---

