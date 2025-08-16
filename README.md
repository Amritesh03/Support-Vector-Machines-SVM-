# Task 7 - Support Vector Machines (SVM)

## Objective
Implement Support Vector Machines (SVM) for binary classification using both linear and non-linear kernels.

## Steps Followed
1. **Dataset**: Used the Breast Cancer dataset (Kaggle/Sklearn).
2. **Preprocessing**: Cleaned data, handled missing values, and scaled features.
3. **Model Training**:
   - Trained SVM with Linear Kernel.
   - Trained SVM with RBF Kernel.
4. **Hyperparameter Tuning**:
   - Tuned `C` and `gamma` using GridSearchCV.
5. **Evaluation**:
   - Used cross-validation accuracy.
   - Compared performance of linear vs. RBF kernel.
6. **Visualization**:
   - Plotted decision boundaries for 2D data.
   - Showed margins and support vectors.

## Results
- Linear Kernel: Accuracy ~XX%
- RBF Kernel: Accuracy ~YY%
- RBF kernel performed better due to non-linear separation ability.

## Tools Used
- Python (Scikit-learn, NumPy, Matplotlib, Seaborn)
