
# 📊 College Majors Salary Data Exploration with Pandas

This project focuses on **data exploration and cleaning** using the Python `pandas` library on a dataset of salaries categorized by college majors. The goal is to analyze which majors have the highest starting and mid-career salaries, determine risk levels based on salary spread, and identify trends across academic fields.

---

## 🗂 Dataset

The dataset used in this project is `salaries_by_college_major.csv`, which includes:

- `Undergraduate Major`
- `Starting Median Salary`
- `Mid-Career Median Salary`
- `Mid-Career 10th Percentile Salary`
- `Mid-Career 25th Percentile Salary`
- `Mid-Career 75th Percentile Salary`
- `Mid-Career 90th Percentile Salary`

---

## ✅ Objectives

- Load and clean the dataset by handling missing values.
- Find:
  - Majors with highest/lowest starting and mid-career salaries.
  - Majors with the smallest and largest salary spread (risk factor).
  - Majors with the highest potential earnings (90th percentile).
- Sort data to identify patterns and insights.
- Add new metrics like salary spread for better analysis.

---

## 🧠 Key Learnings

- Reading and cleaning CSV files using `pandas`
- Data inspection using `.head()`, `.tail()`, `.shape`, `.isna()`
- Handling missing data with `dropna()`
- Using `idxmax()` and `idxmin()` for locating specific values
- Adding calculated columns (`Spread`)
- Sorting data with `.sort_values()`
- Basic data visualization potential (not included but can be extended)

---

## 🔧 Technologies Used

- Python
- Jupyter Notebook
- Pandas

---

## 📁 Project Structure

```
📦 College Major Salary Analysis
 ┣ 📜 Data_Exploration_Pandas_College_Major_(complete).ipynb
 ┣ 📜 salaries_by_college_major.csv
 ┗ 📜 README.md
```

---

## 📌 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/college-major-salary-analysis.git
cd college-major-salary-analysis

# Open the notebook
jupyter notebook Data_Exploration_Pandas_College_Major_(complete).ipynb
```

---

## 📈 Sample Insights

- The **highest starting salary** belongs to **Engineering majors**.
- **Philosophy majors** have a lower starting salary but high mid-career growth.
- **Spread** metric helps measure the **risk vs reward** of choosing a major.

---

## 📌 Next Steps (Optional Extensions)

- Add data visualizations using Seaborn/Matplotlib.
- Create an interactive dashboard using Streamlit.
- Compare with cost of education to find ROI for each major.
