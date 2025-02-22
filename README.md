
# Heart Disease Analysis

## Overview
Heart disease is a leading cause of mortality worldwide. This project aims to analyze heart disease datasets using data science and machine learning techniques to extract valuable insights and predict heart disease risk.

## Features
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation
- Visualization of insights

## Dataset
The dataset used for this project is the **Heart Disease Dataset** from Kaggle. It contains various attributes which are crucial in determining heart disease risk.

### Dataset Link
[Heart Disease Dataset - Kaggle]-https://www.kaggle.com/code/desalegngeb/heart-disease-predictions

### Dataset Columns
The dataset consists of the following features:
- `age`: Age of the patient
- `sex`: Sex of the patient (1 = male, 0 = female)
- `cp`: Chest pain type (4 values)
- `trestbps`: Resting blood pressure (in mm Hg)
- `chol`: Serum cholesterol (mg/dl)
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- `restecg`: Resting electrocardiographic results (values 0,1,2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes, 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: The slope of the peak exercise ST segment
- `ca`: Number of major vessels (0-3) colored by fluoroscopy
- `thal`: Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
- `target`: Presence of heart disease (1 = disease, 0 = no disease)

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

## Installation
1. Open Google Colab: [Google Colab](https://colab.research.google.com/)
2. Upload the dataset to Colab.
3. Install necessary dependencies by running:
   ```python
   !pip install pandas numpy matplotlib seaborn scikit-learn
   ```

## Usage
1. Open Google Colab.
2. Upload and open the `Heart_Disease_Analysis.ipynb` notebook.
3. Run the cells step by step.

## Project Workflow
1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and normalizing data.
2. **Exploratory Data Analysis (EDA)**: Understanding the dataset through visualizations and statistical analysis.
3. **Feature Selection**: Identifying the most relevant features for prediction.
4. **Model Training & Evaluation**: Applying simple machine learning models like Logistic Regression and Decision Trees to predict heart disease.
5. **Result Analysis**: Evaluating model performance using accuracy, precision, recall, and F1-score.

## Results
The project provides insights into the factors contributing to heart disease and achieves a predictive model with high accuracy. Visualizations and model performance metrics help in understanding the effectiveness of the approach.

## Future Scope
- Implement deep learning models for better accuracy.
- Deploy the model as a web application.
- Improve feature engineering techniques.

## Contributing
Feel free to fork this repository and contribute to improving the analysis. You can raise an issue or submit a pull request with enhancements.

