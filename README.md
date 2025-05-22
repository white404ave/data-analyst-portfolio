# AI Developer Productivity Dashboard
This portfolio project visualizes how AI usage, cognitive load, and rest affect software development outcomes using real-world inspired data.

📊 About the Dataset
The dataset explores three key relationships:

AI Usage vs. Code Commits – How increased use of AI tools correlates with developer output.

Sleep Hours vs. Bugs Reported – Investigating whether rest impacts the number of bugs introduced.

Cognitive Load vs. Task Success – A scatter plot of mental load against task completion success rate.

Data fields include:

ai_usage_hours

commits

sleep_hours

bugs_reported

cognitive_load

task_success

🔗 Live Data Integration
This dashboard uses live CSV data hosted on Google Sheets, connected via the PapaParse library.

The spreadsheet is published and accessible as a CSV:
Google Sheets CSV

Charts are rendered using Chart.js.

🚀 How It Works
Papa.parse fetches and parses the CSV from Google Sheets.

Data is mapped into three different charts:

Bar Chart: AI usage hours and commits.

Line Chart: Sleep hours vs. bugs reported.

Scatter Plot: Cognitive load vs. task success.

All charts update automatically from the live dataset.

👨‍💻 Author
John White
Data Analyst – Python • SQL • Tableau
