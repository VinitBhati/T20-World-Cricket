# 🏏 Player Analysis Dashboard – T20 World Cup  <br>
<br>
📌 Project Overview<br>
This Power BI dashboard presents a comparative analysis of top power hitters and openers in the T20 World Cup (Qualifier + Super 12 stages). The visualizations provide key performance metrics such as total runs, strike rate, boundary %, batting average, and more to help in team selection and performance comparison.<br>
<br>
🧰 Tools Used<br>
Python - for cleaning and structuring player data by pandas<br>
Jupyter-Notebook - for cleaning <br>
Power BI – for data modeling, visualization, and interactivity<br>
<br>
📂 Data Source<br>
The dataset was originally in JSON format and was converted to CSV using Python and Pandas for easier data manipulation and visualization.<br>
<br>
🧹 Data Cleaning (in Jupyter Notebook)<br>
Parsed JSON data into a structured DataFrame.<br>
Handled nested structures and flattened them for analysis.<br>
Removed null and inconsistent values.<br>
Converted data types (e.g., strings to integers/floats).<br>
Filtered relevant columns such as:<br>
Player Name, Team, Batting Style, Innings Batted<br>
Runs, Balls Faced, Strike Rate, Batting Average, Batting Position, Boundary Percentage<br>
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


