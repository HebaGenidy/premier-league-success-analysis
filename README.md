# Premier League 2023/24 — What Actually Drives Success?

## Project Overview

This project investigates whether scoring goals alone is enough to explain success in the Premier League, or whether defensive performance plays an equally important role.

Using data from the 2023/24 Premier League season, I analyzed the relationship between:

* Goals Scored
* Goals Conceded
* Total Points Earned

The objective was to determine which factor is more strongly associated with league success.

---

## Research Question

Does scoring more goals lead to a higher points total in the Premier League, or is defensive performance equally important in determining success?

**Hypothesis:** Goals scored will have a stronger relationship with points than goals conceded.

---

## Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Methodology

1. Collected Premier League 2023/24 team statistics.
2. Selected key performance indicators:

   * Goals Scored
   * Goals Conceded
   * Points
3. Calculated Pearson correlation coefficients.
4. Visualized relationships using scatter plots.
5. Compared attacking and defensive metrics to evaluate their impact on league performance.

---

## Key Findings

* Goals scored showed a very strong positive correlation with points (**r = 0.91**).
* Goals conceded showed a strong negative correlation with points (**r = -0.75**).
* Newcastle scored **85 goals**, more than Chelsea, Tottenham, and Aston Villa, but finished below all three teams.
* This suggests that while attacking performance is the stronger predictor of success, defensive solidity remains an important factor in achieving a high league position.

---

## Limitations

* The analysis includes only 10 teams, limiting generalization to the entire league.
* The dataset covers only the 2023/24 season.
* Other important variables such as Expected Goals (xG), squad value, and injury rates were not included.
* Future analysis using multiple seasons and additional metrics could provide a more complete picture of football success.

---

## Future Improvements

Possible extensions of this project include:

* Analyzing multiple Premier League seasons.
* Including Expected Goals (xG) and Expected Goals Against (xGA).
* Examining squad value and wage expenditure.
* Investigating the impact of injuries on team performance.
* Building predictive models for league points and final position.

---

## Author

**Heba Mohamed Sayed**

Data Analysis Project | Python • Pandas • Matplotlib
