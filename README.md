# 🏙️ City of Boston — CityScore Metrics Analysis

## 📊 Project Overview
This project analyzes and visualizes the **City of Boston’s CityScore metrics** using open data from the [Boston Open Data Portal](https://data.boston.gov/).  
CityScore tracks the city's performance across key areas such as **public safety**, **operations**, **housing**, **transportation**, and **community engagement**.

The analysis focuses on:
- Identifying **trends and patterns** in city performance over time.  
- Comparing **performance between service categories**.  
- Examining **part-to-whole relationships**, such as completion rates and contribution proportions.

---

## 🎯 Objectives
1. **Access and Clean the Dataset:**  
   Load CityScore metrics from the Boston Open Data Portal, remove duplicates, and format timestamps.
2. **Analyze Amounts (Quantities):**  
   Explore total incidents, average CityScores, and monthly changes.
3. **Compare Across Time and Categories:**  
   Examine long-term performance trends and differences across metrics.
4. **Part-to-Whole Relationships:**  
   Visualize proportions of resolved vs. total requests and contributions of each sector to the overall CityScore.

---

## 🧠 Key Findings
- **Stable Performance:** Boston’s overall CityScore remains consistently above 1.0, indicating reliable city operations.
- **Rising Engagement:** *Library Users* metric shows a clear upward trend from 2022 onward, signaling greater community involvement.
- **Operational Reliability:** *Code Enforcement On-Time %* and *Signal Repair On-Time %* maintain steady, high scores (~1.2).
- **Variable Safety Metrics:** *Shootings (Trend)* fluctuates significantly, reflecting ongoing public safety challenges.
- **High Completion Rates:** Most services achieve **95–99% completion**, with *Trash Collection* and *311 Surveys* leading performance.

---

## 🧩 Visualizations
This project includes several visualization types:
- 📈 **Line Charts:** Trends and 3-month/12-month rolling averages for key metrics.  
- 📊 **Bar Charts:** Top 10 metrics by monthly score.  
- 🥧 **Stacked & 100% Stacked Bars:** Proportion of resolved vs. remaining service requests.  
- 🌈 **Multi-Line Comparison Charts:** Performance across categories over time.

---

## 🛠️ Tools & Libraries
- **Python 3.12+**
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Data Source:** [CityScore Metrics – Boston Open Data Portal](https://data.boston.gov/dataset/cityscore)

---

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/boston-cityscore-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook Bostoncityscore_analysis.ipynb
   ```
4. View generated charts in the inside the notebook.

---

## 📘 Questions Addressed
1. **Trends or patterns observed in CityScore metrics**  
2. **Comparison of city performance across time and categories**  
3. **Part-to-whole proportions and contributions**

---

## 🏁 Conclusion
The City of Boston demonstrates **consistent service performance**, **increasing public engagement**, and **areas for targeted improvement** in safety and maintenance.  
These findings help guide data-driven decisions for better city management and public accountability.

---

## 👨‍💻 Author
Sanjana Patnam  
📧 patnamsanjana128@gmail.com  
🔗 [LinkedIn](www.linkedin.com/in/sanjana-patnam-82a338347)