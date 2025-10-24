# 🧾 Supermarket Sales Analysis

## 📊 Project Overview
This project analyzes **supermarket sales data** using only the **Pandas** library in Python.  
The goal is to extract meaningful insights about revenue, customer behavior, product performance, and payment trends without using any visualization or BI tools.

Dataset used: [Supermarket Sales – Kaggle (faresashraf1001)](https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales)

---

## 🧠 Objective
- Perform complete data analysis using **only Pandas**
- Explore and clean real-world sales data
- Identify sales patterns, profitable products, and customer preferences
- Calculate business KPIs such as revenue, average sales, and profit margin

---

## 🗂️ Dataset Information
**Rows:** 1,000  
**Columns:** 17  

| Column Name | Description |
|--------------|-------------|
| Invoice ID | Unique identifier for each transaction |
| Branch | Branch of the supermarket (A, B, or C) |
| City | City where the branch is located |
| Customer type | Type of customer (Member or Normal) |
| Gender | Gender of the customer |
| Product line | Category of the product sold |
| Unit price | Price of each unit |
| Quantity | Number of units sold |
| Tax 5% | Tax amount for the sale |
| Total | Total amount including tax |
| Date | Date of purchase |
| Time | Time of purchase |
| Payment | Mode of payment (Cash, Credit card, etc.) |
| cogs | Cost of goods sold |
| gross margin percentage | Profit margin percentage |
| gross income | Income from the transaction |
| Rating | Customer rating of the experience |

---

## 🔍 Key Steps in the Analysis

1. **Data Loading & Exploration**
   - Read CSV using Pandas  
   - Explore data types, missing values, and summary statistics  

2. **Data Cleaning**
   - Converted date and time columns  
   - Extracted `Month` and `Hour` features  

3. **Revenue Analysis**
   - Total revenue generated  
   - Average invoice value  

4. **Branch & City Performance**
   - Revenue comparison between branches and cities  

5. **Product Insights**
   - Best-selling and highest-rated product lines  

6. **Customer Insights**
   - Sales comparison by gender and customer type  

7. **Time-Based Analysis**
   - Monthly and hourly revenue patterns  

8. **Payment Method Insights**
   - Popular payment methods and their total contribution  

9. **Profitability**
   - Calculated average profit margin for branches  

---

## 💡 Key Insights

- **Branch C** generated the highest total revenue.  
- **Food and Beverages** was the top-performing product line.  
- **Members** spent more on average than normal customers.  
- Sales peaked between **noon and evening hours (12 PM–7 PM)**.  
- **E-wallet** payments were most frequently used.  
- Average profit margin across all branches was around **4.76%**.

---

## 🧰 Technologies Used
- **Python 3**
- **Pandas**


---

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/Supermarket-Sales-Analysis.git
   ```
2. Open the notebook in Jupyter or VS Code  
3. Run all cells sequentially  
4. Explore the results printed in each step

---

## 🧑‍💻 Author
**Nidhi Devrani**  
📧 [nidhidevrani01@gmail.com](mailto:nidhidevrani01@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/nidhi-devrani-b79159349) | [GitHub](https://github.com/NidhiDevrani)

