# Pandas Data Analyst Tasks

A set of real-world data science tasks completed using the Python **Pandas** library.

## 📂 Setup

To access all of the files, you can either:

1. **Download ZIP**  
   - Click the green **"Code"** button.  
   - Select **"Download ZIP"**.  
   - Extract all files to your desired location.

### Install Requirements

- **Jupyter Notebook** → [Installation Guide](https://jupyter.readthedocs.io/en/latest/install.html)  
- **Pandas** → [Installation Guide](https://pandas.pydata.org/pandas-docs/stable/install.html)

---

## 📜 Background Information

This repo is part of the project **"Solving Real-World Data Analyst Problems with Python Pandas!"**.

In this project, we use **Python Pandas** & **Matplotlib** to analyze and answer business questions about **12 months of sales data**.  
The dataset contains hundreds of thousands of electronics store purchases, broken down by month, product type, cost, purchase address, etc.

---

## 🧹 Data Cleaning Tasks

- Drop NaN values from the DataFrame.  
- Remove rows based on a condition.  
- Change column types (`to_numeric`, `to_datetime`, `astype`).  

---

## 🔍 Data Exploration Questions

We answer **4 high-level business questions**:

1. **What was the best month for sales?** How much was earned that month?  
2. **Which city sold the most products?**  
3. **What time should we display advertisements** to maximize customer purchases?  
4. **What products are most often sold together?**  


---

## 🛠 Methods & Techniques Used

- Concatenating multiple CSVs into a single DataFrame (`pd.concat`).  
- Adding new calculated columns.  
- Parsing strings to create new columns (`.str`).  
- Using `.apply()` for custom logic.  
- Using `groupby` for aggregate analysis.  
- Plotting bar charts and line graphs with Matplotlib.  
- Adding titles and labels to graphs.

---

## 📊 Visualization

We use **Matplotlib** to create bar charts and line graphs to help visualize insights from the sales data.

---

## 🎯 Goal

The goal is to demonstrate how to **clean, process, and analyze real-world datasets** using Python Pandas and then visualize the results to answer meaningful business questions.
