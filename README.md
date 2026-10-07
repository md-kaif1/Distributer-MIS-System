# Distributer-MIS-System
1. One-line project summary
"MIS dashboard for a distributor business — tracks daily/weekly/monthly sales vs target across 6 cities and 8 salespeople, built entirely with Excel formulas (SUMIFS/COUNTIFS/INDEX-MATCH)."

2. Screenshots
This matters most. Take 2-3 screenshots of your actual dashboard (Daily MIS block, Weekly table, Insights section) and embed them in the README. This is the only way someone sees your work without downloading Excel.

3. What it does — short bullet list

Daily MIS: sales, orders, achievement %, pending orders, top salesperson for any selected date
Weekly MIS: 13-week rolling view with WoW growth
Monthly MIS: MTD, YTD, MoM growth with correct year-boundary reset
City/category breakdown with % contribution
Auto-generated business insights (formula-driven, not hardcoded)

4. Key technical decisions (this is the part that signals skill)
A short paragraph like:

"Used helper columns (Month_Key, Week_Key) derived from the date column so every rollup is a single SUMIFS rather than separate logic per time period. YTD resets correctly at year boundaries using an IF on the year prefix."

5. Tools used
Excel (formulas only, no VBA) — mention this explicitly since some reviewers assume "dashboard" means Power BI.

6. Data note
Say clearly it's your own practice dataset (or synthetic), so nobody questions whether it's a real company's data.

7. How to use it
"Open Distributor_Dashboard, change the date in the yellow cell (C6) to see that day's numbers update across the whole sheet."
