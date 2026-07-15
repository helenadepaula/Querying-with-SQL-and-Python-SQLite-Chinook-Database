# Chinook Music Store Data Analysis with SQL and Python

## About the project
This is a hands-on Data Analysis project focused on the integration between **Python** and **Relational Databases**. The idea was taken from Roadmap.sh, where you can find many Project ideas for developing Data Analysis skills.

Using the **Chinook** sample database (which simulates a digital music store), the goal was to write SQL queries directly from a Jupyter Notebook to explore the data, extract relevant business metrics and create graphical visualizations of the findings.

## Technologies used
* **Python**
* **SQLite3** (for connection and direct queries to the database file)
* **Pandas** (to transform SQL query results into structured DataFrames)
* **Matplotlib** (for data visualization and charting)
* **Jupyter Notebook** (development environment)

## Business questions answered
During the analysis, the following questions were explored and answered using `JOIN`s, `GROUP BY`, and SQL aggregation functions:
1. **Which are the 10 best-selling tracks?** *(Visualized with a horizontal bar chart)*
2. **Which country generates the most revenue?** *(Visualized with a bar chart)*
3. **Who is the top-performing sales employee?** *(Visualized with a pie chart)*

Additionally, the project includes a Python automation that scans the database using the `PRAGMA foreign_key_list` command to automatically map the Database Schema.