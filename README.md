# Basic-Sales-Summary-using-Python-and-SQLite
This task demonstrates how to use Python to connect to a SQLite database, run SQL queries, and visualize basic sales metrics like total quantity sold and revenue per product.

## 🛠️ Tools Used
- Python
- SQLite (`sqlite3`)
- Pandas
- Matplotlib
- Jupyter Notebook

## 📂 Files Included
- `sales_data.db` – SQLite database containing sample sales data
- `task7_sales_summary.ipynb` – Jupyter Notebook with full code
- `sales_chart.png` – Bar chart showing revenue by product
- `sales_summary.csv` – (Optional) CSV export of the summary

## 📊 Steps Performed
1. Created a SQLite database (`sales_data.db`) and a `sales` table with columns: `product`, `quantity`, and `price`.
2. Inserted sample sales records for multiple products.
3. Executed SQL query to calculate:
   - Total quantity sold per product
   - Total revenue per product (`SUM(quantity * price)`)
4. Loaded query results into a pandas DataFrame.
5. Printed the summary table.
6. Visualized revenue using a bar chart with matplotlib.

## 📈 Output
- A printed summary of sales by product
- A bar chart showing revenue distribution across products

## ✅ Result
Successfully extracted and visualized basic sales metrics using SQL inside Python.
