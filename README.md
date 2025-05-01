# 📊 Basic Sales Summary using SQLite, Python, Pandas & Matplotlib

This project demonstrates how to build a simple sales analytics tool using Python. It connects to a SQLite database, retrieves sales data via SQL, and visualizes results using Pandas and Matplotlib.

---

## 📁 Project Structure

- 'sales_data': SQLite database file containing sample sales records.
- 'SQLite db python query': Main script that runs the entire process.


---

## 🚀 Features

- Creates and manages a SQLite database with a `sales` table.
- Inserts sample sales data (product, quantity, price).
- Uses SQL to calculate total quantity sold and revenue per product.
- Displays results using Pandas and visualizes them with a bar chart using Matplotlib.

---

## 🛠️ Requirements

- Python 3.x
- Pandas
- Matplotlib

## 🧠 How It Works
Connects to local SQLite database.

Defines and populates a table named sales.

Executes a SQL query to group data by product and summarize quantity and revenue.

Loads the result into a Pandas DataFrame.

Prints the summary and plots a bar chart showing revenue per product.

## 📈 Example Output
A printed summary table showing each product, total quantity sold, and total revenue.

![Screenshot 2025-05-01 120001](https://github.com/user-attachments/assets/569bffe5-885b-41ac-be7a-e6ae477bc553)


A bar chart with product names on the X-axis and revenue on the Y-axis.
![Screenshot 2025-05-01 120018](https://github.com/user-attachments/assets/473c1447-3c3a-4e25-bd65-79fdcffee37d)
