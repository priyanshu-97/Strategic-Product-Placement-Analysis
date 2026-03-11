# 📊 Strategic Product Placement Analysis using Tableau & Flask

![Tableau](https://img.shields.io/badge/Tableau-Data%20Visualization-blue)
![Python](https://img.shields.io/badge/Python-Flask-yellow)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# 📌 Project Overview

Retail businesses strategically place products in stores to improve visibility and increase sales.
This project analyzes how **product positioning, pricing strategies, promotions, consumer demographics, and store foot traffic** affect product sales performance.

The project uses **Tableau for data visualization** and **Flask for web integration**, allowing the dashboard and story to be embedded inside a web application.

The goal is to help businesses understand the **impact of product placement strategies** and make better data-driven decisions.

---

# 🎯 Problem Statement

Retail companies often struggle to determine how product placement and promotional strategies influence customer purchasing behavior. Without clear insights, businesses may fail to optimize store layouts and product visibility.

This project analyzes product positioning data to identify the key factors affecting sales performance using **interactive dashboards and data visualization techniques**.

---

# 📂 Dataset Information

Dataset Source
**Kaggle – Impact of Product Positioning on Sales**

The dataset includes information about product placement, pricing strategies, promotions, customer demographics, and sales performance.

### Dataset Attributes

| Column                | Description                                      |
| --------------------- | ------------------------------------------------ |
| Product ID            | Unique identifier for each product               |
| Product Position      | Placement of the product (Endcap, Aisle, Shelf)  |
| Price                 | Selling price of the product                     |
| Competitor Price      | Price offered by competitors                     |
| Promotion             | Indicates if promotional offers are available    |
| Foot Traffic          | Number of customers passing the product location |
| Consumer Demographics | Target customer group                            |
| Product Category      | Category of the product                          |
| Seasonal              | Indicates seasonal products                      |
| Sales Volume          | Quantity of products sold                        |

---

# 🛠 Tools & Technologies

| Tool           | Purpose            |
| -------------- | ------------------ |
| Tableau Public | Data Visualization |
| Python Flask   | Web Integration    |
| HTML / CSS     | Web Interface      |
| Kaggle Dataset | Data Source        |
| GitHub         | Version Control    |

---

# 🔄 Project Workflow

1. Problem Definition
2. Data Collection from Kaggle
3. Data Preparation and Cleaning
4. Data Visualization using Tableau
5. Dashboard Creation
6. Story Development
7. Performance Testing
8. Web Integration using Flask

---

# 🧹 Data Preparation

The dataset was imported into **Tableau** and prepared for analysis.

Preparation steps included:

* Checking data types
* Verifying dataset consistency
* Reviewing column structures
* Applying Tableau aggregation functions
* Preparing fields for visualization

---

# 📈 Data Visualizations

The following visualizations were created:

| Visualization                         | Purpose                         |
| ------------------------------------- | ------------------------------- |
| Avg Sales Volume vs Product Category  | Category performance comparison |
| Competitor Price vs Product Price     | Pricing competitiveness         |
| Avg Sales by Category & Position      | Product placement impact        |
| Consumer Demographics vs Sales Volume | Customer segment analysis       |
| Product Category vs Price             | Price comparison                |
| Avg Sales by Category by Season       | Seasonal impact                 |
| Foot Traffic vs Sales Volume          | Store traffic influence         |
| Promotion Impact on Price & Sales     | Promotional strategy analysis   |

Total Visualizations Created: **8**

---

# 📊 Dashboard

All visualizations were combined into a **Tableau Dashboard** that provides an interactive overview of the analysis.

Features of the dashboard:

* Interactive filters
* Comparative visualizations
* Customer demographic insights
* Product placement performance

---

# 🌐 Web Application Integration

To make the dashboard accessible via a web interface, a **Flask-based web application** was developed.

The web app allows users to navigate between:

* Home Page
* About Page
* Dashboard
* Story
* Contact Page

The Tableau dashboard and story are embedded into the website using **iframe integration**.

---

# 💻 Web Application Structure

```text
sales_tableau_flask_project

│── app.py

│── templates
│   │── index.html
│   │── about.html
│   │── dashboard.html
│   │── story.html
│   │── contact.html

│── static
│   │── css
│   │   └── style.css
│   │
│   │── images
│       ├── backgroud.jpg
│       └── about.jpg
```

---

# 🚀 Running the Web Application

To run the Flask application locally:

```bash
pip install flask
python app.py
```

Then open:

```
http://127.0.0.1:5000
```

---

# 🌍 Live Tableau Dashboard

View the published dashboard here:

https://public.tableau.com/views/ProjectBook_17732269076800/Productplacementanalysis-dashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

# 🔍 Key Insights

• Electronics products recorded the highest average sales volume.
• College students and families contribute significantly to total sales.
• Products placed in **high visibility areas such as endcaps** generate higher sales.
• Higher foot traffic locations strongly influence product sales performance.
• Promotional strategies help maintain stable sales across product categories.

---

# 📖 Tableau Story

View the published dashboard here:

https://public.tableau.com/views/ProjectBook_17732269076800/Productplacementanalysisstory?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

A Tableau Story was created to explain the analysis in a step-by-step format.
It highlights key insights related to:

* Product category performance
* Consumer demographics influence
* Product placement strategies
* Pricing comparisons

---

# ⚡ Performance Testing

Performance testing included the following aspects:

### Utilization of Filters

Filters used in the dashboard:

* Product Category
* Consumer Demographics
* Product Position
* Seasonal
* Promotion

### Calculation Fields

Custom calculated fields used: **0**

Tableau aggregation functions used:

* AVG(Sales Volume)
* AVG(Price)

### Number of Visualizations

Total visualizations created: **8**

---

# 🎥 Project Demonstration Video

Watch the complete project explanation here:

https://youtu.be/j0OmR48hSkY

The video explains:

* Problem statement
* Dataset overview
* Data preparation
* Tableau visualizations
* Dashboard walkthrough
* Key insights

---

# 📁 Repository Structure

```text
sales_tableau_flask_project

├── dataset
│   └── product_positioning_sales.csv
│
├── docs
│   └── dataset_description.md
|
├── screenshots
│   
├── tableau
│   └── Project book.twb
│
├── webapp
│   ├── app.py
│   ├── templates
│   └── static
│
└── README.md
```

---

# 📌 Conclusion

This project demonstrates how **data visualization and web integration can be used together to analyze retail product placement strategies**.

By combining **Tableau dashboards with a Flask web application**, the project provides an interactive platform for exploring data insights and understanding how product placement affects sales performance.

---

# 👨‍💻 Author

**Priyanshu kumar , Team 69**

---
