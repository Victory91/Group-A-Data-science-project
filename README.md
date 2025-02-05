# Group-A-Data-science-project
A brief description of our project.

**Table of Contents**
- Introduction
- Dataset
- Exploratory Data Analysis (EDA)
- Preprocessing
- Model Development
- Model Evaluation
- Findings and Observations
- Recommendations

**Introduction:**

This repository contains the code and documentation for predicting blood pressure using a machine learning model. The model leverages a variety of demographic, lifestyle, and clinical features to provide accurate predictions, potentially aiding in early detection and management of hypertension.

**Dataset:**

The dataset used in this project includes the following attributes:
- Demographic: Age, Gender
- Lifestyle: Exercising, Smoking status, Alcohol consumption
- Clinical: Medical history, Family history of heart disease, Body mass index (BMI), Blood sugar levels, heart disease status

**Exploratory Data Analysis (EDA):**

Before building the model, an exploratory data analysis (EDA) was performed to understand the dataset better. Key insights include:

- Distribution of demographic attributes

- Correlation between lifestyle factors and blood pressure (Correlation matrix)

- Visualizations of clinical data (boxplot, scatterplot)

**Preprocessing:**

Preprocessing steps involved:

- Handling missing values
  
- Feature engineering to create new relevant attributes

**Model Development:**

The model development process included:
- Selection of algorithms: Linear Regression, Random Forest
- Training the models on the preprocessed dataset

**Model Evaluation:**

The models were evaluated using the Mean Absolute Error (MAE)

**Findings and Observations**
1. The predictive model works and generates values corresponding to the health and lifestyle choices of the patients in the dataset
2. The data collection was not done properly which lead to inaccurate representation of real-life health scenerios where there should a positive correlation observed between factors like age and blood pressure, indicating that older individuals tend to have higher blood pressure. Also, smoking and excessive alcohol consumption are supposed to be positively correlated with elevated blood pressure levels.
3. The model predicted values, particularly around 148, 150, and 152.
4. The Baseline mean absolute error (MAE) was 15.2 which is quite high due to the issues experienced with the dataset. A lower MAE indicates better model performance.
5. The nature of the dataset was densely populated having about 10,000 rows and 21 columns which lead to difficulty in visualization such as scatterplots making it difficult to observe clear relationships between columns despite feature engineering done.

**Recommendation**

Linear Regression model works if a proper dataset is used to train and test the model.

**Contributing:**

1. Fork the repository.
2. Create a new branch.
3. Make changes and commit.
4. Submit a pull request.

**License:**

MIT License

**Acknowledgments:**

- Thanks for your tutoring and mentorship
- Thanks https://github.com/favour-me-art for your collaboration
- Thanks to https://github.com/LexCie10 for your collaboration
- Thanks to https://github.com/trojan-1 for your collaboration
