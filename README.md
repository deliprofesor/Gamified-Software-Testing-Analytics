# Gamified-Software-Testing-Analytics 

![Project Header](https://github.com/user-attachments/assets/02bd30ca-d5e1-41ed-bbb8-a8c310c8b2d1)

This project analyzes student engagement and performance data from a gamified software testing course. We explore how gamification elements impact learning effectiveness and student behavior.

##  Project Roadmap

- [x] **Phase 1: Exploratory Data Analysis (EDA)**
  - Statistical distribution of scores across 4 exercises.
  - Correlation analysis between "Active Time" and "Effectiveness".
- [x] **Phase 2: Student Segmentation (Clustering)**
  - Identifying hidden student personas using K-Means clustering.
  - Defining profiles: "Elite Grinders", "Efficient Achievers", and "At-Risk".
- [ ] **Phase 3: Engagement & Dropout Analysis**
  - Identifying behavioral patterns leading to course dropouts.
- [ ] **Phase 4: Predictive Modeling**
  - Forecasting final race performance using early-stage engagement metrics.

##  Key Insights

### Phase 1: General Trends
* **Effectiveness Trends:** Visualized via Box Plots in `reports/figures/`.
* **Engagement Patterns:** Scatter plots revealed a strong positive correlation between active time and test effectiveness.

### Phase 2: Student Personas (Clustering Results)
We identified 3 distinct groups of students based on their behavior:
* **🏆 Cluster 1: "The Elite Grinders"** (Avg. Effectiveness: **97.1%**) - Characterized by extreme persistence with an average of **200.3 executions**.
* **⚡ Cluster 2: "The Efficient Achievers"** (Avg. Effectiveness: **94.1%**) - High success with optimized effort (avg. **71.3 executions**).
* **⚠️ Cluster 0: "The At-Risk"** (Avg. Effectiveness: **55.2%**) - Low engagement and low success (avg. **27.1 executions**).



---

# 📁 Data Sources & Formats

### **Data Files**

| File Name | Format | Description |
|----------|--------|----------|
| `gamification-software-testing.csv` | CSV | Standard format for initial loading. |
| `gamification-software-testing.feather` | Feather | High-performance columnar format. |
| `gamification-software-testing.parquet` | Parquet | Optimized for big data environments. |

### **Data Dictionary (Metadata)**

| File Name | Description | Importance |
|-----------|----------|--------|
| `metadata.csv` | Contains variable names and types. | Primary reference for modeling. |

---

##  Tech Stack
- **Machine Learning:** Scikit-Learn (K-Means, StandardScaler)
- **Processing:** Pandas, PyArrow
- **Visualization:** Seaborn, Matplotlib
- **Environment:** Jupyter Notebooks