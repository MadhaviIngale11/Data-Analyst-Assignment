# Data-Analyst-Assignment
## Q1 – CRUD Operations in Python
File: Sale q1.ipynb

Objective
Implement basic CRUD (Create, Read, Update, Delete) operations in Python using Pandas and CSV file handling.

Technologies/Libraries Used
Python 3.x

Pandas

How It Works
Create: Add new records to a CSV file.

Read: Load and display data from the CSV file.

Update: Modify existing records based on a given condition.

Delete: Remove specific records from the dataset.

Steps to Run
Open the Jupyter Notebook: Sale q1.ipynb.

Run all cells in sequence.

Follow prompts (if any) to test each CRUD function.

Expected Output
The CSV file updates according to CRUD operations performed.

The notebook prints before/after states of the dataset.

## Q2 – Sales Forecasting
File: Sales Q2.ipynb

Objective
Analyze sales data and forecast future sales using time series models.

Technologies/Libraries Used
Python 3.x

Pandas

Matplotlib

Statsmodels (SARIMA)

(Optional) Scikit-learn / Prophet for alternative models

How It Works
Load and clean sales data from CSV.

Group data by month and year for trend analysis.

Visualize historical sales trends.

Apply ARIMA model to forecast future sales.

Plot forecasted results alongside actual data.

Steps to Run
Open Sales Q2.ipynb.

Install dependencies if needed:

bash
Copy code
pip install pandas matplotlib statsmodels
Run all cells to see analysis and forecasts.

Expected Output
Plots of monthly/yearly sales trends.

Forecasted sales chart for future periods.

Printed forecast values in a table.

## Q4 – Web Scraping Product Details (Flipkart + Croma)
File: q4.ipynb

Objective
Scrape product details (Name, Price, Rating) from Flipkart and Croma for a user-given search term, then save results to Excel.

Technologies/Libraries Used
Python 3.x

Selenium

Pandas

WebDriver Manager

OpenPyXL

How It Works
Takes a product name from the user (input()).

Opens Flipkart and Croma in Chrome using Selenium.

Waits for search results to load.

Extracts product name, price, and rating.

Saves all data to an Excel file named <product>_products.xlsx.

Steps to Run
Install dependencies:

bash
Copy code
pip install selenium pandas openpyxl webdriver-manager
Run the notebook.

Enter the product name when prompted.

Wait for scraping to finish; Excel file is saved in the working directory.

Expected Output
Excel file containing product details from both Flipkart and Croma.

Console preview of first 5 results.
