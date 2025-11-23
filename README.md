# 🩺 Diabetes Prediction using Support Vector Machine (SVM)

A supervised machine learning project aimed at **early and reliable detection of diabetes** in patients using a classification model trained on key diagnostic health indicators.

The core objective was to develop a machine learning model that accurately predicts the onset of diabetes using key diagnostic health indicators from patient data.

---

## 🎯 Key Features and Performance

| Metric | Detail | Source |
| :--- | :--- | :--- |
| **Model** | Support Vector Machine (SVM) Classifier | Linear Kernel |
| **Dataset** | PIMA Indians Diabetes Dataset (768 patient records, 8 features) |
| **Test Accuracy** | **77.27%** (approx. 77.3%) |
| **Generalization** | Training Accuracy (78.66%) and Test Accuracy are very close (1.39% difference), indicating **minimal overfitting** and good reliability on unseen data. |

---

## ⚙️ Methodology Pipeline

The project follows a rigorous machine learning pipeline, all detailed in the included Colab notebook:

1.  **Data Analysis:** Loaded the PIMA dataset, separating the 8 diagnostic features (Glucose, BMI, Age, etc.) from the binary outcome variable.
2.  **Data Standardization:** Crucial for SVM, all features were standardized using the **`StandardScaler`** (mean of 0, standard deviation of 1) to ensure equal contribution from all inputs.
3.  **Train-Test Split:** Data was divided into **80% training** and **20% testing**. This utilized **stratified splitting** to preserve the original class ratio, preventing sampling bias.
4.  **Model Training:** A **Support Vector Machine with a Linear Kernel** was trained to find the optimal hyperplane that maximizes the margin between the two classes.

---

## 📂 Repository Contents

| File | Description |
| :--- | :--- |
| **`Diabetes_Prediction_Model.ipynb`** | The complete Python source code executed in a Google Colaboratory notebook, containing the entire ML pipeline from data loading to prediction. |
| **`diabetes_dataset.csv`** | The raw PIMA Indians Diabetes Dataset used for training and testing. |
| **`Diabetes Prediction Model report.pdf`** | The detailed project report, which formally documents the methodology, evaluation, and conclusion. |

---

## ▶️ Getting Started

To view and run the code:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/MinahilAhmedAli/Diabetes-Prediction-Model-Machine-Learning-SVM-Classifier.git](https://github.com/MinahilAhmedAli/Diabetes-Prediction-Model-Machine-Learning-SVM-Classifier.git)
    ```
2.  **Open the Notebook:** Open the `Diabetes_Prediction_Model.ipynb` file in **Google Colaboratory** or a local Jupyter Notebook environment.
3.  **Run Cells:** Execute the notebook cells sequentially to reproduce the data analysis, model training, and prediction pipeline.
