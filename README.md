# E-commerce Data Analysis and Sales Prediction Using Machine Learning

## Project Overview
This project analyzes e-commerce sales data and builds a Machine Learning model to predict future sales. It was developed as part of the **AICTE | IBM SkillsBuild Data Analytics with AI Academic Internship 2026** conducted by **BharatCares**.

---

## Dataset
- **Source:** Kaggle — Amazon E-commerce Sales Dataset
- **Link:** https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data
- **File:** `Amazon Sale Report.csv`
- **Records:** ~128,975 rows | 21 columns
- **Features:** Order ID, Category, Size, Quantity, Amount, Ship-State, Status, Date

---

## Technologies Used
| Tool | Purpose |
|------|---------|
| Python 3.9 | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib & Seaborn | Data Visualization |
| Scikit-learn | Machine Learning Models |
| Jupyter Notebook | Code Execution |

---

## Project Structure
```
ecommerce_project/
├── YourName_EcommerceDataAnalysis.ipynb   # Main code file
├── requirements.txt                        # Python dependencies
├── YourName_ProjectReport.docx            # Project documentation
├── README.md                              # This file
└── Amazon Sale Report.csv                 # Dataset (download from Kaggle)
```

---

## ML Models Used
1. **Linear Regression** — Baseline model
2. **Random Forest Regressor** — Best performing model

### Model Performance
| Model | MAE | R2 Score |
|-------|-----|----------|
| Linear Regression | Higher | Lower |
| Random Forest | Lower ✅ | Higher ✅ |

---

## Setup & Run Instructions

### Step 1: Install Python
Download from: https://www.python.org/downloads/

### Step 2: Install Libraries
```bash
pip install -r requirements.txt
```

### Step 3: Download Dataset
- Go to: https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data
- Download `Amazon Sale Report.csv`
- Place it in the `ecommerce_project/` folder

### Step 4: Open Jupyter Notebook
```bash
jupyter notebook
```
Then open `YourName_EcommerceDataAnalysis.ipynb`

### Step 5: Run All Cells
- Click **Kernel → Restart & Run All**

---

## Key Findings
- Identified top-selling product categories
- Analyzed revenue distribution across Indian states
- Built ML model to predict sales amount based on category, size, and quantity
- Random Forest achieved better prediction accuracy than Linear Regression

---

## Author
- **Name:** Your Name
- **Email:** your.email@example.com
- **Internship:** AICTE | IBM SkillsBuild | BharatCares 2026
