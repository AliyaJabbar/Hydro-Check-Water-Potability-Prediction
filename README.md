# Hydro-Check-Water-Potability-Prediction
Project Overview
This project aims to predict whether water is potable (safe for drinking) based on various physicochemical parameters. Using machine learning techniques, we analyze water quality data and classify it as potable or non-potable to help ensure safe drinking water.

📊 Dataset
The dataset contains water quality indicators such as:

pH – Measures acidity/alkalinity of water
Hardness – Presence of calcium and magnesium ions
Solids – Total dissolved solids (TDS) in water
Chloramines – Amount of disinfectant in water
Sulfate – Presence of sulfate ions
Conductivity – Water’s ability to conduct electricity
Organic Carbon – Organic matter in water
Trihalomethanes (THMs) – Chemical byproducts from water disinfection
Turbidity – Clarity of water
Potability – Target variable (1 = Potable, 0 = Not potable)

⚙️ Technologies Used
Python
Pandas, NumPy – Data preprocessing
Matplotlib, Seaborn – Data visualization
Scikit-learn – Machine learning models
Jupyter Notebook

🏗️ Model Development
Data Preprocessing

Handle missing values
Normalize/scale data
Handled outliers 
Exploratory Data Analysis (EDA)

Visualize feature distributions
Analyze correlations between variables
Model Selection & Training

Implemented Random Forest Classifier (other models like Logistic Regression, Decision Trees were tested)
Used GridSearchCV for hyperparameter tuning
Applied Cross-validation to ensure model reliability
Evaluation Metrics

Accuracy
Precision, Recall, F1-Score
Confusion Matrix
🚀 Results & Insights
The Random Forest Classifier provided the best accuracy after tuning.
Water potability is significantly influenced by pH, hardness, and organic carbon.
Data imbalance was handled to improve model performance.
