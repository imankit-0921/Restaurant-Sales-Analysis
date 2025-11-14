# 🍽️ Restaurant Sales Analysis – Data Science Project & BI Dashboard

## 📌 Project Overview
This project focuses on analyzing **restaurant sales performance** using data science techniques.  
It includes:
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Statistical Insights  
- Interactive BI Dashboard using **Plotly**  
- Business-driven insights for decision-making  

The purpose of this project is to understand:
- Which products sell the most  
- Revenue trends over time  
- Best-performing cities & managers  
- Payment preferences  
- Monthly trends and customer behavior  

---

## 📁 Dataset Description
The dataset contains **254 rows** and **12 columns**:

| Column | Description |
|--------|-------------|
| `Order ID` | Unique identifier for each order |
| `Date` | Date of purchase |
| `Product` | Purchased food item |
| `Price` | Unit price |
| `Quantity` | Quantity sold |
| `Purchase Type` | Mode of purchase (Online/Drive-thru/In-store) |
| `Payment Method` | Card / Cash / Wallet / Gift Card |
| `Manager` | Manager handling the order |
| `City` | Buyer’s city |
| `Revenue` | Price × Quantity |
| `Total Sales` | Total order value |
| `Month` | Extracted (YYYY-MM) |

---

## 🧹 Data Cleaning & Preprocessing
Performed the following steps:

### 🔧 Data Fixes  
- Removed unwanted spaces in the **Manager** column  
- Converted `Date` → `datetime`  
- Converted `Quantity` → integer  
- Converted `Price` → float  
- Fixed inconsistent formatting  

### ➕ Feature Engineering  
Added:
- `Revenue`  
- `Total Sales`  
- `Month` (Period-based YYYY-MM)

---

## 📊 Exploratory Data Analysis (EDA)

### 🔸 Most Preferred Payment Method  
Bar chart showing usage of Card, Cash, Wallet, Gift Card.

### 🔸 Best Selling Product  
- By Quantity  
- By Revenue  

### 🔸 Manager Performance  
Which manager contributes the most?

### 🔸 City-Wise Revenue  
Which city drives top revenue?

### 🔸 Monthly Revenue Trend  
Time-series analysis.

### 🔸 Statistical Analysis  
- Mean, Std. Deviation  
- Variance  
- MoM revenue change  

---

## 📈 Interactive Dashboard (Plotly)
A complete **BI dashboard** containing:

### 📌 Visuals Included
- Sales by Category  
- Monthly Sales Trend  
- Top 10 Best Selling Items  
- Payment Mode Distribution  
- Branch / City Sales  
- Combined Multi-chart Layout  
- Exportable HTML Dashboard  

### 📤 Export Dashboard (HTML)
```python
fig.write_html("restaurant_dashboard.html")
```
### 🚀 How to Run the Project
  1. Install Required Libraries
  -pip install pandas numpy plotly seaborn matplotlib

  2. Upload Dataset in Google Colab
  -from google.colab import files
  -uploaded = files.upload()

  3. Run the Notebook

    Execute all steps:
    -Data Cleaning
    -EDA
    -Dashboard Generation

  4. Export Dashboard
  -fig.write_html("restaurant_dashboard.html")
  -files.download("restaurant_dashboard.html")

### 🧰 Tools & Technologies Used
- Languages
- Python
- Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Plotly Express
- Pathlib
- Platforms
- Google Colab
- GitHub (for deployment)

### 🔍 Key Insights (From EDA)
📌 1. Top-Selling Products

Fries, Burgers, Beverages & Sandwiches generate maximum quantity & revenue.

📌 2. Most Common Payment Method

Gift Card & Credit Card dominate sales.

📌 3. Best Manager by Revenue

Walter Muller generates the highest revenue.

📌 4. Top City by Sales

Berlin contributes maximum revenue.

📌 5. Monthly Trend

Sales increased significantly during December.

### 🚀 Future Enhancements
## 🔮 Advanced Improvements

- Build a Machine Learning Model to predict revenue
- Develop a Recommendation System for items
- Add Customer Segmentation (Clustering)
- Add Sales Forecasting using ARIMA / LSTM
- Deploy Dashboard using Streamlit / Flask
- Add AI-powered insights generator

### 🧑‍💻 Author

Ankit Kumar Upadhyay | 
Data Science & AI Enthusiast

📧 Email: upadhyayankit767@gmail.com

🔗 GitHub: [your-github-link](https://github.com/imankit-0921) | 
🔗 LinkedIn: [your-linkedin-link](https://www.linkedin.com/in/ankit-upadhyay-9734a424b)
