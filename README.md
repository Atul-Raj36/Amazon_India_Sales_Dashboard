# Amazon_India_Product_Dashboard

## Project Overview
The Amazon India Sales Dashboard is an Excel-based business
intelligence project designed to provide a clear view of sales,
profitability, product performance, order status, payment methods,
fulfilment methods, and geographic performance.

The dashboard is intended for business management users, including
non-technical stakeholders, so that they can monitor key performance
indicators (KPIs), identify trends, and make informed business decisions
using visual summaries.

## Business Objective
The objective is to bring important business information into one
management dashboard. The dashboard addresses four key business
questions:
1. How is the business performing overall?
2. Which products and categories are driving the business?
3. How many orders are successfully completed and how many are being
   lost through returns and cancellations?
4. Which payment methods, fulfilment methods, and states are generating
   business?

## Dataset Overview
The project dataset contains 10,000 order records covering 1
January 2024 to 30 August 2026.

The source workbook includes a Data worksheet with 13 fields:



<div align="center">
  <h1>📊 Amazon India Sales Dashboard</h1>
  <p><strong>An Excel-based Business Intelligence Dashboard for Sales, Profitability & Operations</strong></p>
</div>

---

## 📋 Project Overview & Business Objective

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎯 Project Overview</h3>
      <p>The <strong>Amazon India Sales Dashboard</strong> is an Excel-based business intelligence project designed to provide a clear view of sales, profitability, product performance, order status, payment methods, fulfilment methods, and geographic performance.</p>
      <p>Intended for business management and non-technical stakeholders, it helps monitor KPIs, identify trends, and make informed decisions using visual summaries.</p>
    </td>
    <td width="50%" valign="top">
      <h3>❓ Key Business Questions</h3>
      <ol>
        <li>How is the business performing overall?</li>
        <li>Which products and categories are driving the business?</li>
        <li>How many orders are completed vs. lost through returns and cancellations?</li>
        <li>Which payment methods, fulfilment methods, and states generate business?</li>
      </ol>
      <p><em>Based on the supplied business requirements document.</em></p>
    </td>
  </tr>
</table>

---

## 📈 Headline Dashboard KPIs

<table>
  <tr>
    <td width="33%" align="center">
      <h3>₹15.58 Cr</h3>
      <p><strong>Total Sales</strong></p>
    </td>
    <td width="33%" align="center">
      <h3>₹3.32 Cr</h3>
      <p><strong>Total Profit</strong></p>
    </td>
    <td width="33%" align="center">
      <h3>21.29%</h3>
      <p><strong>Profit Margin</strong></p>
    </td>
  </tr>
  <tr>
    <td width="33%" align="center">
      <h3>10,000</h3>
      <p><strong>Total Orders</strong></p>
    </td>
    <td width="33%" align="center">
      <h3>24,926</h3>
      <p><strong>Total Units Sold</strong></p>
    </td>
    <td width="33%" align="center">
      <h3>₹15,579</h3>
      <p><strong>Average Order Value (AOV)</strong></p>
    </td>
  </tr>
</table>

---

## 🗂️ Dataset Overview & Metric Definitions

The dataset contains **10,000 order records** covering **1 January 2024 to 30 August 2026** across 13 fields in the `Data` worksheet.

<table>
  <tr>
    <td width="55%" valign="top">
      <h3>📑 Source Data Fields</h3>
      <table>
        <tr>
          <th>Column</th>
          <th>Description</th>
        </tr>
        <tr><td><code>Order_ID</code></td><td>Unique order identifier</td></tr>
        <tr><td><code>Order_Date</code></td><td>Date order was placed</td></tr>
        <tr><td><code>Category</code></td><td>Product category</td></tr>
        <tr><td><code>Product</code></td><td>Product name</td></tr>
        <tr><td><code>Quantity</code></td><td>Number of units ordered</td></tr>
        <tr><td><code>Unit_Price_INR</code></td><td>Unit price in INR</td></tr>
        <tr><td><code>Discount_Pct</code></td><td>Discount percentage</td></tr>
        <tr><td><code>Total_Sales_INR</code></td><td>Sales value in INR</td></tr>
        <tr><td><code>Profit_INR</code></td><td>Profit in INR</td></tr>
        <tr><td><code>Payment_Method</code></td><td>Payment method used</td></tr>
        <tr><td><code>Fulfillment</code></td><td>Fulfilment method</td></tr>
        <tr><td><code>Order_Status</code></td><td>Current order status</td></tr>
        <tr><td><code>Ship_State</code></td><td>Customer shipping state</td></tr>
      </table>
    </td>
    <td width="45%" valign="top">
      <h3>🧮 Metric Definitions</h3>
      <ul>
        <li><strong>Total Sales:</strong> Sum of <code>Total_Sales_INR</code>.</li>
        <li><strong>Total Profit:</strong> Sum of <code>Profit_INR</code>.</li>
        <li><strong>Total Orders:</strong> Distinct count of <code>Order_ID</code>.</li>
        <li><strong>Total Units Sold:</strong> Sum of <code>Quantity</code>.</li>
        <li><strong>Average Order Value:</strong> Total Sales ÷ Total Orders.</li>
        <li><strong>Profit Margin:</strong> (Total Profit ÷ Total Sales) × 100.</li>
        <li><strong>Return Rate:</strong> (Returned Orders ÷ Total Orders) × 100.</li>
        <li><strong>Cancellation Rate:</strong> (Cancelled Orders ÷ Total Orders) × 100.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🔍 Dashboard Sections & Key Insights

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>1. Overall Sales & Profit Performance</h3>
      <p><strong>Metrics Covered:</strong> Total Sales, Profit, Orders, Units Sold, AOV, Profit Margin, Monthly Sales & Profit Trend.</p>
      <p><strong>Key Findings:</strong></p>
      <ul>
        <li>Sales and profit were nearly flat from 2024 to 2025 (~0.7% sales growth).</li>
        <li>Jan–Aug 2026 sales rose <strong>7.5%</strong> and profit rose <strong>9.6%</strong> YoY.</li>
        <li><strong>July 2026</strong> was the strongest month (~₹64.4L sales, ~₹13.3L profit).</li>
        <li>Monthly profit margin stayed consistently within <strong>19%–23%</strong>.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>2. Category & Product Performance</h3>
      <p><strong>Metrics Covered:</strong> Category-wise Sales, Profit, Units Sold, Top 10 Products by Sales.</p>
      <p><strong>Key Findings:</strong></p>
      <ul>
        <li><strong>Electronics & Mobiles</strong> drove ~<strong>79.3%</strong> of total sales, including all top 5 products.</li>
        <li><strong>Home & Kitchen</strong> contributed ~<strong>11.5%</strong> of total sales.</li>
        <li><strong>Apparel & Fashion</strong> sold more units than Home & Kitchen but generated lower revenue.</li>
        <li><strong>Beauty & Personal Care</strong> and <strong>Pantry & Groceries</strong> combined for &lt;3% of sales.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>3. Order Status & Revenue Loss</h3>
      <p><strong>Metrics Covered:</strong> Delivered, Shipped, Returned, Cancelled Orders, Return & Cancellation Rates.</p>
      <table>
        <tr>
          <th>Order Status</th>
          <th>Orders</th>
          <th>Share</th>
        </tr>
        <tr><td>Delivered</td><td>8,147</td><td>81.47%</td></tr>
        <tr><td>Shipped</td><td>868</td><td>8.68%</td></tr>
        <tr><td>Returned</td><td>485</td><td>4.85%</td></tr>
        <tr><td>Cancelled</td><td>500</td><td>5.00%</td></tr>
      </table>
      <p><strong>Key Findings:</strong></p>
      <ul>
        <li>Returns and cancellations accounted for <strong>985 orders (9.85%)</strong>.</li>
        <li><strong>Apparel & Fashion</strong> had the highest cancellation rate; <strong>Electronics & Mobiles</strong> had the highest return rate.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>4. Payment, Fulfilment & Geography</h3>
      <p><strong>Metrics Covered:</strong> Sales & Profit by Payment/Fulfilment Method, State-wise Sales, Profit & Orders.</p>
      <p><strong>Key Findings:</strong></p>
      <ul>
        <li><strong>UPI</strong> was the top payment method (~<strong>50.4%</strong> of sales).</li>
        <li><strong>Amazon Pay Later</strong> achieved the highest profit margin among payment methods.</li>
        <li><strong>Amazon (FBA)</strong> accounted for ~<strong>69.0%</strong> of total sales.</li>
        <li><strong>Maharashtra, Karnataka, and Delhi</strong> led sales; top 5 states generated ~<strong>69%</strong> of sales.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🛠️ Tools, Usage & Repository Structure

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚙️ Tools & Excel Features</h3>
      <ul>
        <li>Microsoft Excel</li>
        <li>Excel Tables & Dynamic Formulas</li>
        <li>PivotTables & PivotCharts</li>
        <li>Interactive Slicers & Filters</li>
        <li>KPI Cards & Dashboard Visuals</li>
      </ul>
      <h3>📖 How to Use the Workbook</h3>
      <ol>
        <li>Open <code>Amazon India Dashboard.xlsx</code>.</li>
        <li>Review the <code>Data</code> sheet for source records.</li>
        <li>Check <code>Obj_*</code> sheets for supporting analysis.</li>
        <li>Open the <code>Dashboard</code> sheet and use slicers (Date, Category, Payment, Fulfilment, Status, State) to filter views.</li>
        <li>Click <strong>Data → Refresh All</strong> if source data updates.</li>
      </ol>
    </td>
    <td width="50%" valign="top">
      <h3>📁 Repository Structure</h3>
      <pre>
Amazon-India-Sales-Dashboard/
│
├── README.md
│
├── Dashboard/
│   ├── Amazon India Dashboard.xlsx
│   └── Dashboard Screenshot.png
│
├── Dataset/
│   └── Amazon Sales Data India.xlsx
│
└── Documentation/
    ├── Amazon India Dashboard Requirements.pdf
    └── Amazon India Dashboard – Business Questions & Insights.docx
      </pre>
      <p><em>Note: Only include or redistribute the dataset if you have permission to share it.</em></p>
    </td>
  </tr>
</table>

---

## ✅ Conclusion

The analysis shows that the business is strongly dependent on the **Electronics & Mobiles** category, while **UPI** and **Amazon FBA** serve as the primary payment and fulfilment channels. Although **81.47%** of orders are successfully delivered, reducing the **9.85%** combined return and cancellation rate represents a clear opportunity for operational improvement.

