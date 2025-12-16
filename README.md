Wine Quality Prediction – README
This project focuses on predicting wine quality using machine learning models based on chemical
characteristics.
The dataset includes various attributes such as acidity, sugar levels, pH, sulphates, alcohol, and more.
-------------------------
■ Project Workflow
-------------------------
1. Upload Dataset
You can upload your wine dataset manually in Google Colab using:
from google.colab import files
uploaded = files.upload()
2. Exploratory Data Analysis (EDA)
Includes:
- Data overview
- Null value check
- Statistical summary
- Correlation heatmap
3. Data Preprocessing
- Feature/Target separation
- Train-test split (80/20)
- Feature scaling using StandardScaler
4. Machine Learning Models
Three classifiers are used:
- Random Forest Classifier
- SGD Classifier
- Support Vector Classifier (SVC)
5. Model Evaluation
- Accuracy score
- Classification report
- Confusion matrix
- Model comparison
-------------------------
■ Dataset Requirements
-------------------------
Your dataset must contain a 'quality' column as the target variable.
If not, adjust the code accordingly.
-------------------------
■ Results
-------------------------
All models are compared, and the best model is selected based on accuracy.
-------------------------
■ Files Included
-------------------------
- README PDF (this file)
- Your Google Colab Notebook (.ipynb)
- Uploaded dataset (CSV)
-------------------------
■ Author
-------------------------
This project was created for educational and machine learning practice purposes.
