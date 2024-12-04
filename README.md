# **Sales Data Analysis Project**

## **Overview**  
This project demonstrates a complete sales data analysis pipeline using Microsoft Excel. From validating raw data to creating a dynamic dashboard, the aim was to derive actionable insights and provide an interactive platform for understanding sales performance.

---

## **Project Structure**  

| **File Name**      | **Description**                                                                                   |
|---------------------|---------------------------------------------------------------------------------------------------|
| `Sales Project.xlsx`| Complete project workbook including data cleaning, calculations, and dynamic dashboard.           |
| `Sales Data.xlsx`    | Dataset for practice, containing raw sales and master data tables.                                |
| `Sales Dashboard.png`     | Screenshot of the dynamic dashboard showcasing key metrics and visuals.                          |
| `README.md`         | Project documentation and guidelines for exploration.                                            |

---

## **Workflow and Methodology**  

1. **Data Validation**  
   - Verified the dataset to ensure it had no duplicates, null values, or errors.  
   - Ensured correct data types for all columns (Currency (English - United States) for prices, Numeric for quantities, Date for date fields, etc).  

2. **Data Enrichment**  
   - Referenced the **Master Data Table** to enrich the **Input Data Table** with additional columns:  
     - **Product Name**, **Category**, **UOM**, **Buying Price**, **Selling Price**.  
   - Created calculated fields:  
     - **Total Buying Price** = Quantity × Buying Price  
     - **Total Selling Price** = Quantity × Selling Price × (1 - Discount)  

3. **Data Modeling and Analysis**  
   - Leveraged Power Pivot to build relationships between data tables.  

4. **Dynamic Dashboard Creation**  
   - Developed a user-friendly dashboard with slicers for:  
     - Year  
     - Month  
     - Sales Type  
     - Payment Type  

   - Key visualizations include:  
     - **Top Products** and **Top Categories**.  
     - **Sales Trends** (by day and month, with Profit %).  
     - **Sales Distribution** by Payment and Sales Type.  
     - **Buying vs. Selling Prices** for each product.  
     - **Category-Wise Sales**.  

---

## **Key Insights**  

- **Profitability Analysis**: Monthly profit percentages revealed periods of high profitability.  
- **Top Performers**: Identified the most popular products and categories driving sales.  
- **Trends & Patterns**: Analyzed sales behavior across different sales types and payment modes.  
- **Pricing Insights**: Highlighted the relationship between buying and selling prices for each product.  

---

## **Tools & Techniques Used**  

| **Tool/Technique**          | **Purpose**                                                                                 |
|------------------------------|---------------------------------------------------------------------------------------------|
| **Microsoft Excel**          | Data validation, enrichment, and dashboard creation.                                       |
| **Power Pivot**              | Relationship building and advanced analytics.                                              |
| **Slicers and Pivot Tables** | Enhanced interactivity and visualization in the dashboard.                                 |

---

## **How to Explore the Project**  

1. Download the repository files, especially:  
   - `Sales Project.xlsx`  
   - `Sales Data.xlsx`  
   - `Sales Dashboard.png`  

2. Open `Sales Project.xlsx` in Microsoft Excel to explore the project, including the dynamic dashboard.  
3. Use `SalesData.xlsx` for hands-on practice with raw data.  

---

## **Contact**  
For questions, collaborations, or feedback, feel free to reach out:  

- **Email**: [engysead498@gmail.com]  
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/engy-saeed-b47784276?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B0pTrqhMeRg2bmvRhVG53Aw%3D%3D)  
