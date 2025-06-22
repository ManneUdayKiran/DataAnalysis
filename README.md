
# 📊 Colab & Conquer — Your First Data Notebook

This project demonstrates basic exploratory data analysis (EDA) using **Google Colab**, **pandas**, and **matplotlib**. The goal is to load a dataset, generate summary statistics, and visualize feature distributions through histograms.

---

## 📁 Dataset

**Source:** [https://bit.ly/4nejNue](https://bit.ly/4nejNue)  
The dataset is loaded directly using pandas and contains multiple numeric features suitable for basic EDA.

---

## ✅ Tasks Completed

### 1. **Load Data using `pandas`**
- Used `pd.read_csv()` to load the dataset from a URL.

### 2. **Show Basic Statistics**
- Displayed `.describe()` output for summary stats.
- Calculated and printed:
  - **Mean**
  - **Median**
  - **Standard Deviation**

### 3. **Visualize Features**
- Plotted **histograms** for all numeric features using `matplotlib`.

---

## 🛠️ Tools & Libraries

- [Google Colab](https://colab.research.google.com/)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)

---

## 📌 How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Copy the code from the main notebook or use the following:
   ```python
   import pandas as pd
   import matplotlib.pyplot as plt

   url = "https://bit.ly/4nejNue"
   df = pd.read_csv(url)

   print(df.describe())
   df.hist(figsize=(12, 8))
   plt.show()
````

---

## 📚 Learning Outcomes

* Learn to use pandas for data inspection.
* Understand basic statistical summaries.
* Visualize data distributions with histograms.
* Practice writing clean, readable EDA notebooks.

---

## 📸 Sample Output

*(Optional: Add screenshots of histograms and `.describe()` output here)*

---

## 🧠 Bonus Ideas

* Add correlation heatmaps with `seaborn`.
* Perform missing value analysis.
* Use boxplots for outlier detection.

