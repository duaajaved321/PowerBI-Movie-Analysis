# 🎬 Movie Revenue & Ratings Analysis (Power BI Dashboard)

## 📌 Project Overview
This project explores the intersection of **commercial success** and **critical reception** in the film industry. Using a publicly available movie dataset, I developed an interactive Power BI dashboard to analyze how profitability correlates with viewer and critic ratings across major and independent studios.

### ❓ Key Analytical Questions
* **How are the most profitable movies rated by viewers and critics?**
* **How much revenue did each of the top-rated films generate for its studio?**
* **Which movie had the highest worldwide gross?**

---

## 📊 Dashboard Features
The dashboard is designed to provide both high-level summaries and granular movie-level insights:

### 1. Profitability vs. Ratings Analysis (Combo Chart)
* **Visual:** Bar chart (Profitability) with a Line chart overlay (Average Total Rating).
* **Purpose:** To identify if high-profit "blockbusters" satisfy audiences or if "prestige" films with high ratings struggle commercially.

### 2. Studio Revenue Contribution (Treemap)
* **Visual:** Treemap grouped by **Studio** and segmented by **Film**.
* **Purpose:** Visualizes how much specific "heavy hitter" films contribute to the total revenue of their respective studios.

### 3. Studio-Level Summary Table (Matrix)
* **Visual:** Aggregated table with drill-down capabilities.
* **Purpose:** Provides a snapshot of **Average Ratings** and **Total Worldwide Gross** for quick studio-to-studio comparison.

---

## 🔍 Key Insights
* **The Profit-Rating Gap:** High profitability does not always guarantee high critical acclaim. Some of the most profitable films in the dataset maintain average ratings.
* **Blockbuster Dependency:** Major studios like **Warner Bros** and **Disney** see a significant portion of their revenue driven by a few top-performing titles.
* **Market Leaders:** Within this dataset, **Warner Bros** leads in total worldwide gross, followed closely by **Disney** and **Summit Entertainment**.

---

## 🛠 Tools & Technologies
* **Power BI Desktop:** Dashboard development and data visualization.
* **DAX (Data Analysis Expressions):** Used for calculating profitability metrics and ranking top-performing films.
* **Data Modeling:** Established relationships between movie facts and studio reference tables.

---

## 📁 Repository Structure
```text
├── Dashboard/
│   └── Movie_Analysis_Dashboard.pbix  # Power BI File
├── Data/
│   └── movie_dataset.csv              # Source Data
├── Images/
│   └── dashboard_preview.png          # Visual Preview
└── README.md                          # Project Documentation
