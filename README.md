# -Support-Vector-Machines--Task-7

This project uses **Support Vector Machines (SVM)** for **binary classification** on a Breast Cancer dataset.

## Steps Performed
1. **Loaded and cleaned the dataset** (`breast-cancer.csv`), removed ID columns, handled missing values.
2. **Detected and encoded the target** into binary values (0 = Benign, 1 = Malignant).
3. **Standardized features** and split data into train/test sets.
4. **Trained and evaluated SVM models**:
   - LinearSVC (fast linear SVM)
   - SVC with Linear kernel
   - SVC with RBF kernel
5. **Hyperparameter tuning** for RBF SVM using `GridSearchCV` on `C` and `gamma`.
6. **Evaluated performance** with classification report and confusion matrix.
7. **Reduced data to 2D with PCA** and plotted the RBF decision boundary.

## Tools & Libraries
- Python 3.x
- Pandas, NumPy, Matplotlib
- scikit-learn (SVM, PCA, GridSearchCV)

## Output
- Model performance metrics (accuracy, precision, recall, F1-score)
- Confusion matrix plot
- 2D decision boundary visualization (PCA reduced space)
