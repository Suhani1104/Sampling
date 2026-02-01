# Sampling Techniques Analysis - Credit Card Fraud Detection

## Objective
- To understand the importance of sampling techniques in handling highly imbalanced datasets
- To analyze how different sampling strategies affect the accuracy of machine learning models

---

## Dataset
- Credit Card Fraud Detection Dataset
- Target column: `Class`
  - `0` → Legitimate transaction
  - `1` → Fraudulent transaction
- The dataset is highly imbalanced

---

## Sampling Techniques Used
- **Sampling1** – Simple Random Sampling  
- **Sampling2** – Stratified Sampling  
- **Sampling3** – Systematic Sampling  
- **Sampling4** – Cluster Sampling  
- **Sampling5** – Cross Validation Sampling  

---

## Machine Learning Models Used
- **M1** – Logistic Regression  
- **M2** – Decision Tree  
- **M3** – Random Forest  
- **M4** – Support Vector Machine (SVM)  
- **M5** – Naive Bayes  

---

## Methodology
- Balanced the dataset by selecting equal numbers of fraud and non-fraud transactions
- Created five different samples using statistical sampling techniques
- Applied five machine learning models on each sampled dataset
- Evaluated and compared model performance using **Accuracy**

---

## Results
<img width="849" height="416" alt="image" src="https://github.com/user-attachments/assets/64867e7a-5f0a-43e8-babc-9d956ca26901" />

---

## Observations
- The highest accuracy (0.83) is achieved by **Decision Tree (M2)** using **Stratified Sampling (Sampling2)**.
- **Random Forest (M3)** performs consistently across most sampling techniques but does not achieve the highest accuracy.
- **Cluster Sampling (Sampling4)** yields the lowest overall performance, showing a constant accuracy of 0.33 across all models.
- The results clearly indicate that **sampling strategy significantly impacts model performance**, and no single sampling technique is optimal for all models.
- ### Best Sampling Technique for Each Model
|  Machine Learning Model  |   Best Sampling Technique    | Accuracy |
|--------------------------|------------------------------|----------|
| M1 – Logistic Regression | Sampling5 (Cross Validation) |   0.50   |
|    M2 – Decision Tree    |    Sampling2 (Stratified)    |   0.83   |
|    M3 – Random Forest    |  Sampling1 (Simple Random)   |   0.67   |
|         M4 – SVM         |    Sampling1 / Sampling5     |   0.50   |
|     M5 – Naive Bayes     |    Sampling2 (Stratified)    |   0.67   |


**Heatmap**
<img width="1327" height="641" alt="image" src="https://github.com/user-attachments/assets/0eb9c927-623b-443e-8dac-96fe0628e53a" />

