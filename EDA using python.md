1.Import Libraries
* Used pandas, numpy, matplotlib, and seaborn for data manipulation and visualization.

2. Load Dataset
* Loaded data.csv using latin-1 encoding.
* Configured pandas to display all columns for better inspection.

3. Initial Data Exploration
* Checked dataset shape, column names, and data types.
* Counted missing values for each column.
* Generated descriptive statistics for numerical and categorical columns.

4. Handle Missing Values
* Filled missing values in the Country column with "Unknown".

5. Data Visualization
* Monthly Sales Chart – Grouped sales by Month and plotted total sales as a bar chart.
* Country Sales Chart – Created a bar chart showing total sales per country.
* Displayed value counts of Country.
* Correlation Heatmap – Visualized correlations among numeric features.

6. Data Cleaning
* Dropped unnecessary column: InvoiceNo.
* Calculated mean and sum of UnitPrice grouped by Description.

7. Reload & Prepare for Further Analysis
* Reloaded the dataset to ensure all necessary columns (e.g., CustomerID) were available for subsequent steps.
