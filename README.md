
# ShopperMetrics Analysis
### Customer Shopping Behavior Analysis Using Python, PostgreSQL, SQL & Power BI

## 1. Project Overview

ShopperMetrics Analysis is an end-to-end data analytics project focused on understanding customer shopping behavior, purchasing patterns, product preferences, and discount usage.

The project uses Python for data cleaning and exploratory data analysis, PostgreSQL for database management, SQL for business analysis, and Power BI for creating an interactive dashboard.

The main objective is to transform raw customer shopping data into meaningful insights that help understand customer preferences and purchasing trends.

## 2. Dataset

The project uses a Customer Shopping Behavior dataset containing information about customer demographics, purchased products, shopping preferences, payment methods, discounts, and purchase history.

The dataset includes the following attributes:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

## 3. Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| PostgreSQL | Database management |
| SQL | Business data analysis |
| Power BI | Interactive dashboard creation |
| Jupyter Notebook | Python development environment |
| Gamma AI | Presentation preparation |

## 4. Project Workflow

### Step 1: Data Loading and Cleaning – Python

- Imported the dataset using Pandas.
- Explored the dataset structure and data types.
- Checked for missing values and duplicate records.
- Performed data cleaning and preprocessing.
- Prepared the dataset for further analysis.

### Step 2: Exploratory Data Analysis (EDA)

- Analyzed customer demographics.
- Explored product and category preferences.
- Examined purchasing patterns.
- Analyzed discount and promotional code usage.
- Studied customer ratings and purchase history.
- Created visualizations using Matplotlib and Seaborn.

### Step 3: Database Connection – PostgreSQL

- Created a PostgreSQL database named `customer_behaviour`.
- Connected Python to PostgreSQL using SQLAlchemy and psycopg2.
- Loaded the cleaned dataset into a PostgreSQL table named `customer`.

### Step 4: SQL Business Analysis

Used SQL queries to analyze customer shopping behavior and answer business-related questions.

The analysis included:

- Purchase and revenue analysis.
- Customer purchasing frequency.
- Product and category performance.
- Discount and promotional code analysis.
- Customer ratings and preferences.
- Shopping patterns across different customer groups.

### Step 5: Dashboard Creation – Power BI

- Connected Power BI to the PostgreSQL database.
- Imported the customer data.
- Created visualizations to represent important business metrics.
- Designed an interactive dashboard to explore customer shopping behavior.

## 5. Power BI Dashboard

The Power BI dashboard provides a visual overview of customer shopping behavior and purchasing patterns.

### Key Dashboard Metrics

- Total Number of Customers
- Average Purchase Amount
- Average Review Rating
- Customer Subscription Status
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group

The dashboard also includes interactive filters for:

- Subscription Status
- Gender
- Category
- Shipping Type

### Dashboard Preview

![ShopperMetrics Power BI Dashboard](screenshots/ShopperMetrics%20Power%20BI%20Dashboard.png)

**Power BI File:** [customer_behavior_dashboard.pbix](powerbi/customer_behavior_dashboard.pbix)

## 6. Key Analysis Areas

The project focuses on understanding:

- Customer purchasing behavior and preferences.
- Popular products and product categories.
- Spending patterns across customer groups.
- Discount and promotional code usage.
- Customer ratings and satisfaction patterns.
- Shopping frequency and subscription behavior.

## 7. Project Structure

```text
Customer_Shopping_Behavior_Analysis/
│
├── dataset/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_shopping_analysis.ipynb
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── reports/
│   ├── Business Problem Document.pdf
│   ├── Customer-Shopping-Behavior-Analysis.pptx
│   ├── REPORT Customer Shopping Behavior Analysis.pdf
│   └── ShopperMetrics Analysis.pptx
│
├── screenshots/
│   └── ShopperMetrics Power BI Dashboard.png
│
├── sql/
│   └── customer_behavior_sql_queries1.sql
│
└── README.md
```

## 8. How to Run the Project

### Prerequisites

Install the following tools:

- Python
- Jupyter Notebook or Visual Studio Code
- PostgreSQL
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone https://github.com/Oviyaavanasi/ShopperMetrics-Analysis.git
```

Navigate to the project folder:

```bash
cd ShopperMetrics-Analysis
```

### Step 2: Install Python Libraries

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary
```

### Step 3: Run Python Analysis

1. Open the project in Visual Studio Code or Jupyter Notebook.
2. Open `notebooks/customer_shopping_analysis.ipynb`.
3. Make sure the dataset path points to the correct CSV file.
4. Run the notebook cells to perform data cleaning and exploratory data analysis.

### Step 4: PostgreSQL Setup

1. Open PostgreSQL using pgAdmin.
2. Create a database named `customer_behaviour`.
3. Update the database connection details in the notebook.
4. Execute the Python code to load the cleaned data into the PostgreSQL database.

**Note:** Keep your PostgreSQL password private. Do not upload passwords or credentials to GitHub.

### Step 5: Run SQL Analysis

1. Open PostgreSQL using pgAdmin or another SQL editor.
2. Connect to the `customer_behaviour` database.
3. Open `sql/customer_behavior_sql_queries1.sql`.
4. Execute the queries to perform business analysis.

### Step 6: Open Power BI Dashboard

1. Open Power BI Desktop.
2. Open `powerbi/customer_behavior_dashboard.pbix`.
3. Configure the PostgreSQL connection if required.
4. Explore the dashboard and its visualizations.

## 9. Future Enhancements

- Customer segmentation based on purchasing behavior.
- Detailed discount effectiveness analysis.
- Additional customer satisfaction analysis.
- Advanced product performance analysis.
- Enhanced Power BI dashboard with additional interactive features.

## 10. Author

**Oviya A.**

B.E. Computer Science and Engineering

This project was developed as part of my learning journey in Data Analytics, focusing on Python, SQL, PostgreSQL, and Power BI.

---

⭐ If you find this project interesting, feel free to explore the repository!
