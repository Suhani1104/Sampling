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
- Evaluated model performance using **Accuracy**
- Compared results using a Model × Sampling matrix

---

## Results
- Accuracy results are organized in a tabular format
- Rows represent machine learning models (M1–M5)
- Columns represent sampling techniques (Sampling1–Sampling5)

📄 **Result File:**  
- `sampling_accuracy_results.csv`

---

## Observations
- Stratified Sampling generally produced more stable and consistent accuracy
- Random Forest achieved the highest accuracy across most sampling techniques
- Cluster and Systematic Sampling showed comparatively lower performance
- Sampling strategy significantly impacts model performance

---

## Visualizations (Optional)
- Accuracy comparison table (screenshot or CSV view)
- Bar chart or heatmap showing accuracy across models and sampling techniques

Suggested folder:
