# NBA Salary Allocation Analysis (2024–25)

### Author: Daniel Lenney  

---

## 📊 Overview
This project analyzes how NBA teams distribute their salary cap among their **top three highest-paid players** and how that spending concentration relates to **team success** in the 2024–25 season.  
The goal was to determine whether teams with **star-heavy payrolls** outperform or underperform compared to **more balanced rosters**.

---

## Key Findings
- **R² (Final Ranking Model):** 0.03  
- **R² (Ranking Change Model):** 0.21  
- **β(top3_share):** +33.91 (*p = 0.048*)  

*Teams that concentrated more payroll in their top players tended to slightly underperform preseason expectations.*  
While the effect was modest, results suggest that **depth and roster balance** may provide more consistent success than heavily top-loaded spending.

---

## Visualizations
**Payroll Concentration vs Final Power Ranking (2024–25)**  
*Lower ranking = better performance*  
![Final Ranking](NBA_Top3_Allocation_vs_Final_Ranking.png)  

**Payroll Concentration vs Change in Power Ranking (2024–25)**  
*Negative values = improvement vs preseason expectations*  
![Ranking Change](NBA_Top3_Allocation_vs_Ranking_Change.png)  

---

## Files
| File | Description |
|------|--------------|
| `NBA Top 3 Salary Allocation.Rmd` | R Markdown analysis |
| `NBA-Top-3-Salary-Allocation.pdf` | Final report |
| `NBA Salary Cap Data - 24-25 Salaries.csv` | Source dataset |
| `NBA_Top3_Allocation_vs_Final_Ranking.png` | Visualization: payroll vs final ranking |
| `NBA_Top3_Allocation_vs_Ranking_Change.png` | Visualization: payroll vs ranking change |

---

### Summary
This project shows that **star-heavy spending does not guarantee success** in the NBA.  
Teams that invested more evenly across their roster tended to meet or exceed expectations — proving that **balance often beats concentration**.
