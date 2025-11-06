# Exploratory Data Analysis (EDA) on Student Grades

A **complete, end-to-end EDA notebook** using a **synthetic but realistic** dataset of 35 student grades — intentionally *messy* to showcase real-world data issues.

---

## What This Notebook Demonstrates

- **Synthetic data generation** with controlled randomness  
- **Intentional data corruption**: missing values, negative grades, 10× typos, out-of-range values  
- **Systematic EDA**:  
  - Data preview & schema  
  - Summary statistics  
  - Missingness & validity checks  
  - Outlier & typo detection  
- **Rule-based cleaning** with **full audit trail**  
- **Before/after visualization** of grade distributions  
- **Reproducible outputs** saved to `outputs/`

---

### Key Techniques Used

| Step | Tool / Method |
|------|---------------|
| Data Gen | `numpy.random`, name banks |
| EDA | `pandas.describe()`, `.info()`, custom validity checks |
| Cleaning | `.clip()`, median imputation, 10× typo correction |
| Visualization | `matplotlib.pyplot.hist` |
| Export | `pathlib`, CSV |

---

## How to Use

1. Clone the repo  
2. Run in any Python environment with:
   ```bash
   pip install pandas numpy matplotlib