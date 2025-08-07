# Task 2 – Titanic Dataset: Exploratory Data Analysis (EDA)

## 📌 Objective
Explore the Titanic dataset to uncover patterns in passenger survival using Python and visual analytics.

---

## 🧰 Tools Used
- Python (Pandas, Seaborn, Matplotlib)
- Google Colab
- Titanic dataset from Kaggle (via GitHub URL)

---

## 🧹 Data Cleaning
- Filled missing Age values with the median
- Filled Embarked values with the mode
- Dropped Cabin column (too many nulls)
- Converted categorical columns (Sex, Embarked) for visualization and correlation

---

## 📊 Visualizations & Insights

| Visualization                        | Insight Summary |
|-------------------------------------|-----------------|
| Barplot: Survival by Gender         | 74% of females survived vs. 19% of males |
| Barplot: Survival by Class          | 62% of 1st class vs. 24% of 3rd class survived |
| Histogram: Age of Survivors         | Most were 20–30 years old, some infants too |
| Violin plot: Age by Survival & Sex  | Young women had higher survival across all ages |
| Countplot: Embarked vs. Survival    | Cherbourg passengers had highest survival |
| Heatmap: Correlations               | Higher Fare & lower Pclass positively correlate with survival |

---

## 📁 Files Included
- Titanic_EDA_EssamMohamed.ipynb
- Titanic_EDA_Report.pdf
- README.md

---

## ✅ Outcome
This task demonstrates key EDA skills including:
- Cleaning real-world data
- Group-based statistical analysis
- Multi-variable visualizations
- Clear interpretation of insights
