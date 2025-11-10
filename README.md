# 💡 ElectroHub Sales Dashboard — Power BI Project  

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Cleaning-217346?style=flat&logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-Data%20Modeling-0078D4?style=flat&logo=powerbi&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Business%20Intelligence-blueviolet?style=flat)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-1E90FF?style=flat)

---

## 🧭 Project Overview  

**ElectroHub** is a retail company selling multiple product categories — *Electronics, Footwear, Clothing, Home Appliances, Accessories, Kitchenware, Bags, and Personal Care*.  

This Power BI dashboard provides actionable insights into **Sales Performance, Profitability, Customer Behavior**, and **Discount Strategies**.  
It helps stakeholders make **data-driven business decisions** by visualizing key KPIs, product trends, and regional performance.

🔗 **Dashboard Link:** [View Power BI Report](https://app.powerbi.com/links/13y6TgW8sI?ctid=5e770d14-5ca7-46e0-9e00-2cdf210bd1ca&pbi_source=linkShare)

---

## ⚙️ Steps Followed  

- **Step 1:** Imported dataset (CSV) into **Power BI Desktop**.  
- **Step 2:** Used **Power Query Editor** for cleaning and enabled column profiling.  
- **Step 3:** Transformed and validated data for consistency.  
- **Step 4:** Created DAX Measures for KPIs:  
  - `Total Sales = SUM(Sales[Total Sales])`  
  - `Net Sales = SUM(Sales[Net Sales])`  
  - `Total Profit = SUM(Sales[Sum of Profit])`  
  - `Quantity Sold = SUM(Sales[Units Sold])`  
  - `Discount Value = SUM(Sales[Discount Value])`  
- **Step 5:** Designed slicers for **Date, Customer Name, Product Name, Promotion Name**.  
- **Step 6:** Built KPIs for Net Sales, Total Profit, Quantity Sold, and Orders.  
- **Step 7:** Added comparison visuals for different time periods.  
- **Step 8:** Created visualizations:  
  - Bar Charts → Top 5 & Bottom 5 Products  
  - Map → Sales by City  
  - Scatter Plot → Profit vs Net Sales  
  - Line Chart → Sales Trends over Time  
  - Bar Chart → Average Discount by Promotion Category  
- **Step 9:** Styled the dashboard with a purple–pink gradient theme for professional readability.  
- **Step 10:** Published the final report to **Power BI Service** for online access.

---

## 📸 Dashboard Snapshots  

| View | Description |
|------|--------------|
| ![Order Date](https://github.com/Shivamt7/Sales-Dataset-Analysis/blob/4caa1c2976e8ed7ab9d9d8acb1c8f2831bf979df/Table%20Visual.png) | Orders Data Table with interactive filters |
| ![KPIs](https://github.com/Shivamt7/Sales-Dataset-Analysis/blob/8c14aa8039e56fe2ff801af3ea956731aaee50ed/Camparison%20Sales_Profit_Quantity.png) | KPI cards for Net Sales, Profit & Quantity comparison |
| ![Top Bottom Products](https://github.com/Shivamt7/Sales-Dataset-Analysis/blob/4caa1c2976e8ed7ab9d9d8acb1c8f2831bf979df/Top_Bottom%20Sales.png) | Top & Bottom 5 Products by Sales, Profit & Quantity |
| ![Sales by City](https://github.com/Shivamt7/Sales-Dataset-Analysis/blob/4caa1c2976e8ed7ab9d9d8acb1c8f2831bf979df/Trends%20and%20Overview.png) | Sales by City, Profit vs Net Sales & Sales Trend visual |

---

## 📊 Insights  

### 🔹 Overall Metrics  
- **Total Net Sales:** ₹12.23M  
- **Total Profit:** ₹1.22M  
- **Total Quantity Sold:** 7.1K Units  
- **Total Orders:** 3510  

---

### 🔹 Top & Bottom Products  

#### 🏆 Top 5 Products (by Net Sales)
1. Apple iPhone 14 — ₹21.4M  
2. Apple MacBook Air — ₹19.6M  
3. Sony Bravia 55" TV — ₹19.4M  
4. Samsung Galaxy S21 — ₹15.3M  
5. HP Pavilion Laptop — ₹14.4M  

#### ⚠️ Bottom 5 Products (by Net Sales)
1. Tupperware Lunch Box  
2. L’Oreal Shampoo  
3. Nivea Body Lotion  
4. Dove Soap Pack  
5. Colgate Toothpaste  

---

### 🔹 Top & Bottom by Profit  
- **Top:** Apple iPhone 14 — ₹2.14M  
- **Bottom:** Colgate Toothpaste — ₹2K  

---

### 🔹 Sales Trends  
- Steady growth from **2020–2024**.  
- Sharp peaks during **Diwali & New Year** periods.  

---

### 🔹 Profit vs Net Sales  
- Strong positive correlation — higher sales directly increase profits.  
- Indicates effective **pricing & cost management**.  

---

### 🔹 Average Discount by Promotion Category  

| Promotion Type | Average Discount |
|----------------|------------------|
| Weekend Flash Sale | ₹23K |
| Clearance Sale | ₹18K |
| Summer Sale | ₹7K |
| New Year Special | ₹3K |
| Festive Diwali | ₹0 |

---

### 🔹 Sales by City  

**Top Performing Cities:**  
Bangalore, Mumbai, Delhi, Hyderabad  

**Moderate Performing Cities:**  
Jaipur, Ahmedabad, Pune, Chennai  

---

## 🧠 Key Learnings  

- Power BI slicers enable **interactive data exploration** by product, city, customer, and promotion.  
- Strong **profit–sales correlation** indicates business efficiency.  
- **Discount analysis** helps identify the most effective promotional campaigns.  
- KPIs and trends enable **data-driven strategy formulation** for management.  

---

## 🧰 Tools & Technologies  

| Tool | Purpose |
|------|----------|
| **Power BI Desktop** | Dashboard creation |
| **Power Query** | Data transformation |
| **DAX** | KPI calculations & measures |
| **Excel** | Pre-cleaning and validation |
| **Power BI Service** | Dashboard publishing & sharing |

---

## 👨‍💻 Author  

**Shivam Mishra**  
SDE Intern | Data Analyst | Power BI Developer  

📧 [shivammishra@example.com](mailto:shivammishra@example.com)  
🌐 [LinkedIn Profile](https://linkedin.com/in/shivammishra)  

---

⭐ *If you found this project insightful, don’t forget to star this repository!* ⭐
