# 📊 Medical-Students Dataset Preprocessing Project

This project focuses on **data preprocessing** of a Medical-Students dataset sourced from **Kaggle**. It includes all essential data cleaning and transformation steps to prepare the dataset for further machine learning tasks.

---

## 📁 Dataset Information
- **Type:** Tabular, Supervised
- **Goal:** Prepare data for predicting loan approval

---
## 📌 Key Preprocessing Steps

1. **Exploratory Data Analysis (EDA):**
   - Visualize missing values
   - Understand distributions and relationships

2. **Handling Missing Values:**
   - Impute numerical features using median
   - Impute categorical features using mode

3. **Encoding Categorical Variables:**
   - Label Encoding for binary columns
   - One-Hot Encoding for multiclass columns

4. **Outlier Treatment:**
   - IQR method or Z-score filtering

5. **Feature Scaling:**
   - StandardScaler or MinMaxScaler used to normalize numerical columns

6. **Saving Cleaned Data:**
   - Exported to `cleaned_loan_data.csv` for ML usage

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Matplotlib / Seaborn (for EDA)
- Scikit-learn

---
## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/SyedaHadiaZainab/Medical-Students Dataset.git
cd loan-preprocessing
2. Install Dependencies
pip install -r requirements.txt
3. Run Preprocessing
Open the notebook and run:

🧠 Key Insights
Imputation techniques significantly improved data quality.

One-hot encoding increased feature dimensionality but preserved category info.

Scaled data is now suitable for training ML models like logistic regression or decision trees.

👩‍💻 Author
Syeda Hadia Zainab
Student of Software Engineering at Fatima Jinnah Women University
📧 Email: taqviggg@gmail.com
🔗 LinkedIn: syeda-hadia-zainab

