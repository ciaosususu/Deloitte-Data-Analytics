# Deloitte Data Analytics Virtual Experience - Task 2

## 📌 Overview
This project analyses gender pay equality across different factories and job roles at Daikibo Industrials.  

Using employee compensation data, an Equality Score was provided for each job role, ranging from -100 to +100 (where 0 represents perfect equality).  

The objective of this analysis is to classify and visualise the level of gender pay inequality to help identify areas requiring attention.

## 📊 Methodology

### 1. Data Processing
- Loaded the dataset from Excel
- Cleaned column names and ensured data consistency

### 2. Feature Engineering
Created a new column: **`Equality Class`**, based on the Equality Score:

- **Fair** → -10 ≤ score ≤ 10  
- **Unfair** → -20 ≤ score < -10 OR 10 < score ≤ 20  
- **Highly Discriminative** → score < -20 OR score > 20  

### 3. Visualisation
- Bar chart showing distribution of Equality Classes
- Analysis performed using Python (Pandas & Matplotlib)


## 📈 Key Insights

- A significant number of roles fall into **Unfair** and **Highly Discriminative** categories  
- This suggests notable gender pay imbalance across certain job roles  
- Only a portion of roles achieve **Fair** equality levels  
- Further investigation is needed to identify specific factories or roles driving inequality  


## 📂 Project Structure

- `data/`  
  - Original dataset (`Equality Table.xlsx`)  
  - Processed dataset (`Equality Table - Classified.xlsx`)  

- `notebook/`  
  - Jupyter Notebook containing full analysis  

- `images/`  
  - Visualisations of equality distribution  


## 🛠️ Tools & Skills

- Python (Pandas, Matplotlib)  
- Data Cleaning & Feature Engineering  
- Data Visualisation  
- Excel Data Handling  


## 📎 Output

- Classified dataset with Equality Class column  
- Visual insights into gender pay distribution  
- Reproducible analysis in Jupyter Notebook  


## 🚀 Business Value

This analysis helps organisations:

- Identify areas of gender pay inequality  
- Prioritise HR and policy interventions  
- Improve fairness and compliance with equality standards  
