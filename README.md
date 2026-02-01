# Gamified-Software-Testing-Analytics 

![Project Header](https://github.com/user-attachments/assets/02bd30ca-d5e1-41ed-bbb8-a8c310c8b2d1)

This project analyzes student engagement and performance data from a gamified software testing course. We explore how gamification elements impact learning effectiveness and student behavior.

##  Project Roadmap

- [x] **Phase 1: Exploratory Data Analysis (EDA)**
  - Statistical distribution of scores across 4 exercises.
  - Correlation analysis between "Active Time" and "Effectiveness".
  - Visualization of performance trends by academic years.
- [ ] **Phase 2: Student Segmentation (Clustering)**
  - Grouping students into learning profiles (e.g., High Achievers vs. Strugglers).
- [ ] **Phase 3: Engagement & Dropout Analysis**
  - Identifying behavioral patterns leading to course dropouts.
- [ ] **Phase 4: Predictive Modeling**
  - Forecasting final race performance using early-stage engagement metrics.

##  Phase 1 Insights
In this initial phase, we processed the raw data to understand student distributions. Key findings:
* **Effectiveness Trends:** Visualized via Box Plots in `reports/figures/`.
* **Engagement Patterns:** Scatter plots revealed how increased active time correlates with higher test effectiveness.

---

#  Data Sources & Formats

The dataset includes student behavior and success metrics across four exercises and the overall course performance.

### **Data Files**

| File Name | Format | Description |
|----------|--------|----------|
| `gamification-software-testing.csv` | CSV | Standard format for initial loading. |
| `gamification-software-testing.feather` | Feather | High-performance columnar format for Python/R. |
| `gamification-software-testing.parquet` | Parquet | Optimized for big data environments and compression. |

### **Data Dictionary (Metadata)**

| File Name | Description | Importance |
|-----------|----------|--------|
| `metadata.csv` | Contains variable names, types, and examples. | Primary reference for data processing and modeling. |

---

##  Tech Stack
- **Processing:** Pandas, PyArrow
- **Visualization:** Seaborn, Matplotlib
- **Environment:** Jupyter Notebooks
