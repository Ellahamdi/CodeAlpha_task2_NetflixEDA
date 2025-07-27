#  CodeAlpha - Task 2: EDA
✅ **Internship Task:** EDA  
✅ **Intern Name:** Ella Hamdi   
✅ **Company:** CodeAlpha - [www.codealpha.tech](https://www.codealpha.tech)
## 📌 Objectives

- Perform a detailed exploratory data analysis on the Netflix dataset.
- Ask relevant business questions and test hypotheses.
- Detect data quality issues and perform cleaning.
- Visualize patterns, trends, and anomalies using Python libraries.

---

## 🧠 Key Questions Explored

1. What is the overall composition of content on Netflix (Movies vs TV Shows)?
2. How has Netflix's content library evolved over time?
3. Which countries dominate the content production?
4. What is the distribution of content ratings (e.g., PG, TV-MA)?
5. Who are the most frequent directors or actors on the platform?
6. What are the top genres on Netflix?
7. How long are movies on average?
8. What types of content are most frequently added?
9. Are there any seasonal trends in content additions?
10. What are the most recommended and high-quality films based on multiple factors?

---

## 🧪 Hypothesis Testing

Each question led to a hypothesis that was tested using descriptive statistics and visualizations.
Examples:
- Netflix contains more Movies than TV Shows ✅
- Content additions increased sharply after 2016 ✅
- USA dominates the Netflix catalog ✅
- The average movie duration is around 90 minutes ✅

---

## 📉 Visualizations Used

- Countplots and Barplots
- Line charts for trends over time
- Histograms with KDE
- Heatmaps for missing values (optional)
- Custom filters for Top 10 lists

All visualizations were created using `matplotlib`, `seaborn`, and `pandas`.

---

## 🧼 Data Cleaning Performed

- Extracted duration into numerical + categorical columns
- Formatted `date_added` to datetime
- Removed rows with critical missing values (like `date_added`)
- Handled missing `country`, `rating`, and `cast` fields
- Removed duplicates if present

---

## 🚨 Potential Data Issues Identified

- Missing values in `director`, `cast`, `rating`, and `date_added`
- Mixed formats in the `duration` column
- Outliers in duration (some movies > 300 min)
- Multi-genre strings hard to analyze (`listed_in` column)

---

## 🔗 Dataset Source

Netflix Dataset from [Kaggle](https://www.kaggle.com/shivamb/netflix-shows)

---

## 💻 Tools & Libraries

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook 

## 👩‍💻 Author

**Ella Hamdi**
_Data Analytics Intern @ CodeAlpha | Aspiring BI Analyst_
🔗 [[My LinkedIn](https://www.linkedin.com/in/ella-hamdi-662974375)]

---

## 📬 Contact

For collaboration or feedback:
📧 hamdiella55@example.com 

---

## 🏅 Internship Program

This project is part of the **Data Analytics Internship - July 2025**
Organized by: [CodeAlpha](https://codealpha.tech)

---
