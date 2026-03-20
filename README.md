

---

# Experiment 11: Create Data Set and Load Data Set In Pandas Library

---

### Aim: Create Data Set and Load Data Set In Pandas Library

---

### Theory

The **Pandas** library is the primary tool in Python for data manipulation and analysis. It provides high-performance data structures like **DataFrames**, which allow users to handle labeled data similarly to SQL tables or Excel spreadsheets.

In this experiment, two methods of data handling were implemented: manual creation using Python dictionaries and automated loading from external CSV files. The study also highlights the importance of **EDA (Exploratory Data Analysis)**, which involves checking for null values, duplicates, and statistical trends to understand the quality and distribution of data before further processing.

---

### Functions and Logic Used

#### Functions Used

* `pd.DataFrame()` – Converts dictionaries or lists into a structured table.
  
* `pd.read_csv()` – Loads data from external comma-separated values (CSV) files.
 
* `.to_csv()` – Exports a DataFrame to a local file for storage or external use.
  
* `.head()` / `.tail()` – Displays the first or last 5 rows of the dataset for a quick preview.
  
* `.sample()` – Displays a random set of rows from the DataFrame.
  
* `.describe()` – Provides a statistical summary (mean, std, min, max) of numerical data.
  
* `.info()` – Displays a summary of the DataFrame including index, data types, and non-null counts.

---

#### Logic and Attributes Used

* **Structural Attributes:** `.shape` is used to find the number of rows and columns, while `.size` gives the total number of elements.
  
* **Data Integrity:** `.isnull().sum()` is used to identify and count missing values, and `.duplicated().sum()` identifies repeated rows.
  
* **Summary Logic:** `.nunique()` is used to count distinct entries in each column, which helps in understanding data diversity.

---

### Conclusion

Through this experiment, the process of creating and managing datasets using the Pandas library was successfully studied. The experiment demonstrated how to convert raw Python data into structured formats and how to load large external datasets for analysis. Mastering these Pandas functions is an essential first step for any data science or machine learning workflow.

---

