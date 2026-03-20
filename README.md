
---

# Experiment 11: Create Data Set and Load Data Set In Pandas Library

---

### Aim: Create Data Set and Load Data Set In Pandas Library

---

### Theory

The **Pandas** library is a powerful open-source tool built on top of the Python programming language for data manipulation and analysis. It provides high-performance data structures, primarily the **DataFrame**, which organizes data into a 2D labeled tabular structure similar to an Excel spreadsheet or SQL table.

In this experiment, we explore two primary methods of data handling: manual creation of a dataset using Python dictionaries and loading external data from a **CSV (Comma Separated Values)** file. The experiment also covers **Exploratory Data Analysis (EDA)**, which is the process of using statistical summaries and structural attributes to understand the dataset's characteristics, identify missing values (nulls), and detect duplicate entries before performing deeper analysis.

---

### Command Descriptions

The following Pandas and structural commands were used to manage and inspect the datasets:

| Command | One-Line Description |
| :--- | :--- |
| `pd.DataFrame(data)` | Converts a Python dictionary into a structured tabular DataFrame. |
| `df.to_csv("file.csv")` | Exports the DataFrame to a CSV file that can be opened in Excel. |
| `df.shape` | Returns a tuple representing the number of rows and columns in the DataFrame. |
| `df.size` | Calculates the total number of elements (cells) present in the entire dataset. |
| `df.info()` | Displays metadata including data types, memory usage, and non-null counts. |
| `df.describe()` | Generates a statistical summary (mean, std, min, max, quartiles) for numerical columns. |
| `pd.read_csv('path')` | Loads an external CSV file into a Pandas DataFrame for analysis. |
| `df.head()` | Returns the first five rows of the dataset for a quick preview. |
| `df.tail()` | Returns the last five rows of the dataset to check the end of the file. |
| `df.sample(n)` | Selects a specified number of random rows from the DataFrame. |
| `df.isnull().sum()` | Identifies missing values by returning the total count of null entries per column. |
| `df.duplicated().sum()` | Checks the entire dataset for identical rows and returns the total number of duplicates. |
| `df.nunique()` | Returns the count of unique (distinct) values present in each column. |

---

### Functions and Logic Used

#### Structural Analysis
* **Dimension Checking:** Using `.shape` and `.size` to understand the scale of the data.
* **Metadata Review:** Using `.info()` to ensure data types (integers, floats, objects) are correctly assigned.

#### Statistical Logic
* **Descriptive Statistics:** Applying `.describe()` to find the central tendency and spread of numerical data like Price or CGPA.
* **Quartile Analysis:** Using the 25%, 50%, and 75% markers to identify data distribution and potential outliers.

#### Data Quality Checking
* **Null Identification:** Summing null values to see where data might be missing (e.g., the AirBags column).
* **Uniqueness:** Using `.nunique()` to see the variety of data, such as how many different Manufacturers are in the list.

---

### Conclusion

Through this experiment, I successfully learned how to create and export custom datasets and how to load large external files for processing. The experiment demonstrated that structural commands and statistical summaries are vital for getting a "bird's-eye view" of any dataset. Mastering these Pandas basics provides the necessary foundation for advanced data cleaning and machine learning tasks.

---

