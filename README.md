# Sales Prediction using Machine Learning

This project predicts product sales based on advertising and related features using machine learning.  
It was developed as part of an internship task, with the workflow implemented in a Jupyter Notebook.

## 📂 Project Structure
- `notebook.ipynb` — main Jupyter Notebook with data loading, preprocessing, modeling, and evaluation.  
- `data.csv` — dataset used for training and testing (not included here).  
- `requirements.txt` — Python dependencies.  
- `final_sales_model.joblib` — saved trained model (generated after training).  

## ⚙️ Workflow
1. **Data Loading**  
   Load the dataset, remove index columns, and inspect the structure.  

2. **Exploratory Data Analysis (EDA)**  
   Quick checks on missing values, data types, and target distribution.  

3. **Preprocessing**  
   - Impute missing values  
   - Scale numeric features  
   - One-hot encode categorical features  

4. **Modeling**  
   - Baseline: Linear Regression  
   - Stronger models: Random Forest & Gradient Boosting  
   - Optional hyperparameter tuning with GridSearchCV  

5. **Evaluation**  
   - RMSE, MAE, and R² metrics  
   - Residual and true vs predicted plots  
   - Feature importance visualization  

6. **Saving the Model**  
   The trained model is saved as a `.joblib` file for reuse.  

## 🚀 How to Run
1. Clone this repository or copy the files.  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
3. Open notebook and run all cells in correct order
