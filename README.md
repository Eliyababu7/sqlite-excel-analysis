&nbsp;SQLite3 Data Analysis and Excel Visualization



&nbsp;📘 Project Overview

This project demonstrates how data can be imported from a CSV file into an SQLite3 database, analyzed using SQL queries, and visualized using Microsoft Excel. The goal is to transform raw data into meaningful insights through graphs and summaries.







&nbsp;🧰 Tools Used

&nbsp;	**SQLite3** – for database creation and queries  

&nbsp;	**Microsoft Excel** – for data visualization (charts, graphs)  

&nbsp;	**CSV files** – for data import/export between tools  





&nbsp;📂 Folder Structure

&nbsp;	sqlite-excel-analysis/

&nbsp;	┣ data/

&nbsp;	┃ ┗ input\_data.csv

&nbsp;	┣ results/

&nbsp;	┃ ┣ daily\_active\_users.xlsx

&nbsp;	┃ ┗ queries\_summary.txt

&nbsp;	┣ README.md

&nbsp;	┗ .gitignore







&nbsp;⚙️ Steps Performed

1\. Imported the CSV file into SQLite using:

&nbsp;  sql

&nbsp;  .mode csv

&nbsp;  .import data/input\_data.csv daily\_users

2\. Ran queries to verify and analyze the data:

&nbsp;	SELECT \* FROM daily\_users LIMIT 5;

&nbsp;	

3\. Exported the results and opened them in Excel.



4\. Adjusted the graph axes and formatting for clarity.



5\. Saved the Excel results in the /results folder.





📈 Outputs



&nbsp;	results/daily\_active\_users.xlsx → contains formatted charts and graphs.



&nbsp;	The “day” column represents date values (auto-formatted in Excel).



&nbsp;	The “dau” column represents Daily Active Users counts.

🧩 Future Improvements



&nbsp;	Automate export from SQLite to Excel using Python.



&nbsp;	Add trend analysis or forecasting.



&nbsp;	Include visuals (screenshots of charts) in README.
👤 Author



Eliya Babu Yallamelli

MSc Data Science \& Artificial Intelligence, University of Liverpool

LinkedIn Profile: https://www.linkedin.com/in/eliya-babu-705297137




