# WNBA Betting Market Calibration (2024)

### Author: Daniel Lenney  

---

## 📊 Overview
This project analyzes the accuracy of sportsbook win probabilities in the 2024 and first half of the 2025 WNBA season.  
The goal was to test how well the market’s implied odds predicted actual game outcomes — essentially, whether betting markets are **well-calibrated**.

---

## 🧠 Key Findings
- **Calibration slope:** 0.61  
- **Intercept:** +0.37  
- **Brier score:** 0.199 (vs. 0.201 baseline)

🟢 *The WNBA betting market was largely accurate and efficient.*  
Favorites slightly outperformed their implied odds, suggesting a **small undervaluation of favorites**, though not statistically significant.

---

## 📈 Visualization
**Observed win rate vs. predicted probability (vig-normalized):**

![Reliability Diagram](wnba_calibration_plot.png)

---

## 📁 Files
| File | Description |
|------|--------------|
| `WNBA Betting Data.Rmd` | R Markdown analysis |
| `WNBA-Betting-Data.pdf` | Final report |
| `wnba_calibration_plot.png` | Calibration chart |
| `WNBA Rookie Impact II - CSV Export.csv` | Source dataset |

---

### 🏀 Summary
This project demonstrates that the WNBA betting market is highly well-calibrated, with only minor biases toward favorites.  
In other words — **the oddsmakers are good at their jobs.**
