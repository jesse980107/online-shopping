## Online Shopping Intention Analysis

### Project Overview

This project aims to analyze online shopping intentions using a classification model. The model's performance is evaluated using a normalized confusion matrix.

### Confusion Matrix

The normalized confusion matrix visualizes the performance of the classification model. Below is the normalized confusion matrix:

![Normalized Confusion Matrix](image.png)

### Interpretation

- **True Label 0 (Non-buyers):**
  - **Predicted 0:** 94% of non-buyers were correctly predicted.
  - **Predicted 1:** 6% of non-buyers were incorrectly predicted as buyers.

- **True Label 1 (Buyers):**
  - **Predicted 0:** 85% of buyers were incorrectly predicted as non-buyers.
  - **Predicted 1:** 15% of buyers were correctly predicted.

### Conclusion

The model performs well in identifying non-buyers but has a high misclassification rate for buyers. Future improvements should focus on enhancing the model's ability to correctly predict buyers.

### Project Structure

- **data/**: Contains the dataset used for analysis.
- **notebooks/**: Jupyter notebooks for data exploration, preprocessing, and model training.
- **models/**: Saved models and configurations.
- **reports/**: Generated analysis and evaluation reports.
- **scripts/**: Python scripts for data processing and model evaluation.
