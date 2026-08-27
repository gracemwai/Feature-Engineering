# Titanic - Machine Learning from Disaster Titanic 

##  Project Overview
This project builds a predictive model to determine which passengers survived the Titanic shipwreck using passenger data (such as age, gender, socio-economic class, etc.). This is a binary classification problem focused on data preprocessing, feature engineering, and model evaluation.

##  Tech Stack & Concepts
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy
* **Categorical Encoding:** 
  * `OneHotEncoder`: Used for nominal variables without a natural order (e.g., `Sex`, `Embarked`).
  * `LabelEncoder`: Used for transforming binary categories or the target variable.
* **Evaluation Metric:** Accuracy Score (`accuracy_score`)

##  Workflow & Key Features
1. **Data Preprocessing & Cleaning:** 
   * Handled missing data in critical columns like `Age` and `Embarked`.
   * Dropped non-predictive or high-cardinality features (like `PassengerId`, `Name`, `Ticket`).
2. **Feature Encoding:** Converted text-based categorical variables into numerical formats using `OneHotEncoder` and `LabelEncoder` so the machine learning model could process them without introducing artificial ranking.
3. **Model Evaluation:** Split the dataset into training and testing sets to evaluate generalizability, measuring performance using `accuracy_score`.

##  Results
The classification model achieved the following baseline performance on the test set:
* **Accuracy Score:** [0.8206106870229007 for label encoding and   0.8244274809160306 for one hot encoding]
## ⚙️ How to Run This Project
1. Clone the repository using SSH:
   ```bash
   git clone git@github.com:gracemwai/Feature-Engineering.git
   ```
2. Install the required libraries:
   ```bash
   pip install scikit-learn pandas numpy
   ```
3. Run the notebook or script:
   ```bash
   python main.py
   ```

