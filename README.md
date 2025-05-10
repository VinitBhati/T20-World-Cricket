# 🏏 Player Analysis Dashboard – T20 World Cup  <br>
<br>
📌 Project Overview<br>
This Power BI dashboard presents a comparative analysis of top power hitters and openers in the T20 World Cup (Qualifier + Super 12 stages). The visualizations provide key performance metrics such as total runs, strike rate, boundary %, batting average, and more to help in team selection and performance comparison.<br>
<br>
🧰 Tools Used<br>
Power BI – for data modeling, visualization, and interactivity<br>
Microsoft Excel – for cleaning and structuring player data<br>
<br>
🧹 Data Cleaning (Excel)<br>
Before dashboard creation, the dataset underwent the following cleaning steps:<br>
Removed duplicates – Ensured no repeated entries for players or matches.<br>
Handled missing values – Replaced null values with appropriate placeholders (e.g., 0 or "Not Available").<br>
Converted data types – Standardized numeric columns (e.g., Runs, Balls Faced) and formatted text (e.g., Team, Batting Style).<br><br>
Created calculated metrics, including:<br>
Strike Rate = (Runs / Balls Faced) * 100<br>
Boundary % = (Boundaries / Balls Faced) * 100<br>
Batting Average = Runs / Innings Played (for players not out, handled as per cricket rules)<br>
<br>
📈 Dashboard Features<br>
🔹 Tabs and Filters:<br>
Player Categories: Power Hitters, Anchors, Finishers, All-Rounders, Specialist Fast Bowlers<br>
Match Stage Toggle: Qualifier / Super 12<br>
<br>
🔹 Top Section (Bar Table):<br>
Metric	Example (Jos Buttler)<br>
Name	Jos Buttler<br>
Team	England<br>
Batting Style	Right-hand Bat<br>
Innings Batted	6<br>
Runs	225<br>
Balls Faced	156<br>
Strike Rate	144.23<br>
Batting Average	45.00<br>
Boundary %	61.33%<br>
Batting Position	1<br>
<br>
🔹 Line Graphs (Bottom Left):<br>
Batting Average vs. Players<br>
Average Balls Faced per Innings<br>
Strike Rate Trend<br>
Boundary % Comparison<br>
<br>
🔹 Bubble Chart (Bottom Right):<br>
X-Axis: Batting Average<br>
Y-Axis: Strike Rate<br>
Bubble Size: Run Contribution<br>
Insightful comparison between high-strike players (e.g., Rilee Rossouw) vs. stable anchors (e.g., Jos Buttler)<br>
<br>
🔍 Key Insights<br>
Jos Buttler leads with the highest batting average (45.0) and strong strike rate.<br>
Rilee Rossouw has the highest strike rate (169.88), making him a strong finisher.<br>
Quinton de Kock has the best boundary percentage (75.81%).<br>
Players like Kusal Mendis and Alex Hales show consistent performance but vary in aggression.


