# elevatelabs_Task_3
Objective: Design an interactive dashboard for business stakeholders.


🪄 How I Made This Dashboard-

Got the data

I went to Kaggle and downloaded Apple’s financial dataset (2009–2024).

The file was in CSV format, which is like a giant Excel sheet.

Put data into Tableau

I opened Tableau Desktop and connected it to the CSV file.

Tableau showed me all the columns (like Revenue, Profit, Margin, Debt, etc.).

Cleaned numbers

Some values had symbols like $ and % that Tableau couldn’t calculate with.

I created new “calculated fields” to turn them into pure numbers.

Example: Removed % from Gross Margin and converted it into decimal form (like 0.46).

Made KPI cards

I built big number boxes (called cards in Tableau).

These cards show important metrics at a glance → Revenue, Net Income, EBITDA, EPS, Employees.

This helps stakeholders quickly see the most important results.

Drew line charts

I made line charts for Revenue, Net Income, and Gross Margin over time.

This shows the trend (going up or down) across years.

Example: Revenue grew strongly around 2020, but slowed in recent years.

Added growth bars

I calculated YoY (Year-over-Year) growth % for Revenue and Net Income.

Then I made bar charts to compare which years had strong growth vs weak growth.

Example: 2020 had a big jump in revenue (+15.7%), but 2023–24 slowed to ~+2%.

Joined everything into a dashboard

I arranged the KPI cards, line charts, and bar charts onto one dashboard page.

This made it look like a control panel where everything is in one place.

I applied the same color theme (blue/green shades) for a clean and professional look.

Made it interactive

I added a “Year” filter so users can choose which year they want to focus on.

For example, clicking 2020 will highlight all metrics and charts for that year.

This makes the dashboard more useful for stakeholders.

Shared insights

I looked at the numbers and wrote the key takeaways:

Revenue hit $391B in 2024 (+2% YoY).

Net Income dropped slightly (–3% YoY).

EBITDA reached the highest ever at $135B.

Gross Margin stayed strong at 46.2%.

Debt went down, which is a good sign for stability.

These insights help business people make smarter decisions.
