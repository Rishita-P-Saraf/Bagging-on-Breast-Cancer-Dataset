# Bagging on Breast Cancer Dataset

This project demonstrates the use of ensemble learning through **Bagging** with a **K-Nearest Neighbors (KNN)** classifier on the Breast Cancer dataset from scikit-learn. It compares the performance of a simple KNN model with a BaggingClassifier using KNN as the base estimator.

## 🧪 Dataset

The dataset used is the **Breast Cancer Wisconsin Diagnostic Dataset**, which comes preloaded with `sklearn.datasets`. It contains 569 samples of malignant and benign tumor cases with 30 numeric features each.

## 📦 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## 🔍 Model Workflow

1. Load the breast cancer dataset.
2. Split the dataset into training and testing sets.
3. Train a KNN classifier.
4. Evaluate its accuracy.
5. Create a BaggingClassifier using KNN as the base model.
6. Fit and evaluate the bagging model.

## 📊 Results

- **KNN Classifier Accuracy**: Varies per split but typically lower than the bagging model.
- **Bagging KNN Classifier Accuracy**: Achieved up to **93.7%** accuracy on test data.

## 🧠 Why Bagging?

Bagging helps to reduce variance and avoid overfitting by combining the results of multiple models trained on different subsets of the data. This generally results in better generalization performance.

## 📁 File Structure
```
bagging-on-breast-cancer/
├── bagging on breast cancer dataset.txt # Python script for model building and evaluation
├── README.md # Project documentation
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bagging-on-breast-cancer.git
   cd bagging-on-breast-cancer
   ```
   
2. Install required packages:
   ```
   pip install -r requirements.txt
   ```
3. Run the Python script:
   ```
   python "bagging on breast cancer dataset.txt"
   ```

## 📌 TODO
- Add cross-validation for better performance estimation.
- Plot confusion matrices and ROC curves.
- Compare with other ensemble methods (e.g., Random Forest, AdaBoost).

## 📬 Contact
For any queries or contributions, please feel free to open an issue or contact rishitasarafp@gmail.com.
