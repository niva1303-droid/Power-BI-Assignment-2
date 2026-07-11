### Ecommerce Sales Data Analysis - Using Dax and Data Visualization

## 🎯Objective
The objective of this project is to analyze retail sales performance using an Indian Superstore-style dataset — covering orders, order details (revenue, profit, quantity), and monthly sales targets — and build an interactive Power BI dashboard that helps stakeholders:

➡️ Track Actual Sales vs Sales Target across categories and months

➡️ Identify the most profitable and high-performing product categories/sub-categories

➡️ Monitor monthly sales trends to detect seasonality

➡️ Compare profit and quantity across sub-categories to spot high-margin vs high-volume products

➡️ Understand geographic distribution of orders across Indian states

➡️ Provide a consolidated, visual, decision-support tool instead of raw spreadsheet data

## 📁 Datasets
● List of orders

Attributes: Order ID, Order Date, Customer Name, City, State, Category, Amount, Profit

● Order Details

Attributes: Order ID, Category, Sub-Category, Quantity, Amount, Profit

● Sales Target

Attributes: Category, Month of Order Date, Target

## 🧰 Tools Used
➡️ Microsoft Power BI

➡️ DAX (Data Analysis Expressions)

➡️ Data Modeling & Visualization

## ⚖️ DAX Calculations
# Calculated Columns
Category Type, Revenue Per Order, Sales Category

# Calculated Measures
Order Count, Average Profit (Delhi), Year-to-Date (YTD) Sales

## 🖼️ Dashboard Features

⏺️ Clustered Column CHart: Sales Target Achievement by Category

⏺️ Donut Chart: Max Profit Margin by Sub-Category

⏺️ Line Chart: Monthly Sales Trend

⏺️ Scatter Chart: Comparison of Profit and Quantity by Sub-Category

⏺️ Multi-row Cards: Comparison of Total Sales Amount and Target

⏺️ Matrix View: Sales Performance Matrix

⏺️ Tree Map: Sales Distribution by Sub-Category

⏺️ Funnel CHart: Order Count Analysis by State

## 📔 Key Insights:
### Overall Performance

•	Total Sales: ₹4,31,502 | Total Profit: ₹23,955 | Overall profit margin: 5.55% — quite thin

•	Total quantity sold: 5,615 units across 500 orders

•	33.5% of all line items (503 of 1,500) were sold at a loss

### 🥇 Category Performance (Sales vs Target)

•	Electronics is the only category beating its target overall, and by a wide margin.

•	Clothing sold the most units by far (3,516 of 5,615, i.e. 63%) but missed its target the most in value terms — high volume, lower ticket value.

•	Furniture nearly hit its target but earns almost no profit (1.81% margin) — it's your "break-even" category.

•	At the month level, only 16 of 36 category-months (44.4%) actually met target — target-missing is the norm, not the exception.

### 📈 Monthly Trend

•	Sales are volatile, not steadily growing: low point July 2018 (₹12,966), then a strong finish with January 2019 (₹61,439) and March 2019 (₹58,937) as the two best months.

•	November 2018 (₹48,086) also stands out — likely a festive/year-end demand bump, followed by a dip in December (₹37,579).
Sub-Category Deep Dive

•	Best performers: Printers (₹58,252 sales, 10.2% margin) and Bookcases (₹56,861, 8.6% margin) are your top revenue sub-categories with healthy margins.

•	Highest margin: T-shirt (20.3%) and Accessories (16.4%) — small in sales but very profitable per rupee.

### Problem areas — actual money losers: 

o	Tables: ₹22,614 in sales but –₹4,011 loss (-17.7% margin) — your single worst performer.

o	Electronic Games: ₹39,168 sales, –₹1,236 loss (-3.2% margin).

o	Saree: ₹53,511 sales but almost breakeven (0.66% margin) — high revenue, negligible profit.

### 🗺️ Geography

•	Madhya Pradesh (101 orders, ₹1,05,140) and Maharashtra (90 orders, ₹95,348) dominate — together ~38% of all orders.

•	Indore and Mumbai are the top two cities by order count (76 and 68 orders).

•	Tamil Nadu is a red flag: only 8 orders but –₹2,216 total loss. Punjab, Bihar, and Andhra Pradesh are also net-negative on profit despite positive sales.

### 🧗‍♂️ Top Customers
•	Yaanvi (₹9,177), Pooja (₹9,030), and Abhishek (₹8,135) are the top 3 by spend — no single customer dominates, spend is fairly distributed.

## 🚧 Conclusion

The business is growing sales in bursts (especially Nov–Mar) but is not consistently profitable: a third of transactions lose money, overall margin is under 6%, and two sub-categories (Tables, Electronic Games) actively destroy value. Electronics is the clear star — it beats target and carries decent margin — while Clothing drives volume but underdelivers on target and Furniture breaks even at best. The immediate priorities suggested by the data: fix or discontinue Tables and Electronic Games, investigate the Tamil Nadu/Punjab/Bihar loss-making regions, and replicate whatever worked in Nov 2018/Jan 2019/Mar 2019 to smooth out the weak months like July.
