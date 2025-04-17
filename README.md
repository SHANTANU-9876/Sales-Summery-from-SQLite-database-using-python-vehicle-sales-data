# Sales-Summery-from-SQLite-database-using-python-vehicle-sales-data
This project analyzes car sales data from a CSV file using Python, pandas, matplotlib, and SQLite. It calculates and visualizes total revenue by car make. The process involves loading data, storing it in an SQLite database, querying the database for revenue aggregation, and presenting the results with charts.

Key Features:
- Data Loading: Uses pandas to efficiently load car sales data (make, model, selling price) from a CSV.
- SQLite Database: Creates and manages an SQLite database file to store the car sales data in a table.
- Revenue Calculation: Employs SQL queries within SQLite to calculate the total revenue for each car make.
- Data Visualization: Generates bar charts with matplotlib to visualize revenue by car make, highlighting top performers.
- Result Display: Presents the analysis results (DataFrame) clearly, often using tabulate for formatting.

Technologies Used:
- Python
- pandas
- matplotlib
- sqlite3 (built-in Python library)

Use Cases:
- Basic sales analysis
- Quickly summarizing revenue by manufacturer
- Educational demonstrations of data analysis with SQLite
