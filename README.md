 # 🏅 2026 Data Masters Challenge — 2nd Place
End-to-end data science project analyzing Milan-Cortina 2026 athlete data through data cleaning, exploratory analysis, predictive modeling, and business insights.

## Project Highlights

- **2nd Place** in the 2026 Data Masters Challenge
- Built an end-to-end data science workflow covering **data cleaning, EDA, predictive modeling, model evaluation, and visualization**
- Analyzed **Milan-Cortina 2026 athlete data** to generate predictive and business insights
- Developed collaboratively as a four-person team, with Samara serving as **Project Lead**

## 📌 Project Overview
This repository contains our end-to-end data science workflow for the **2026 Data Masters Challenge**, focused on analyzing athlete data for the Milan-Cortina Winter Olympics.

The objectives of this project are to:
- Clean and validate raw athlete data  
- Perform exploratory data analysis (EDA) and storytelling  
- Build predictive models  
- Generate business insights for decision-making  

The project follows a structured pipeline:  
**Raw Data → Data Cleaning → EDA → Modeling → Business Insights**

---
## 📂 Folder Explanation

### 📊 Data

| Folder | File | Description |
|--------|------|-------------|
| `data/raw/` | `milan_cortina_2026_athletes.csv` | Original raw dataset used as input. This file should remain unchanged to ensure reproducibility. |
| `data/cleaned/` | `01_missing_value_summary_raw.csv` | Summary of missing values in the raw dataset. |
| `data/cleaned/` | `02_duplicate_records_detected.csv` | Identified duplicate records before cleaning. |
| `data/cleaned/` | `04_impossible_values_detected.csv` | Records with invalid or impossible values. |
| `data/cleaned/` | `09_outlier_summary_iqr.csv` | Outlier detection results using IQR method. |
| `data/cleaned/` | `11_before_after_cleaning_summary.csv` | Comparison of dataset before and after cleaning. |
| `data/cleaned/` | `12_cleaning_decision_log.csv` | Log of cleaning decisions applied during preprocessing. |
| `data/cleaned/` | `milan_cortina_2026_cleaned.csv` | Final cleaned dataset. |
| `data/cleaned/` | `milan_cortina_2026_modeling_ready.csv` | Dataset prepared for modeling. |

---

### 📊 Figures
|  File | Description |
|------|-------------|
| `confusion_matrix_best_model_tuned_threshold.png` | Confusion matrix of the best tuned model using optimized threshold. |
| `feature_importance_best_model.png` | Feature importance plot of the best-performing model. |
|  `model_roc_curves.png` | ROC curves comparing model performance across classifiers. |
|  `named_athlete_prediction_test.png` | Predictions on named athlete test samples. |
| `threshold_tuning_macro_f1.png` | Macro F1-score across different classification thresholds. |

### 📓 Notebooks

| Notebook | Description |
|----------|------------|
| `01_Data_Cleaning.ipynb` | Handles data preprocessing, cleaning, and validation steps. |
| `02_eda_storytelling.ipynb` | Performs exploratory data analysis and generates insights. |
| `03_predictive_modeling.ipynb` | Builds and evaluates predictive models. |
| `04_business_insights.ipynb` | Translates analytical results into business insights and recommendations. |
---

### 📑 Reports

| Report | Description |
|--------|------------|
| `Data_Cleaning_Report.pdf` | Summary of data cleaning process and decisions. |
| `EDA_Report.pdf` | Key findings from exploratory data analysis. |
| `Modeling_Report.pdf` | Model performance, evaluation and results. |
| 'Business_Insight_Report.pdf' | Business insights, recommendations and final conclusions |
---

## 🔁 Reproducibility Instructions

# 1. Clone the repository
```bash
git clone https://github.com/Saung210/2026_data_masters_challenge.git
cd 2026_data_masters_challenge
```

# 2. Set up a virtual environment
```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

# 3. Install dependencies
```bash
pip install -r requirements.txt
```

# 4. Run notebooks in order
```bash
jupyter notebook
```

### Execute the notebooks sequentially:

- `01_Data_Cleaning.ipynb`
- `02_eda_storytelling.ipynb`
- `03_predictive_modeling.ipynb`
- `04_business_insights.ipynb`

---

## 📊 Outputs

- Cleaned datasets → `data/cleaned/`  
- Reports → `reports/`  
- Insights and visualizations → notebooks  

---

## 👥 Team Contributions

| Full Name        | Primary Role                     | % Contribution |
|-----------------|----------------------------------|---------------|
| Samara Pires    | Project Lead                     | 25%           |
| Saung Hnin Phyu | Data Cleaning Lead               | 25%           |
| Anna Tam Ly     | Modeling Lead                    | 25%           |
| Yuke Hou        | Business Insights & Report Lead  | 25%           |

---

## 🛠️ Tools & Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📄 License

This project is for academic purposes as part of the 2026 Data Masters Challenge.
