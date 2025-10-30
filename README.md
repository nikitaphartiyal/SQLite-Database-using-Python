🛍️ Sales Data Analysis & Visualization

This project analyzes and visualizes a Sales Dataset using Python, SQLAlchemy, and Matplotlib/Seaborn. It demonstrates database integration, data cleaning, SQL querying, and insight visualization — all in one workflow.

⚙️ Steps Overview

Load Data

Extracted from /content/salesforcourse-4fe2kehu.csv.zip

Uploaded to an SQLite database (sales_data.db)

Logged operations using logging module

SQL Operations

SELECT, GROUP BY, and DELETE queries via SQLAlchemy

Checked for NULLs and invalid data (Customer Age < 1)

Calculated total and category-wise revenue

Data Cleaning & EDA

Handled missing and invalid values

Computed age statistics (mean, median, mode)

Visualized major trends using charts

📊 Key Visualizations
Chart	Insight
Bar Plot	Revenue by Product Category
Pie/Donut Chart	Sub-Category Distribution
Gender-wise Bar Plot	Revenue by Customer Gender
Line Chart	Monthly Revenue Trend
Bar Plot (Top 10 States)	Highest Revenue States
Scatter Plot	Quantity vs Revenue
Histogram	Customer Age Distribution
🧠 Insights

Technology leads in total revenue.

Female customers slightly contribute more revenue.

Seasonal trend: revenue peaks in specific months.

Top states dominate overall sales.

Majority of customers are aged 30–40.

🧰 Tools & Libraries

Python, Pandas, NumPy, Matplotlib, Seaborn, SQLAlchemy, SQLite, Logging

▶️ How to Run
git clone https://github.com/nikitaphartiyal/SQLite Database using Python.git
cd SQLite Database using Python
pip install pandas numpy matplotlib seaborn sqlalchemy
python untitled5.py

📂 Output Files

🗄️ sales_data.db → SQLite Database

🧾 log_file.log → Process Logs

📈 Visuals → Displayed inline

✨ Future Improvements

Add interactive dashboards (Plotly / Power BI)

Include forecasting models for future revenue

Automate data refresh

👩‍💻 Author: Nikita
📊 Data Analyst | Python | SQL | Visualization
