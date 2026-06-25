# 🧹 Automated Data Cleaning & Reporting using Python

## 📌 Project Overview

Data quality is one of the most important aspects of any data analytics or machine learning workflow. Raw datasets often contain missing values, duplicate records, inconsistent formatting, and unnecessary columns that can negatively impact analysis and model performance.

This project demonstrates an **automated data cleaning and reporting pipeline** built using **Python** and **Pandas**. The system automatically cleans raw datasets, generates summary reports, exports a cleaned dataset, and creates visual summaries, significantly reducing manual preprocessing effort.

The objective is to build a reusable automation workflow that can be applied to real-world datasets with minimal user intervention.

---

# 🎯 Objectives

* Automate the data cleaning process using Python.
* Identify and handle missing values.
* Detect and remove duplicate records.
* Remove unnecessary columns.
* Standardize inconsistent categorical data.
* Generate automated reports summarizing the cleaning process.
* Produce visual summaries for better understanding of the dataset.
* Export the cleaned dataset for further analysis.

---

# 📂 Dataset

## Dataset Used

Titanic Passenger Dataset (Train & Test Combined)

The dataset contains demographic and travel information for passengers aboard the Titanic.

### Features Include

* Passenger ID
* Name
* Gender
* Age
* Ticket Information
* Cabin
* Fare
* Embarkation Port
* Passenger Class
* Survival Status
* Family Information

The dataset contains both numerical and categorical variables, making it ideal for demonstrating automated preprocessing techniques.

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* VS Code / Jupyter Notebook

---

# 🔄 Project Workflow

## 1. Data Loading

The raw CSV dataset is imported into Python using Pandas for further processing.

---

## 2. Data Exploration

Before cleaning, the dataset is analyzed to understand its structure.

The automated inspection includes:

* Dataset dimensions
* Data types
* Missing values
* Duplicate records
* Statistical summary

---

## 3. Automated Data Cleaning

The cleaning pipeline performs the following tasks automatically:

### Duplicate Removal

Duplicate records are detected and removed.

### Missing Value Handling

Numerical columns:

* Missing values are replaced using the **median**.

Categorical columns:

* Missing values are replaced using the **mode**.

### Unnecessary Column Removal

Columns containing redundant or placeholder values (such as multiple "zero" columns) are automatically identified and removed.

### Text Standardization

Categorical text values are standardized by removing leading and trailing spaces.

---

# 📊 Automated Reporting

After preprocessing, the system automatically generates a comprehensive cleaning report including:

* Original dataset dimensions
* Cleaned dataset dimensions
* Number of rows removed
* Number of columns removed
* Remaining missing values
* Remaining duplicate records
* Cleaning operations performed

The report is automatically saved as:

```text
cleaning_report.txt
```

---

# 📈 Visual Reports

The project automatically generates several visual summaries to provide insights into the cleaned dataset.

### Missing Value Heatmap

Visual comparison of missing values before and after cleaning.

### Correlation Heatmap

Displays relationships between numerical variables.

### Age Distribution

Shows the distribution of passenger ages.

### Fare Distribution

Visualizes fare spread and potential outliers.

### Survival Distribution

Illustrates the count of survived and non-survived passengers.

---

# ⚙️ Automation Features

The project uses a reusable cleaning function that performs multiple preprocessing steps automatically.

### Automated Tasks

✔ Remove duplicate records

✔ Remove unnecessary columns

✔ Handle missing numerical values

✔ Handle missing categorical values

✔ Standardize text formatting

✔ Export cleaned dataset

✔ Generate automated reports

✔ Produce visual summaries

This modular approach allows the same function to be adapted for different datasets with minimal changes.

---

# 📁 Project Structure

```text
Data-Cleaning-Automation/
│
├── data_cleaning.ipynb
├── train_and_test2.csv
├── cleaned_dataset.csv
├── cleaning_report.txt
├── README.md
│
└── screenshots/
    ├── missing_values_before.png
    ├── missing_values_after.png
    ├── correlation_heatmap.png
    ├── age_distribution.png
    ├── fare_distribution.png
    └── survival_distribution.png
```

---

# 📊 Output Files

The automation pipeline generates the following outputs:

| File                | Description                              |
| ------------------- | ---------------------------------------- |
| cleaned_dataset.csv | Cleaned dataset ready for analysis       |
| cleaning_report.txt | Automated summary of cleaning operations |
| PNG Images          | Visual summaries of the cleaned data     |

---

# 💡 Business Benefits

Automating data preprocessing provides several advantages:

* Reduces manual cleaning effort.
* Improves data quality and consistency.
* Saves time in analytics workflows.
* Produces standardized reports.
* Enables scalable preprocessing for larger datasets.
* Provides reusable code for future projects.

---

# 🚀 Future Enhancements

Possible improvements include:

* Interactive dashboard using Power BI or Streamlit.
* Automated PDF report generation.
* Outlier detection using machine learning techniques.
* Data validation rules for incoming datasets.
* Batch processing of multiple CSV files.
* Integration with cloud storage and databases.
* Scheduled execution for recurring data cleaning tasks.

---

# 📚 Key Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Data Quality Assessment
* Data Automation
* Python Programming
* Pandas
* NumPy
* Data Visualization
* Exploratory Data Analysis (EDA)
* Report Generation

---

# 📝 Conclusion

This project demonstrates how repetitive data preprocessing tasks can be fully automated using Python. By combining data cleaning, reporting, visualization, and export functionality into a single workflow, the solution provides a scalable foundation for real-world analytics and machine learning projects.

The automated pipeline ensures cleaner, more reliable datasets while reducing preprocessing time and improving overall workflow efficiency.

---

# 👨‍💻 Author

**Akshat Porwal**

B.Tech Information Technology | Aspiring Data Analyst

### Skills

* Python
* SQL
* Power BI
* Excel
* Data Cleaning
* Data Visualization
* Machine Learning
* Business Analytics

---

### ⭐ If you found this project helpful, consider giving the repository a star and feel free to connect with me on LinkedIn.
