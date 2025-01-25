# Fetal Health Classification using CTG Data

This project aims to classify fetal health based on Cardiotocography (CTG) data into three categories: **Normal**, **Suspect**, and **Pathological**. The CTG data provides crucial information about fetal heart rate, movements, and uterine contractions, enabling healthcare professionals to assess the health status of the fetus.

---

## Project Overview

### Steps:
1. **Data Collecting**
2. **Data Analysis**
3. **Data Validation**
4. **Object Definition**
5. **Data Cleaning**
6. **Feature Engineering**
7. **Label Definition**
8. **Model Building and Evaluation**
9. **Model Comparison**

---

## Dataset Details

### Features:
1. `baseline value`: Baseline fetal heart rate (beats per minute).
2. `accelerations`: Number of accelerations per second.
3. `fetal_movement`: Number of fetal movements per second.
4. `uterine_contractions`: Number of uterine contractions per second.
5. `light_decelerations`: Number of light decelerations per second.
6. `severe_decelerations`: Number of severe decelerations per second.
7. `prolongued_decelerations`: Number of prolonged decelerations per second.
8. `abnormal_short_term_variability`: Percentage of time with abnormal short-term variability.
9. `mean_value_of_short_term_variability`: Mean short-term variability.
10. `percentage_of_time_with_abnormal_long_term_variability`: Percentage of time with abnormal long-term variability.
11. `mean_value_of_long_term_variability`: Mean long-term variability.
12. `histogram_width`: Width of the fetal heart rate histogram.
13. `histogram_min`: Minimum value in the histogram.
14. `histogram_max`: Maximum value in the histogram.
15. `histogram_number_of_peaks`: Number of peaks in the histogram.
16. `histogram_number_of_zeroes`: Number of zeroes in the histogram.
17. `histogram_mode`: Mode of the histogram.
18. `histogram_mean`: Mean of the histogram.
19. `histogram_median`: Median of the histogram.
20. `histogram_variance`: Variance of the histogram.
21. `histogram_tendency`: Tendency of the histogram.

### Target:
`fetal_health`: 
- **1**: Normal
- **2**: Suspect
- **3**: Pathological

---

## Models Used

1. Naive Bayes
2. Random Forest Classifier
3. Support Vector Machine (SVM)
4. Logistic Regression
5. Decision Tree

---

## Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

---

## Results and Comparison

| Model                 | Accuracy | Precision | Recall | F1-Score |
|-----------------------|----------|-----------|--------|----------|
| Naive Bayes           | 73%      | 86%       | 73%    | 76%      |
| Random Forest         | 91%      | 91%       | 91%    | 91%      |
| SVM                   | 82%      | 87%       | 82%    | 83%      |
| Logistic Regression   | 76%      | 83%       | 76%    | 78%      |
| Decision Tree         | 89%      | 89%       | 89%    | 89%      |

Best Model: **Random Forest** with 91% accuracy.

---

## Tools and Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Numpy
- Imbalanced-learn
- Scikit-learn
- Collections

---

## Conclusion

The project successfully classified fetal health using CTG data with high accuracy. The **Random Forest** model performed the best, achieving an accuracy of 91%.

---
