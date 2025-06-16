# Basic EDA of Hepatitis Dataset

## 📌 Introduction

This folder contains an exploratory data analysis (EDA) of the Hepatitis dataset. The EDA investigates patient records with various clinical features, symptoms, lab results, treatment information, and the survival status (`live=0`, `die=1`). The primary objectives are:

- Assessing data quality
- Identifying patterns and trends
- Preparing the data for further modeling

---

## 📂 Folder Contents

| File Name            | Description                                              |
|----------------------|---------------------------------------------------------|
| `main.ipynb`         | Jupyter notebook with all EDA code and visualizations   |
| `hepatitis.csv`      | Raw dataset used for analysis                           |
| `final_report.pdf`   | Exported PDF report of the EDA findings                 |

---

## 📝 Dataset Overview

- **Rows:** 155 (patients)
- **Columns:** Multiple clinical and demographic variables
- **Target:** Survival status (`live=0`, `die=1`)

---

## 🔍 EDA Workflow

### 1. Importing Libraries

- Utilizes `pandas` for data manipulation
- Uses `matplotlib` and `seaborn` for visualization

### 2. Loading the Dataset

- Loads the dataset with `pandas.read_csv`
- Displays all columns to review structure and data types

### 3. Data Inspection

- **Head and Info:** Shows the first few rows and column data types
- **Summary Statistics:** Provides descriptive statistics for numerical columns
- **Missing Values:** Checks for missing values in each column

### 4. Data Cleaning

- **Handling Missing Values:** Discusses and applies strategies (imputation or dropping)
- **Data Types:** Ensures columns have correct data types

### 5. Univariate Analysis

- **Categorical Variables:** Value counts and bar plots
- **Numerical Variables:** Histograms and boxplots for distributions and outlier detection

### 6. Bivariate Analysis

- **Target vs Features:** Visualizes relationships between survival status and other variables
- **Correlation Matrix:** Heatmap of numerical feature correlations

### 7. Key Findings

- **Survival Distribution:** Breakdown of live vs. die outcomes
- **Important Features:** Highlights features most associated with survival
- **Missing Data Impact:** Discusses handling and impact of missing values

---

## 📊 Visualizations

The notebook includes:

- Bar plots for categorical features
- Histograms for numerical features
- Boxplots for outlier detection
- Correlation heatmap for numerical features

---

## 📄 How to Use

1. Open `main.ipynb` in Jupyter Notebook or a compatible environment.
2. Run the cells sequentially to reproduce the analysis and visualizations.
3. Refer to `final_report.pdf` for a summary of findings.

---

**For issues or suggestions, please open an issue or pull request in the repository.**
