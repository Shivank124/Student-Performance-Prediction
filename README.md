# Student Performance Prediction

## Overview  

The "Student Performance Prediction" project is designed to predict students' math scores based on various factors, providing valuable insights for educators to understand and identify influential elements affecting academic outcomes.  

## Project Components  

### 1. Data Ingestion  

- **Description:** Ingests student performance data from a CSV file.  
- **Files:** `DataIngestion.py`, `train.csv`, `test.csv`, `data.csv`  

### 2. Data Transformation  

- **Description:** Preprocesses data by handling missing values, scaling numerical features, and one-hot encoding categorical features. The preprocessing steps are saved for reproducibility.  
- **Files:** `DataTransformation.py`, `DataTransformationConfig.py`  

### 3. Model Training   

- **Description:** Trains various regression models, including Random Forest, Decision Tree, Gradient Boosting, Linear Regression, XGBoost, CatBoost, and AdaBoost. Hyperparameter tuning optimizes model performance.  
- **Files:** `ModelTrainer.py`, `ModelTrainerConfig.py`  

### 4. Model Evaluation  

- **Description:** Evaluates models using the R-squared metric on a dedicated testing dataset. The model with the highest R-squared score is selected as the optimal predictor of student math scores.  
- **Files:** `evaluate_models.py`  

### 5. Model Persistence  

- **Description:** Saves the best-performing model for future deployment, enabling predictions on new data and supporting ongoing educational interventions.  
- **Files:** `save_object.py`  

## Project Achievements  

- **R-squared Score:** The project achieves a significant R-squared score of 87.98% on the testing dataset, indicating the model's robust ability to capture variance in student math scores.  

## Key Technologies  

- Python  
- Pandas  
- Scikit-learn  
- XGBoost  
- CatBoost  
- AdaBoost  
- Logging and Exception Handling  
- Data Preprocessing Techniques  
- Hyperparameter Tuning
- 
### 6. Retrieve Best Model:  
The best-performing model is saved at artifacts/model.pkl.

### 7. Note:  
A high R-squared score is achieved through thoughtful feature engineering, model selection, and hyperparameter tuning. Contextual understanding of the data and interpretation of model results are critical for successful project implementation.
