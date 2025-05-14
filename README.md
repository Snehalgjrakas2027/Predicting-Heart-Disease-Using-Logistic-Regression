
#  Predicting Heart Disease Using Logistic Regression

This project focuses on building a **Logistic Regression** model to predict whether a patient has heart disease based on various medical features such as age, cholesterol level, blood pressure, and more.

## 📌 Objective

To develop a binary classification model that predicts the **presence or absence of heart disease** in a patient, using logistic regression based on clinical and demographic attributes.

## 🧬 Dataset

The dataset typically includes the following features:

* Age
* Gender
* Resting blood pressure
* Serum cholesterol
* Fasting blood sugar
* Resting electrocardiographic results
* Maximum heart rate achieved
* Exercise-induced angina
* ST depression induced by exercise
* Slope of the peak exercise ST segment
* Number of major vessels colored by fluoroscopy
* Thalassemia (thal)
* **Target (0 = No Heart Disease, 1 = Heart Disease)**

> *Source: UCI Heart Disease Dataset (or other medical datasets depending on the source you use)*

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn (for visualization)


4. **Model output**

   * The logistic regression model will output predictions on the test set.
   * Evaluation metrics such as **Accuracy**, **Precision**, **Recall**, **F1 Score**, and **ROC-AUC** will be displayed.

## 📈 Model Evaluation Metrics

* **Accuracy** – Overall, how often is the classifier correct?
* **Precision** – What proportion of predicted positives is truly positive?
* **Recall (Sensitivity)** – What proportion of actual positives is correctly identified?
* **F1 Score** – Harmonic mean of precision and recall.
* **ROC-AUC** – Area under the receiver operating characteristic curve.


## 🚀 Future Enhancements

* Add feature selection or dimensionality reduction (e.g., PCA).
* Experiment with other classifiers: Random Forest, SVM, XGBoost.
* Build a simple web interface using Flask or Streamlit to take patient inputs and show predictions.

