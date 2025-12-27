# Breast Cancer Data Analysis, Modeling & Prediction (R)

##  Overview
This project presents an **end-to-end machine learning workflow in R** for **breast cancer classification**.  
It includes **data cleaning, exploratory data analysis (EDA), feature scaling, predictive modeling, and model evaluation** to classify tumors as **benign (B)** or **malignant (M)**.

The full workflow is implemented using **R Markdown** and provided as both `.Rmd` and rendered `.html` reports.


## Objective
To build, evaluate, and compare multiple supervised machine learning models for accurate breast cancer prediction using numerical tumor features.



## Dataset
- Breast Cancer Wisconsin (Diagnostic) Dataset  
- 569 observations  
- 33 numeric predictors  
- Target variable: `diagnosis` (B / M)
- Download link: https://www.kaggle.com/datasets/khansaafreen/breastdataset  


Note: After downloading, place the CSV file in the data/ folder, and update the file path in your R script



## Methods
- Data cleaning and preprocessing
- Exploratory data analysis (summary statistics, correlations, feature distributions)
- Train–test split (80/20)
- Feature scaling
- Machine learning models:
  - Logistic Regression
  - K-Nearest Neighbors (k = 7)
  - Decision Tree
  - Random Forest



##  Model Evaluation
Models are evaluated using:
- Confusion Matrix
- Accuracy
- Sensitivity
- Specificity
- Precision
- F1 Score

**Best performing model:** Logistic Regression  
- Accuracy ≈ **96.5%**  
- Sensitivity = **100%**





##  Reports
- `reports/breast_cancer.Rmd`
- `reports/breast.html`



##  How to Run
1. Open the `.Rmd` file in RStudio  
2. Ensure `data/data.csv` is available on your local machine and update the file path in the R script to match your local directory
4. Knit the document to HTML



## Repository  Structure
breast-cancer-data-analysis/
│
├── reports/  

│   ├── breast_cancer.Rmd  

│   └── breast.html  

│
├── .gitignore  

├── README.md  

└── LICENSE  




## Author
**Ana Menkshi**



## Disclaimer: 
**The analyses and models in this project are for analytical and demonstration purposes only and are not intended for clinical use.**
