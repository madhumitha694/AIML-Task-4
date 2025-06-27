# AIML-Task-4
🤖 Task 4: Logistic Regression – AI & ML Internship

 📌 Objective
To build a **binary classification model** using **Logistic Regression** on the **Breast Cancer Wisconsin dataset**.  
We aim to evaluate the model using common metrics like **confusion matrix, precision, recall, and ROC-AUC**.

🧾 Dataset
- Dataset Name: Breast Cancer Wisconsin (Diagnostic)
- Format: CSV
- Target Column: `diagnosis` (Malignant = 1, Benign = 0)

🔧 Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn & Matplotlib

## 🔍 Steps Followed
1. **Loaded** dataset from local `.csv` file
2. **Cleaned** data: removed empty columns like `Unnamed: 32`
3. **Encoded** diagnosis column: `M → 1`, `B → 0`
4. **Dropped** unnecessary columns: `id`
5. **Split** data into training and testing sets
6. **Standardized** features using `StandardScaler`
7. **Trained** a Logistic Regression model
8. **Evaluated** performance with:
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)
   - ROC Curve and AUC Score

📊 Results
- **Accuracy**: ~96–98%
- **AUC Score**: ~0.98–0.99
- **Very high** sensitivity and specificity

## 📈 Visual Outputs
- 📌 Confusion Matrix heatmap
- 📌 ROC Curve with AUC

Output :
  [Classification with Logistic Regression output (1).pdf](https://github.com/user-attachments/files/20945165/Classification.with.Logistic.Regression.output.1.pdf)
