NHL Injuries Analysis (2020–2023)
This project explores the rise in upper body injuries in the NHL, focusing on the seasons before, during, and after COVID schedule changes. The main question addressed:
Why was there such an increase in upper body injuries from the 2020 season to the 2021 season?
📊 Data & Tools
Data Source: NHL injury data (2020–2023 seasons)
Tools:
Jupyter Notebook (Python, Pandas, Matplotlib, SciPy)
Tableau (for interactive visualization)
Outputs:
Processed CSV for Tableau: data/nhl_injuries_data.csv
Notebook: notebook/nhl_injuries_analysis.ipynb
Tableau Dashboard: tableau/nhl_injuries_viz.twbx
🔍 Key Findings
Injury Spike After COVID
Comparing pre-COVID seasons to the return of the full 82-game schedule, injuries rose sharply.
Upper body injuries increased 32.99% from 2020 → 2021.
Lower body injuries increased 27.92% over the same period.
Possible Factors Behind the Increase
Rule Change: Stricter enforcement of Rule 59 (Cross-Checking) in 2021–22.
Instead of using sticks, players may have relied more on shoulder-to-shoulder contact, potentially raising upper body injuries.
Full Season Return: After shortened COVID seasons (~56 games), the 2021–22 return to 82 games likely contributed to higher cumulative injuries.
Game Speed: Increased pace and physicality of modern NHL play.
No Major Equipment/Ice Changes: Boards, ice, and digital dasherboards did not materially affect 2021 season injury rates.
Rule Change vs. Injuries
Despite speculation, statistical analysis (t-test) did not show a significant correlation between cross-checking rule enforcement and upper body injuries.
However, observational evidence suggests the style of contact shifted, which may explain the rise.
📈 Visual Insights
Interactive Tableau dashboards compare:
Injuries by body part across seasons.
Correlation between hits delivered and injuries recorded.
Pre- and post-rule change seasons.
To explore the dashboard:
Open tableau/nhl_injuries_viz.twbx in Tableau Desktop.
Load processed CSV from data/nhl_injuries_data.csv if needed.
🏒 Conclusion
The return to a full season after COVID, combined with rule enforcement changes, most likely explains the sharp rise in upper body injuries.
The effect seems multifactorial, not tied to a single cause.
While statistical evidence for a direct correlation is limited, trend analysis and percentage increases support the theory.
