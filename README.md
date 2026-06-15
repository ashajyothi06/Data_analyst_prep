# Data Analyst Interview Preparation

This repository contains a beginner-friendly **Data Analyst preparation notebook** focused on Python, Pandas, data cleaning, data analysis, joins, date handling, visualization, and common interview questions.

The main notebook is designed for students and freshers preparing for **Data Analyst internships, entry-level Data Analyst roles, and Python/Pandas interview rounds**.

---

## 📌 Project Overview

The notebook covers important Data Analyst concepts using simple examples and practical code.

You will learn how to:

- Create and read datasets using Pandas
- Inspect data using `head()`, `tail()`, `info()`, `describe()`, `shape`, and `columns`
- Select columns and filter rows
- Clean data by handling missing values and duplicates
- Rename columns and change data types
- Perform group-wise analysis using `groupby()`
- Apply multiple aggregations like sum, min, max, mean, and count
- Create new calculated columns
- Use lambda functions with Pandas
- Perform joins/merges: inner join, left join, right join, and outer join
- Work with date columns using `to_datetime()`
- Extract year, month, day, month name, and day name
- Filter and sort data by date
- Create basic visualizations using Matplotlib and Seaborn
- Understand `loc` vs `iloc`
- Find correlation between numerical columns
- Calculate attrition rate

---

## 📂 Repository Structure

```text
data-analyst-prep/
│
├── data_analyst_prep.ipynb   # Main Jupyter Notebook
├── employees.csv             # Sample CSV file used in the notebook
├── requirements.txt          # Python dependencies
├── .gitignore                # Files/folders ignored by Git
└── README.md                 # Project documentation
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🚀 How to Run This Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/data-analyst-prep.git
cd data-analyst-prep
```

### 2. Create a virtual environment

For Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

For macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

```bash
jupyter notebook
```

Then open:

```text
data_analyst_prep.ipynb
```

---

## 📊 Topics Covered

### 1. Pandas Basics

- Creating a DataFrame
- Reading CSV files
- Viewing first and last rows
- Checking dataset information
- Basic statistics
- Column selection
- Row filtering
- Sorting data

### 2. Data Cleaning

- Checking missing values
- Filling missing values with median
- Dropping missing rows
- Removing duplicates
- Renaming columns
- Changing data types

### 3. Data Analysis with Pandas

- Counting records
- Grouping by department
- Finding total salary by department
- Finding average salary by department
- Counting employees by department
- Multiple aggregations
- Filtering high salary records
- Creating annual salary column
- Categorizing salary using lambda

### 4. Joins and Merges

The notebook demonstrates:

- Inner Join
- Left Join
- Right Join
- Outer Join

These are important for both **Pandas interviews** and **SQL interview preparation**.

### 5. Date Handling

- Converting text dates into datetime format
- Extracting year, month, and day
- Extracting month name and day name
- Filtering records by date
- Sorting records by date
- Calculating days from today

### 6. Data Visualization

Basic charts are created using:

- Matplotlib
- Seaborn histogram
- Seaborn boxplot

### 7. Interview Concepts

The notebook also includes short examples for:

- Difference between `loc` and `iloc`
- Lambda function
- Correlation
- Attrition rate calculation

---

## 🧠 Important Interview Questions Covered

1. What is Pandas?
2. How do you read a CSV file in Pandas?
3. What is the use of `head()` and `tail()`?
4. How do you check missing values?
5. How do you fill missing values?
6. What is `groupby()` in Pandas?
7. How do you calculate average salary department-wise?
8. What is the difference between inner, left, right, and outer join?
9. How do you convert a column into date format?
10. How do you extract month and year from a date column?
11. What is the difference between `loc` and `iloc`?
12. What is a lambda function?
13. How do you find correlation?
14. How do you calculate attrition rate?

---

## ✅ Sample Use Cases

This notebook can be used for:

- Data Analyst interview preparation
- Python/Pandas revision
- Internship preparation
- Basic EDA practice
- Resume project learning
- College placement preparation

---

## 📈 Future Improvements

Planned improvements for this repository:

- Add SQL interview questions
- Add Excel interview questions
- Add Power BI/Tableau dashboard examples
- Add real-world sales dataset analysis
- Add end-to-end EDA project
- Add business KPI calculations

---

## 🙋‍♀️ Author

**Ashajyothi Velpula**

Data Analyst / Python / SQL / Excel / Power BI / Tableau Learner

---

## ⭐ Support

If this repository helps you, give it a star on GitHub.
