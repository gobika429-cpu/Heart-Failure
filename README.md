# Heart-Failure
❤️ Heart Failure Clinical Records – Machine Learning

📌 Project Overview

This project focuses on analyzing Heart Failure Clinical Records using Python and applying Machine Learning classification techniques to predict patient outcomes.

The project covers the complete workflow from data preprocessing and exploratory data analysis (EDA) to Machine Learning model building and evaluation.

The dataset used in this project is obtained from the UCI Machine Learning Repository and contains clinical information of patients.

---

🎯 Objectives

* Understand and analyze the Heart Failure Clinical Records dataset.
* Perform data cleaning and preprocessing.
* Explore patient-related clinical features.
* Handle categorical and numerical variables.
* Analyze relationships between features using correlation analysis.
* Prepare the dataset for Machine Learning.
* Build classification models using different algorithms.
* Predict the target outcome.
* Compare and evaluate the performance of the classification models.

---

🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

📂 Project Workflow

1. Data Collection

The Heart Failure Clinical Records dataset was collected from the UCI Machine Learning Repository and imported into Python for analysis.

2. Data Preprocessing

The dataset was checked and prepared by:

* Understanding the dataset
* Checking the shape of the dataset
* Checking data types
* Checking missing values
* Checking duplicate values
* Identifying numerical and categorical features
* Removing unnecessary columns where required
* Converting categorical values into suitable formats

3. Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand the clinical dataset using:

* Descriptive statistics
* Data distribution analysis
* Target variable distribution
* Feature analysis
* Graphical visualizations
* Categorical feature analysis
* Correlation analysis

4. Data Encoding

Categorical variables such as Sex, Education, and Marriage were converted into numerical representations using suitable encoding techniques.

The target variable was represented as:

* 1 → YES
* 0 → NO

This prepared the data for classification algorithms.

5. Correlation Analysis

Correlation analysis was performed to understand the relationship between the clinical features.

A correlation matrix and heatmap were used to identify relationships between numerical variables and the target variable.

6. Machine Learning

After preprocessing and EDA, the dataset was prepared for Machine Learning.

The dataset was divided into:

* Training Data
* Testing Data

Multiple classification algorithms were trained and tested to predict the target outcome.

7. Classification Algorithms

The project uses four Machine Learning classification algorithms:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* K-Nearest Neighbors (KNN)

The performance of these algorithms was compared to identify the better-performing model.

---

📊 Model Evaluation

The trained classification models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics were used to understand how accurately the models classify patient outcomes.

---

📁 Project Structure

Heart-Failure-Clinical-Records/
│
├── dataset/
│   └── heart failure.csv
│
├── HEART FAILURE (1).ipynb
│
├── README.md
│
└── requirements.txt

---

🔧 Installation

Install the required Python libraries using:

pip install pandas numpy matplotlib seaborn scikit-learn

---

▶️ How to Run

1. Download or clone the project.
2. Open "HEART FAILURE (1).ipynb" in Jupyter Notebook.
3. Make sure the Heart Failure dataset is available in the correct location.
4. Run the notebook cells in order.
5. Perform data preprocessing and EDA.
6. Train the four classification models.
7. Evaluate and compare the model results.

---

📈 Results

The project successfully completed the following stages:

Data Collection → Data Preprocessing → EDA → Encoding → Correlation Analysis → Train-Test Split → Classification Model Building → Prediction → Model Evaluation

Four classification algorithms were implemented and evaluated using different performance metrics.

The model results can be compared using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

---

📚 Learning Outcomes

Through this project, I learned how to:

* Work with clinical datasets using Python.
* Perform data preprocessing.
* Handle categorical and numerical variables.
* Perform Exploratory Data Analysis.
* Create visualizations using Matplotlib and Seaborn.
* Analyze feature correlations.
* Prepare data for Machine Learning.
* Perform train-test splitting.
* Build classification models.
* Compare multiple Machine Learning algorithms.
* Evaluate classification models using performance metrics.

---

👩‍💻 Author

GOBIKA R

BCA Student

Interested in Python, Data Science, Machine Learning and UI/UX Design.

---

⭐ Project Status

Completed ✅

The project has been completed up to Machine Learning Model Building and Evaluation using four classification algorithms.
