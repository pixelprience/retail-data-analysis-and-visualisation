# Retail Data Analysis and Visualisation

## Project Background

This project was completed as part of the Tata Data Visualisation Virtual Experience Program on Forage.

The objective was to analyse a large retail transaction dataset and provide actionable business insights for executive stakeholders.

---

## Dataset

The dataset contains more than 500,000 retail transactions and includes:

- Invoice Number
- Product Information
- Quantity Sold
- Invoice Date
- Unit Price
- Customer ID
- Country

---

## Data Cleaning

Before analysis the following cleaning steps were performed:

- Removed transactions where Quantity <= 0.
- Removed transactions where UnitPrice <= 0.
- Created Revenue field using:

Revenue = Quantity × Unit Price

- Created Year field using InvoiceDate.
- Created Month field using InvoiceDate.

---

## Question 1

### Objective

Analyse monthly revenue trends throughout 2011.

### Visual

../visuals/q1-monthly-revenue-trend.png

### Findings

- Revenue fluctuated throughout the year.
- September produced the highest revenue.
- Strong performance observed during July and November.
- Seasonal trends were identified.

### Business Recommendation

Improve forecasting and inventory planning for peak demand periods.

---

## Question 2

### Objective

Identify top-performing countries outside the United Kingdom.

### Visual

../visuals/q2-top-countries.png

### Findings

- Netherlands generated the highest revenue.
- EIRE and Germany also performed strongly.
- Western Europe represented the strongest international market.

### Business Recommendation

Prioritise marketing investment in high-performing regions.

---

## Question 3

### Objective

Identify top revenue-generating customers.

### Visual

../visuals/q3-top-customers.png

### Findings

- Customer 14646 generated the highest revenue.
- Revenue was concentrated among a small group of customers.

### Business Recommendation

Develop retention programmes targeting high-value customers.

---

## Question 4

### Objective

Identify countries with the highest product demand.

### Visual

../visuals/q4-country-demand-map.png

### Findings

- Demand was concentrated in Western Europe.
- Netherlands, Germany and France exhibited strong demand.

### Business Recommendation

Expand marketing and distribution activities in high-demand regions.

---

## Tools Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Data Cleaning Techniques
- Data Visualisation

---

## Skills Demonstrated

- Data Cleaning
- Data Analysis
- Data Visualisation
- Business Intelligence
- Stakeholder Reporting
- Data Storytelling
