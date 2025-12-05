# Deliverable 3: Classification, Clustering, and Pattern Mining

## 1. Classification Results

### Performance Summary

| Model | Accuracy | F1 Score | ROC AUC |
|-------|----------|----------|----------|
| Decision Tree | 0.912 | 0.929 | 0.916 |
| k-NN | 0.956 | 0.966 | 0.979 |
| Tuned Random Forest | 0.956 | 0.966 | 0.992 |

### Key Insights
- k-NN and the tuned Random Forest performed the best.
- Hyperparameter tuning significantly improved Random Forest performance.
- Random Forest achieved the highest ROC AUC, indicating strong predictive power.


## 2. Clustering Results

### K-Means
- Formed 2 clusters closely aligned with benign and malignant classes.
- Showed clear and interpretable separation.

### DBSCAN
- Identified outliers that K-Means forced into clusters.
- Produced one main cluster and a small secondary cluster.

### Insight
- K-Means captured overall class structure.
- DBSCAN was effective for identifying unusual or borderline cases.


## 3. Association Rule Mining

### Frequent Patterns (Apriori)
- Low radius, perimeter, and area values appeared in many frequent itemsets.
- These patterns were strongly linked to malignant outcomes.

### Example Rules
- Low smoothness and low radius predict low perimeter and malignant.
- High confidence and high lift indicate strong relationships.

