Academic Performance Analysis — Data Science Project

This project performs a comprehensive analysis of students’ academic performance using Data Science and Machine Learning techniques.
It includes data cleaning, exploratory data analysis, feature engineering, dataset preparation, and the training of multiple predictive models.

🎯 Project Objective

Identify the key factors that influence whether a student passes or fails,
and build predictive models capable of forecasting this outcome with an acceptable level of accuracy.

🧠 Technologies Used

Python 3

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

📁 Project Structure
academic-performance-analysis/
│── data/                  # Dataset used
│── notebooks/             # Jupyter Notebook with analysis and models
│── images/                # Charts generated during analysis
│── README.md              # Project documentation
│── requirements.txt       # Required dependencies
│── .gitignore             # Git ignored files

📊 Analysis Workflow
1️⃣ Data Cleaning

Handling missing values

Data type validation

Inconsistency correction

Normalization of column names and categories

2️⃣ Exploratory Data Analysis (EDA)

Variable distribution analysis

Relationships between academic factors

Correlation visualization

Pattern and trend identification

3️⃣ Feature Engineering

Creation of a binary target variable:

1 = Passed

0 = Failed

Encoding categorical variables (LabelEncoder)

Scaling numerical features (StandardScaler)

4️⃣ Data Splitting

70% Training

30% Testing

🤖 Trained Models and Performance
🔹 Logistic Regression

Accuracy: 0.78

Strong performance predicting passing students

Lower precision for failing cases

🔹 Decision Tree

Accuracy: 0.75

High precision for passing students

Limited performance for failing cases

(Random Forest can be added in future iterations)

📈 Results Summary
Model	Accuracy
Logistic Regression	0.78
Decision Tree	0.75
🚀 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/rhaynel19/academic-performance-analysis.git

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the analysis
jupyter notebook

👨‍💻 Author

Fraimel (Rhayner) Trinidad
BSc in Business Administration | Data Analyst | Data Science & Artificial Intelligence Student

📧 Open to collaborations, improvements, and suggestions.

Any feedback or contributions are welcome.
