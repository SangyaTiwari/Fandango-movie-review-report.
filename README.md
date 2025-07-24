🎬 Fandango's Movie Review Report
 Project Overview
This project is part of a guided investigation into whether **Fandango**, a popular movie ratings aggregator, was inflating its displayed ratings compared to the actual ratings stored in their system.  
In 2015, data journalist Walt Hickey revealed discrepancies between Fandango’s displayed star ratings and the true ratings found in the page HTML.  
The goal of this project was to:
- Confirm the inflation using 2015 data.
- Compare results with 2016–17 data to check if Fandango adjusted its rating system after the public investigation.

---
  Datasets
- fandango_score_comparison.csv – Ratings from 2015 (both displayed and true values).
- movie_ratings_16_17.csv – Ratings from 2016–17 (displayed values).

---

  Tools & Libraries
- **Python**
- **Jupyter Notebook**
- **Pandas** for data manipulation
- **Matplotlib & Seaborn** for visualization

---

 Key Findings
| Metric | 2015 Displayed | 2015 True | 2016–17 Displayed |
|--------|----------------|-----------|-------------------|
| Mean   | 4.10           | 3.90      | 3.90              |

✅ **2015:** Displayed ratings were consistently higher than true ratings, confirming inflation.  
✅ **2016–17:** Displayed ratings aligned closely with the previous true ratings, suggesting Fandango adjusted its system.

---
 Visualizations
The project includes:
- Frequency distribution plots comparing displayed vs true ratings.
- Line plots showing shifts in distributions from 2015 to 2016–17.
- Bar charts summarizing mean ratings across datasets.
