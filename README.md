# Restaurant Tips Analysis - Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Restaurant Tips dataset to understand the relationship between restaurant bills and tip amounts. 

The analysis focuses on identifying patterns between:
- Total bill amount and tip amount
- Customer behavior based on meal time
- Smoking preferences and their relationship with tipping behavior

The project demonstrates fundamental data analysis and visualization techniques using Python libraries such as Pandas, Matplotlib, and Seaborn.

---

# Business Problem / Objective

Restaurants want to better understand customer tipping behavior to improve service strategies and revenue insights.

The objective of this analysis is to:

- Analyze how total bill amount impacts tip amount.
- Identify trends in customer tipping behavior.
- Explore whether factors such as meal time and smoking status influence tips.
- Create visual insights that help understand customer spending patterns.

---

# Dataset

## Dataset Name:
**Restaurant Tips Dataset**

## Source:
The dataset is available through the Seaborn library (`sns.load_dataset("tips")`).

## Dataset Description:

The dataset contains restaurant transaction details including:

| Column | Description |
|--------|-------------|
| total_bill | Total restaurant bill amount |
| tip | Tip amount provided by customer |
| sex | Customer gender |
| smoker | Whether customer was a smoker |
| day | Day of restaurant visit |
| time | Meal time (Lunch/Dinner) |
| size | Number of people in the group |

## Dataset Size:
- Rows: 244
- Columns: 7

---

## Data Preparation

Steps performed:

- Imported required Python libraries.
- Loaded the dataset using Seaborn.
- Reviewed dataset structure using:
  - `head()`
  - Dataset inspection
  - Column analysis
- Prepared data for visualization.

## Technologies & Libraries Used

### Programming Language:
- Python

### Libraries:
- Pandas - Data manipulation and analysis
- Matplotlib - Data visualization
- Seaborn - Statistical visualization

### Development Environment:
- Anaconda Jupyter Notebook

---

# Exploratory Data Analysis (EDA)

The following exploratory analysis was performed:

## 1. Dataset Inspection

- Loaded the dataset.
- Reviewed sample records.
- Examined available features.

## 2. Relationship Analysis

Analyzed:

- Relationship between total bill amount and tip amount.
- Impact of meal time on tipping patterns.
- Difference in tipping behavior between smokers and non-smokers.

---

# Visualizations

## Scatter Plot: Total Bill vs Tip

A scatter plot was created to analyze the relationship between restaurant bills and tips.

### Visualization Features:

- X-axis: Total Bill Amount
- Y-axis: Tip Amount
- Color grouping: Meal Time (Lunch/Dinner)
- Style grouping: Smoker Status


### Key Visualization Insight:

The scatter plot helps identify whether customers with higher bills tend to provide higher tips.

---

# Key Findings

The analysis revealed:

- There is a positive relationship between total bill amount and tip amount.
- Customers with larger bills generally provide higher tips.
- Dinner transactions typically show higher bill amounts compared to lunch.
- Customer groups and dining patterns influence overall spending behavior.
- Visualization helps identify trends without requiring complex statistical models.

---
# Repository Structure

| File / Folder | Description |
|---------------|-------------|
| `Restaurant_Tips_Analysis.ipynb` | Main Jupyter Notebook containing Python code, exploratory data analysis, and visualizations |
| `README.md` | Documentation explaining project objectives, dataset, analysis process, findings, and usage instructions |
| `requirements.txt` | Contains required Python packages and dependencies |
| `images/` | Stores generated plots and visualization images |
| `.gitignore` | Prevents unnecessary files from being uploaded to GitHub |

---

# Skills Demonstrated

This project demonstrates:

### Programming & Data Analysis
- Python Programming
- Data Cleaning
- Data Exploration
- Data Visualization

### Python Libraries
- Pandas
- Matplotlib
- Seaborn

### Data Science Concepts
- Exploratory Data Analysis (EDA)
- Pattern Identification
- Business Insight Generation
- Data Visualization Techniques

---

# Results

The analysis successfully identified customer tipping patterns and demonstrated how visualization techniques can reveal relationships between variables.

Key outcome:

- Higher total bills are associated with higher tip amounts.
- Visual analytics can help restaurants understand customer behavior and spending trends.

---
Future Improvements

Future enhancements could include:

Perform detailed statistical analysis.
Build a predictive model to estimate tip amounts.
Analyze additional factors influencing tips.
Create interactive dashboards using:
Power BI
Tableau
Plotly
Add correlation analysis between numerical variables.
Deploy analysis as a web application.

---

# How to Run

Follow these steps to run this project locally.

## 1. Clone the Repository

Open your terminal or command prompt and run: ```bash
git clone https://github.com/kumsita0/Restaurant-Tips-Analysis.git


## 2. Navigate to the Project Directory
cd Restaurant-Tips-Analysis

## 3. Install Required Libraries
Install all dependencies listed in requirements.txt
pip install -r requirements.txt

## 4. Launch Jupyter Notebook
Open the notebook file: Restaurant_Tips_Analysis.ipynb

---

Author

Kum Sita

GitHub: https://github.com/kumsita0

---
