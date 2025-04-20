# 🎢 Roller Coaster Data Analysis - Full Report

---

## 1. Introduction

The objective of this project was to perform a comprehensive analysis of a global roller coaster dataset, uncovering trends in coaster design, performance specifications, and historical patterns. The project involved rigorous data cleaning, exploration, visualization, and deriving meaningful insights.

Dataset: **coaster_db.csv**

Key fields included:
- Coaster Name
- Location
- Manufacturer
- Operational Status
- Speed (mph)
- Height (ft)
- Number of Inversions
- G-Force
- Year Introduced
- Coaster Type (Main)

---

## 2. Data Preparation

**Steps performed:**

- **Column Reduction:** Removed irrelevant, redundant, and incomplete columns to streamline the dataset.
- **Duplicate Handling:** Duplicates were identified and removed based on 'Coaster Name', 'Location', and 'Opening Date'.
- **Column Renaming:** Standardized column names for clarity (e.g., `coaster_name` to `Coaster_Name`).
- **Missing Values:** Analyzed missing data; no heavy imputations were necessary.

Resulting dataset shape: **(n_samples, n_features)** after cleaning.

---

## 3. Exploratory Data Analysis (EDA)

### 3.1 Coasters Introduced by Year

A bar plot was generated showing the number of coasters introduced per year. 

**Observations:**
- Peak introduction years were the late 1990s and early 2000s.
- Post-2010, the introduction rate stabilized but remained consistent.

### 3.2 Distribution of Coaster Speeds

- A histogram indicated that most roller coasters operate between **30 to 70 mph**.
- A KDE (Kernel Density Estimate) plot further confirmed the smooth distribution of coaster speeds.

**Observations:**
- Extremely high-speed coasters (above 100 mph) are rare.

### 3.3 Speed vs Height Relationship

A scatter plot was plotted between **Speed (mph)** and **Height (ft)**.

**Insights:**
- A positive correlation: taller coasters tend to achieve higher speeds.
- Outliers exist (very tall but moderate speed coasters and vice versa).

### 3.4 Pairwise Relationships

Using a Seaborn `pairplot`, we explored relationships among:
- Year Introduced
- Speed
- Height
- Inversions
- G-force

Color coding was done based on the **Main Type** (Steel, Wooden).

**Insights:**
- Steel coasters typically dominate in speed and height.
- Wooden coasters cluster around moderate speed and height ranges.

### 3.5 Feature Correlation Heatmap

A heatmap was created showing correlation coefficients among numerical features.

**Key Correlations:**
- Speed and Height: **~0.6** (moderate positive correlation)
- Speed and G-force: weak correlation
- Height and Inversions: low correlation

---

## 4. Key Insights

- **Tall = Fast:** Taller roller coasters generally correspond to higher speeds.
- **Steel vs Wooden:** Steel coasters are faster, taller, and often involve more inversions than wooden coasters.
- **Inversion Trends:** No strong correlation between coaster height and the number of inversions.
- **Historical Trends:** The late 1990s saw a major boom in coaster construction, possibly linked to technological advancements.
- **Design Complexity:** Moderate correlations imply that multiple factors, not just one, drive coaster performance.

---

## 5. Conclusion

Through careful data cleaning, exploration, and visualization, this project uncovered valuable insights into the design and evolution of roller coasters.

The dataset highlights clear trends in coaster construction, particularly the rise of steel coasters and the tendency for height and speed to be coupled in modern designs. 

Future analysis could explore:
- Regional trends (e.g., US vs Europe vs Asia coaster characteristics)
- Predictive modeling (e.g., predicting speed based on other features)
- Sentiment or popularity analysis based on coaster attributes

---

## 6. Limitations

- Some missing values in key features could affect advanced modeling.
- Data may not reflect very recent coaster designs (post-2023).
- Limited information on ride theming, rider experience, or maintenance history.

---

> *This project demonstrates the power of EDA in understanding real-world phenomena through structured datasets. Built using Python, Pandas, Seaborn, and Matplotlib.* 🎢📊

---

# 📎 Notes:

**Graphs** generated during analysis (suggestions for GitHub if needed):
- "Top 10 Years with Most Coasters Introduced" bar chart
- "Coaster Speed Distribution" histogram and KDE
- "Speed vs Height Scatter Plot"
- "Feature Pairplots (colored by Type)"
- "Feature Correlation Heatmap"
