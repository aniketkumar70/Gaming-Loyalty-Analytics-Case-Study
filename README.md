# Gaming Loyalty Analytics Case Study

---

## Overview

This repository demonstrates an end-to-end analytics workflow for a real-money online gaming company, addressing player loyalty through thorough data processing, player scoring, ranking, and bonus allocation strategies. The solution leverages in-depth data engineering and business logic to calculate loyalty points, rank players, extract key KPIs, and critically evaluate loyalty program fairness.

---

## Problem Statement

- Analyze player activity and transactions to calculate and allocate loyalty points for a real-money gaming platform.
- Rank players monthly, compute bonus pool distributions, and make recommendations for a fair, data-driven loyalty system.
- Critique and improve on the platform's existing loyalty point formula and reward allocation structure.

---

## Repository Structure

| File/Folders                             | Description                                                      |
|------------------------------------------|------------------------------------------------------------------|
| `main.ipynb`                             | Main Jupyter notebook with full data analysis, loyalty logic, business answers, and visualizations |
| `Analytics-Position-Case-Study-Question.xlsx`   | Source case study and assignment brief (if used in input)        |
| `report.md`                              | Markdown summary of solution and key insights (this document)    |
| `data/`                                  | (Optional) Supplementary or sample transaction/activity logs     |

---

## Key Features

- **Player Loyalty Point Computation:**  
  - Automates loyalty scoring using deposits, withdrawals, and game activity per hour and time slot.
  - Loyalty formula applied for slot-wise, day-wise, and overall monthly scoring.

- **Player Leaderboard Generation:**  
  - Ranks all players by monthly points and breaks ties using number of games played.
  - Highlights top 50 reward-eligible players with loyalty split calculations.

- **Bonus Pool Allocation Strategies:**  
  - Implements: Equal Split, Proportional to Loyalty, and Tier-Based Distribution, each with full payout breakdowns to the top 50 players.
  - Analyzes impact and fairness of each strategy for both incentivizing and retaining engaged users.

- **KPI & Behavioral Analytics:**  
  - Computes average deposit amount, per-user financial averages, and average play frequency.
  - Delivers multi-faceted usage and engagement reporting, revealing high-value behavioral patterns.

- **Critical Assessment of Loyalty Formula:**  
  - Decomposes the loyalty calculation into contributions (deposit, withdrawal, games).
  - Evaluates proportionality, assesses fairness to player profiles, and offers actionable recommendations.

- **Visualization & Reporting:**  
  - Produces slot- and day-specific leaderboards, monthly summaries, and visual trends for easy review.
  - Contains well-organized, annotated code with stepwise narrative explanations.

---

## How to Run

1. **Clone this repository or download files.**
2. Place the required Excel file (if available) in the workspace.
3. Open `main.ipynb` in Jupyter, Colab, or VS Code.
4. Run cells sequentially for:
    - Data load and cleaning
    - Loyalty computation
    - Leaderboard ranking
    - Bonus allocation simulation
    - KPI and formula critiques
    - Visual analysis
5. Review inline conclusions, tables, and plots for actionable answers.

---

## Outputs & Insights

- **Player Loyalty Points:** Computed per slot, day, and overall—demonstrated with sample leaderboards.
- **Monthly Rankings:** Detailed list of top players, including tie-breakers and leaderboard reasoning.
- **Bonus Distribution:** Clear payout tables for equal, proportional, and tiered systems, showing incentive impact.
- **Key KPIs:** 
    - Average deposit amount (global and per-user)
    - Average games played per user
- **Formula Analysis:** Percentage contribution of deposits, withdrawals, and games. Fairness commentary and improvement proposals.
- **Visualizations:** Trends of activity, deposits, withdrawals, and loyalty distribution (sample charts included).

---

## Dependencies

- Python 3.x
- pandas, numpy
- openpyxl (for Excel file I/O)
- matplotlib or plotly (for visualizations, as applied)
- Jupyter Notebook


---

## Recommendations & Extensions

- **Incentive Structure:** Consider emphasizing games played or long-term play streaks to drive daily engagement, not just raw deposits.
- **Formula Adjustments:** Rebalance loyalty weights to better reward “active” (game-playing) users vs. only depositors.
- **Data-Driven Tiers:** Explore further segmentation (e.g., recency, frequency, monetary) to refine rewards and churn prevention.
- **Dashboarding:** Build a dashboard for ongoing loyalty, bonus, and user segmentation tracking.

---


