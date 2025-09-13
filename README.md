# 🛍️ Product Sales Analysis  

Analyzing and visualizing global product sales data using a **star schema** dataset.  
This project leverages data preprocessing, exploratory data analysis (EDA), and visualization techniques to uncover **key business insights** such as top-performing products, customer behavior, and sales trends.  

---

## 📄 Overview  

This project explores **product sales data** stored in a star schema (Fact + Dimension tables). By integrating fact and dimension tables, the analysis reveals insights into **revenue trends, product performance, customer contribution, and regional growth**.  

The ultimate goal is to **support decision-making** in sales strategy and business development through **data-driven insights**.  

---

## 🎯 Objectives  

- **Data Analysis**: Examine product sales to identify patterns and trends.  
- **Customer Insights**: Understand high-value customers and regions.  
- **Product Performance**: Highlight top-performing and underperforming products.  
- **Time-Based Trends**: Analyze sales growth across months, quarters, and years.  
- **Visualization**: Create interactive, meaningful charts to support findings.  

---

## ⚙️ Technologies Used
- **Python** (Data Processing & Web App)
- **Pandas** (Data Analysis)
- **Plotly / Matplotlib / Seaborn** (Data Visualization)
- **Flask**  (Web Framework for dashboard)
- **CSV files** (Dataset)
  
---

## 🔍 Data Description  

The dataset follows a **star schema** with one fact table and multiple dimension tables:  

- **DIM_Customer.csv** – Contains customer details (Customer ID, Name, Region, etc.)  
- **DIM_Products.csv** – Contains product details (Product ID, Product Name, Category, Subcategory, etc.)  
- **Dim_Date_Excel.csv** – Date dimension table (Date, Month, Quarter, Year, etc.)  
- **FactInternetSale.csv** – Fact table containing sales transactions (Sales Order ID, Product ID, Customer ID, Date ID, Quantity, Sales Amount, etc.)  

📌 These tables are linked using keys (e.g., ProductID, CustomerID, DateID).  

---

## 📊 Data Analysis  

The analysis pipeline includes:  

1. **Data Cleaning**  
   - Handling missing values  
   - Normalizing column formats  

2. **Exploratory Data Analysis (EDA)**  
   - Identifying sales distribution  
   - Detecting seasonality and growth patterns  

3. **Visualization**  
   - Sales by product, customer, region, and time  

---

## 📈 Key Visualizations
The dashboard provides multiple interactive insights:

1. **View Product Sales Data** – Overview of sales across all products  
2. **Explore Customer States** – Distribution of customers by state/location  
3. **Analyze Product Categories** – Sales performance across categories  
4. **Check Product Colors Distribution** – Most popular product colors  
5. **Track Sales Trends Over Time** – Sales trends by month/year  
6. **View Customer Gender Distribution** – Gender-based sales analysis  
7. **Examine Product Line Distribution** – Sales grouped by product lines  
8. **Explore Product Model Distribution** – Model-level performance  
9. **View Products List** – Complete list of products and attributes  

---

## 🏆 Example Insights  

- 📌 *Category A* contributed **35% of overall revenue**.  
- 📌 *Customer X* was the **top spender**, generating over **₹5,00,000**.  
- 📌 Sales peaked in **Q4 2023**, with a **20% growth vs. Q3**.  
- 📌 *South Region* showed consistent growth, while *West Region* lagged.  

---

## 🚀 How to Run the Project  

```bash
# Clone the repository
git clone https://github.com/prithivraj-ml/Product_Sales_Analysis.git
cd Product_Sales_Analysis

# Install dependencies
pip install -r requirements.txt

# Run the analysis
jupyter notebook notebooks/Product_Sales_Analysis.ipynb
📌 All visualizations and detailed analysis are available inside the notebooks/ directory.

🤝 Collaboration
Contributions are welcome! To collaborate:

1.Fork the repository

2.Create a new branch: git checkout -b feature-branch

3.Commit your changes: git commit -m 'Add new feature'

4.Push to the branch: git push origin feature-branch

5.Create a Pull Request

📧 Contact
For inquiries or collaboration:

Name: Prithivraj

Email: prithivraj.ml@gmail.com

LinkedIn: linkedin.com/in/prithivraj-ml

GitHub: github.com/prithivraj-ml
