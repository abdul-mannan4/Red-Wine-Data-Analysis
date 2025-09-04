# Red Wine Quality Analysis

This project performs a comprehensive **data analysis and feature engineering** on the Red Wine dataset. The goal is to explore, clean, and prepare the data for predictive modeling and gain insights into the factors affecting wine quality.

---

## 📂 Dataset

- Dataset: Red Wine Quality dataset
- Features include chemical properties of red wine such as `fixed acidity`, `volatile acidity`, `citric acid`, `residual sugar`, `density`, `alcohol`, and more.
- Target variable: `quality` (wine quality score)

---

## 🛠 Tools & Libraries

- Python 3.x
- Libraries:
  - `pandas` for data loading and preprocessing
  - `numpy` for numerical operations
  - `matplotlib` & `seaborn` for visualization
  - `scikit-learn` for feature scaling and handling class imbalance

---

## 🔹 Project Workflow

1. **Data Loading & Preprocessing**
   - Load data from CSV using Pandas
   - Inspect data using `.info()`, `.describe()`, `.shape`, `.columns`
   - Handle missing values and remove duplicates

2. **Exploratory Data Analysis (EDA)**
   - Target variable analysis
   - Univariate, bivariate, and multivariate analysis
   - Correlation analysis and heatmaps

3. **Feature Engineering**
   - **Outlier Treatment**: Capping and removal
   - **Feature Scaling**: Min-Max Scaling and Standardization
   - **Feature Creation**:
     - `total_acidity = fixed_acidity + volatile_acidity + citric_acid`
     - `sulphate_to_chloride_ratio = sulphates / chlorides`
     - `alcohol_density_interaction = alcohol * density`
   - **Feature Selection**:
     - Keep features with high correlation to target
     - Remove redundant or highly correlated features

4. **Handling Class Imbalance**
   - Checked class distribution
   - Balanced classes by combining categories (Low, Medium, High)
   - Oversampling minority classes (SMOTE) for fair learning

5. **Final Dataset Validation**
   - Class distribution after balancing
   - Feature distribution visualizations
   - Correlation heatmap for final features

---

## 📊 Visualizations

- Histograms for feature distribution  
- Correlation heatmaps  
- EDA plots for target and features

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/abdul-mannan4/Red-Wine-Data-Analysis.git
