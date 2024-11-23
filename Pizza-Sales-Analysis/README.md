# 🍕 Pizza Sales Analysis
# How to Create an Excel Dashboard for Your Data Analytics Project

## 📑 Table of Contents

1. [📋 Project Overview](#project-overview)
2. [❓ Problem Statement](#problem-statement)
3. [🛠 Methodology](#methodology)
4. [💻 Technologies Used](#technologies-used)
5. [📂 Folder Structure](#folder-structure)
6. [📝 How to Use the Project](#how-to-use-the-project)
7. [📊 Data Collection](#data-collection)
8. [🧹 Data Preparation](#data-preparation)
9. [📈 Dashboard Overview](#dashboard-overview)
10. [🔑 Key Findings](#key-findings)
11. [⚠️ Limitations](#limitations)
12. [🚀 Conclusion and Recommendations](#conclusion-and-recommendations)

---

## 📋 Project Overview <a id="project-overview"></a>
This project focuses on developing an interactive Excel dashboard to analyze pizza sales data effectively. By leveraging data visualization techniques, the dashboard aims to reveal critical trends, track key performance indicators (KPIs), and provide actionable insights into sales performance, customer preferences, and operational efficiency.

Through a comprehensive analysis of the dataset, this project will highlight top-selling pizza varieties, seasonal sales patterns, and customer purchasing behaviors. Utilizing Microsoft Excel's powerful data cleaning, analytical, and visualization tools, the project showcases essential skills in transforming raw data into meaningful visual representations that can guide strategic business decisions.

The goal is to provide actionable insights for improving inventory management and marketing strategies.

---

## ❓ Problem Statement <a id="problem-statement"></a>
**Operational Challenges**: Difficulty optimizing performance and capitalizing on market opportunities. ⚠️

**Key Areas**:
- **Product Performance** 📊:
  - Identify top-selling pizzas and revenue contributions.
  - Issues with menu optimization and inventory (over/understocking).
  
- **Sales Trends** 📈:
  - Analyze seasonal and daily patterns.
  - Insufficient insights lead to ineffective marketing and staffing.

- **Efficiency Dashboard** 🖥️:
  - Need for a centralized decision-making tool.
  - Current lack results in reactive strategies and inconsistent service.

**Root Causes** 🔍:
- Poor understanding of sales trends and customer preferences.
- Leads to missed marketing opportunities and suboptimal inventory.

**Project Objectives** 🎯:
- Provide actionable insights.
- Transform data into business intelligence.
- Enable informed decisions.

**Expected Outcomes** 🌟:
- Agile and responsive operations.
- Customer-centric approach.
- Competitive advantage in the food sector.

**Ultimate Goal**: Leverage data for business success! 🚀📊

---

## 🛠 Methodology <a id="methodology"></a>
1. [📥 Data Import and Extraction](#data-import-and-extraction)
2. [📋 Requirements Gathering and Initial Data Assessment](#requirements-gathering-and-initial-data-assessment)
3. [🔍 Dataset Familiarization](#dataset-familiarization)
4. [🧹 Data Preparation and Cleaning](#data-preparation-and-cleaning)
5. [🔄 Data Transformation](#data-transformation)
6. [📈 Key Performance Indicator (KPI) Definition](#key-performance-indicator-kpi-definition)
7. [🎨 Data Visualization and Analysis](#data-visualization-and-analysis)
8. [🖥️ Dashboard Development](#dashboard-development)

---

## 💻 Technologies Used <a id="technologies-used"></a>

### **Microsoft Excel 365**
Microsoft Excel serves as the primary tool for this project, showcasing its capabilities in data analysis, visualization, and dashboard creation. Key features and techniques include:

- **Advanced Formulas** 🧮:
  - `SUMIFS`, `AVERAGEIFS`, and `COUNTIFS` for conditional aggregations.
  - `TEXT` for formatting dates and extracting specific time components.
  - `ROUND`, `UNIQUE`, and `COUNTA` for calculating metrics like average order value and total orders.
  
- **PivotTables** 📊:
  - Dynamic summarization of large datasets for trends and pattern analysis.
  - Grouping features to organize data by time (e.g., hours, days, months).

- **Charts** 📈:
  - Bar Charts to visualize sales trends by hour, day, and size.
  - Line Charts for tracking monthly sales trends and seasonal patterns.
  - Doughnut Charts to showcase top and bottom-selling pizzas.

- **Conditional Formatting** 🎨:
  - Highlighting key insights such as peak sales periods and missing values.
  - Using color scales for quick identification of high and low-performing metrics.

- **Slicers** 🎛:
  - Interactive filtering of data by pizza size, category, and time periods.
  - Enhancing user interactivity in the dashboard, enabling customized views.

- **Dashboard Design** 🖥️:
  - A polished, user-friendly interface with a focus on professional branding.
  - Integration of KPIs, charts, and slicers for a cohesive analytical tool.
  - Dynamic linking of all dashboard elements to underlying data for real-time updates.

**Why Microsoft Excel?**
This project demonstrates Excel’s versatility in handling real-world business problems, transforming raw data into actionable insights. The interactive dashboard highlights Excel's strength in bridging data analytics and decision-making.

---

## 📂 Folder Structure <a id="folder-structure"></a>

The project is organized into the following structure for ease of navigation and clarity:

- **📄 About-Me/**:  
  Contains a README with information about the author’s expertise and professional background.

- **📊 Dashboard/**:  
  Includes the interactive Excel dashboard built during the project, which contains KPIs, charts, and slicers.

- **📁 Dataset/**:  
  Holds the raw dataset used for data analysis.

- **🖼️ Images/**:  
  Stores visuals, such as screenshots of the dashboard, to enhance project understanding.

- **📜 LICENSE**:  
  Specifies the licensing details for the project (e.g., MIT License).

- **📝 README.md**:  
  The main documentation file detailing the project methodology, technologies, findings, and usage instructions.

---

## 📝 How to Use the Project <a id="how-to-use-the-project"></a>

Follow these steps to explore and interact with the project:

1. **📂 Access the Dataset**:  
   - Locate the dataset in the `Dataset/` folder.  
   - Open the `Pizza_Sales_Dataset.xlsx` file to review the raw data, including order details, pizza sizes, categories, and sales figures.

2. **📊 Interact with the Dashboard**:  
   - Navigate to the `Dashboard/` folder.  
   - Open the `Pizza_Sales_Dashboard.xlsx` file to explore the interactive dashboard.  
   - Use slicers and filters to customize your analysis by pizza size, category, and time periods.  

3. **🖼 Refer to Visual Guides**:  
   - Visit the `Images/` folder for screenshots of key charts, insights, and the final dashboard layout. These visuals provide a quick reference to the project’s outcomes and design elements.

4. **🔗 Access the GitHub Repository**:  
   - Explore the complete project repository on GitHub for detailed documentation, project files, and additional resources.  

5. **📖 Read the Documentation**:  
   - Refer to the `README.md` file in the root folder for an in-depth explanation of the project methodology, technologies used, and key findings.

---

### Tips for Best Experience:
- Ensure you have **Microsoft Excel 365 or a compatible version** installed to interact fully with the dashboard and its features.
- Check out the **slicers** and **interactive charts** for a dynamic analysis experience tailored to your needs.

---

## 📊 Data Collection <a id="data-collection"></a>

The dataset provides a comprehensive overview of pizza sales, capturing essential details necessary for effective analysis. Below are the key columns and their descriptions:

| **Column Name**         | **Description**                                                                 |
|--------------------------|-------------------------------------------------------------------------------|
| `order_details_id`       | Unique identifier for each order detail, ensuring no duplicate entries.       |
| `order_id`               | Identifier for each transaction, linking all items within a single order.     |
| `pizza_id`               | Unique identifier for each type of pizza sold, facilitating categorization.   |
| `quantity`               | Number of pizzas sold for each order detail, crucial for sales volume analysis. |
| `order_date`             | The date when the order was placed, useful for analyzing daily, weekly, and seasonal trends. |
| `order_time`             | The time when the order was placed, enabling analysis of peak sales hours.    |
| `unit_price`             | Price per unit of pizza, supporting revenue and pricing strategy analysis.    |
| `total_price`            | Total revenue generated per order detail, essential for calculating KPIs like Total Revenue and Average Order Value. |
| `pizza_size`             | Size of the pizza (e.g., Small, Medium, Large), providing insights into customer preferences. |
| `pizza_category`         | Category of the pizza (e.g., Classic, Veggie, Supreme) for performance analysis. |
| `pizza_ingredients`      | List of ingredients for each pizza, offering insights into popular toppings and customization preferences. |
| `pizza_name`             | Name of the pizza (e.g., "The Hawaiian Pizza"), used to identify top- and bottom-selling items. |

---

### **Dataset Highlights**:
- **Scope**: Covers a wide range of sales data across multiple categories, sizes, and time periods, enabling a detailed analysis of trends and customer preferences.  
- **Time-Based Insights**: Includes fields like `order_date` and `order_time` to allow granular time-series analysis, such as peak sales hours or seasonal demand patterns.  
- **Performance Metrics**: Fields like `quantity` and `total_price` form the foundation for calculating KPIs, helping measure business performance and operational efficiency.  

---

### **Dataset Source**:
This dataset is sourced from **Kaggle** as part of the **Pizza Restaurant Sales** collection. The data can be accessed and downloaded from the following link:  
[Pizza Restaurant Sales on Kaggle](https://www.kaggle.com/datasets/shilongzhuang/pizza-sales)

### **Dataset Licensing**:
- License: **Other (as specified on Kaggle)**  
- Contributor: **Shi Long Zhuang**  
- Context: This dataset is part of the **Maven Analytics Pizza Challenge**, which focuses on using data for actionable business insights.

---

### **Acknowledgment**:
This project leverages the **Pizza Restaurant Sales** dataset made available on Kaggle by **Shi Long Zhuang**. It originates from the **Maven Analytics Data Playground** and is used exclusively for educational and analytical purposes in this project.

Special thanks to:
- **Shi Long Zhuang** for the data contribution.
- **Maven Analytics** for hosting the Pizza Challenge and inspiring analytics projects.

For detailed license terms and dataset usage guidelines, refer to the following resources:
- [Kaggle Dataset](https://www.kaggle.com/datasets/shilongzhuang/pizza-sales)  
- [Maven Analytics - Pizza Challenge](https://www.mavenanalytics.io/blog/maven-pizza-challenge)

---


## 🧹 Data Preparation <a id="data-preparation"></a>

This section provides a comprehensive explanation of the steps followed to complete the project, from data import to insights generation.

### 1. 📥 Data Import and Extraction <a id="data-import-and-extraction"></a>
- **Download the Dataset**: Sourced the dataset from Kaggle ([Pizza Sales Dataset](https://www.kaggle.com/datasets/shilongzhuang/pizza-sales)).
- **Load into Excel**: Imported the dataset into Excel, ensuring all fields were properly mapped and no data was corrupted during import.

---

### 2. 📋 Requirements Gathering and Initial Data Assessment <a id="requirements-gathering-and-initial-data-assessment"></a>
- **Collaborated with Stakeholders**: Discussed project objectives, deliverables, and key questions, such as:
  - What are the top-performing pizzas?
  - When are peak sales periods?
  - How can the dashboard support decision-making?
- **Explored the Dataset**: Performed a high-level review to understand its structure, identify key fields, and highlight potential challenges like duplicates or missing values.

---

### 3. 🔍 Dataset Familiarization <a id="dataset-familiarization"></a>
- **Key Variables**: Reviewed essential columns, including:
  - `Order Date` and `Order Time` for time-based trends.
  - `Pizza Name`, `Pizza Size`, and `Pizza Category` for performance analysis.
  - `Quantity` and `Total Price` for revenue and sales metrics.
- **Aligned Objectives**: Confirmed that the dataset supports project goals, such as analyzing sales trends and identifying customer preferences.

---

### 4. 🧹 Data Preparation and Cleaning <a id="data-preparation-and-cleaning"></a>
- **Removed Duplicates**: Used Excel’s "Remove Duplicates" feature to clean up redundant rows.
- **Handled Missing Values**: Imputed missing revenue values using averages for respective pizza categories.
- **Standardized Formats**:
  - Reformatted the `order_date` column using the `DATEVALUE` function.
  - Cleaned inconsistent `pizza_name` entries using Excel's `TRIM` and `PROPER` functions.

---

### 5. 🔄 Data Transformation <a id="data-transformation"></a>
- **Created Calculated Fields**:
  - `Order Day`: Extracted day of the week using the `TEXT()` function.
  - `Order Month`: Extracted month names for monthly trend analysis.
  - `Order Hour`: Extracted the hour from the `order_time` field for hourly trend analysis.
- **Aggregated Data**:
  - Summarized sales data by category, size, and time periods using PivotTables.

---

### 6. 📈 Key Performance Indicator (KPI) Definition <a id="key-performance-indicator-kpi-definition"></a>
Defined and calculated critical KPIs, including:
- **Total Revenue**: Sum of all `total_price` values.
- **Total Orders**: Count of unique `order_id` values.
- **Average Order Value**: `Total Revenue ÷ Total Orders`.
- **Total Pizzas Sold**: Sum of all `quantity` values.

---

### 7. 🎨 Data Visualization and Analysis <a id="data-visualization-and-analysis"></a>
- **Selected Visuals**:
  - Bar charts for hourly, daily, and size-based sales.
  - Line graphs for monthly trends.
  - Doughnut charts for the top 5 best-selling and bottom 5 worst-selling pizzas.
- **Enhanced Readability**: Applied consistent color schemes and clear labels.

---

### 8. 🖥️ Dashboard Development <a id="dashboard-development"></a>
- **User-Friendly Layout**:
  - Positioned KPIs prominently at the top for easy reference.
  - Grouped related visuals logically for intuitive navigation.
- **Interactive Features**:
  - Added slicers for filtering by time period, pizza size, and category.
  - Included timelines to explore trends over specific months.

---

## 📈 Dashboard Overview <a id="dashboard-overview"></a>
The final dashboard includes:
- 📊 **Bar Chart:** Shows revenue contribution by pizza type.
- 📈 **Line Chart:** Displays monthly sales trends.
- 🎛 **Interactive Slicers:** Filter data by pizza type or date.

Here’s a preview of the dashboard:

![📊 Dashboard Screenshot](images/dashboard_screenshot.png)

---

## 🔑 Key Findings <a id="key-findings"></a>
1. 🍕 **Pepperoni Pizza** contributes 35% of total revenue, making it the top-selling item.
2. 📅 Sales peak on **weekends**, especially on Saturdays.
3. 🎄 **December** is the highest-performing month, indicating strong seasonal demand.

---

## ⚠️ Limitations <a id="limitations"></a>
- 📆 Dataset only covers one year, limiting long-term trend analysis.
- 🙍‍♀️ Customer demographic data is unavailable, preventing deeper segmentation.

---

## 🚀 Conclusion and Recommendations <a id="conclusion-and-recommendations"></a>
Focus on promoting best-selling pizzas, such as Pepperoni, during peak periods.
Optimize inventory and staffing for weekends and December sales surges.
Develop targeted marketing campaigns based on seasonal trends.

---

## 🤝 Contributing and Feedback
- Have suggestions or improvements? Feel free to open an issue or submit a pull request.
- If you found this project useful, please ⭐ star the repository!
