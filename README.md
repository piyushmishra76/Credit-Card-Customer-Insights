# Credit-Card-Customer-Insights
As part of my Internship in Data Analytics at Rixi Lab, I worked on analyzing a credit card customer dataset to extract meaningful business insights.
##  Objective
The objective of this project is to analyze the credit card dataset to understand patterns and trends among users.  
This includes exploring demographics, credit limits, and customer segments to identify factors that influence credit behavior.  
This project was completed as part of my Internship in Data Analytics at Rixi Lab.
## Dataset
- **Rows:** 100  
- **Columns:** 8  
- **Features:** Age, Limit, Credit_Type, Segment, Company, Sno, City, Customer  
- **Type:** Numeric + Categorical  

## Tools & Libraries Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

##  Data Cleaning
- Replaced outliers in Age column with mean values  
- Converted `Limit` column from mixed string (e.g., "INR 450000") to float  
- Performed grouping and segment-wise analysis  

## Key Visualizations
- Histogram: Age Distribution  
- Boxplot: Age by Segment  
- Bar Chart: Customers by Credit Type  
- Pie Chart: Customer Distribution by Segment  
- Histogram: Credit Limit Distribution  

## Findings
- Most customers use credit type in this order: **Gold > Platinum > Silver**  
- Majority of customers belong to the **Govt sector**  
- Most customers are in the **age group near 50**  
🚀 How to Run
Clone this repo:
git clone https://github.com/yourusername/Credit-Card-Customer-Insights.git

Install requirements:
pip install -r requirements.txt

Open the notebook:
jupyter notebook "Credit Card Customer Insights.ipynb"
