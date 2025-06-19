📊 Workflow Overview

1.⁠ ⁠Load Data: Use the digits dataset from sklearn.datasets


2.⁠ ⁠Preprocess: Standardize features


3.⁠ ⁠Dimensionality Reduction: Apply PCA to retain 40 principal components


4.⁠ ⁠Train Model: Train SVM with RBF kernel


5.⁠ ⁠Evaluate: Use accuracy, classification report, and confusion matrix


6.⁠ ⁠Tune Model: Use GridSearchCV for best hyperparameters


7.⁠ ⁠Save: Save model, scaler, and PCA transformer using joblib




---

✅ Sample Output

Dataset shape: (1797, 64), Labels: [0 1 2 3 4 5 6 7 8 9]
Original shape: (1437, 64), After PCA: (1437, 40)
Accuracy: 0.9833
Tuned Model Accuracy: 0.9889
Predicted label: 3
Actual label: 3


---

📌 Highlights

Scikit-learn SVM with PCA for efficient training

GridSearchCV for robust tuning

Full model pipeline saved for production use

Visualization of PCA component clustering



---

📥 Dataset

This project uses the built-in digits dataset from sklearn.datasets. No external downloads are needed.

---
