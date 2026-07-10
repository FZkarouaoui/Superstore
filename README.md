# Context

This project is a Power BI dashboard created to better understand **the performance of this Superstore**. It aims to analyze total sales, total profit, profit margin, and transactions over time, with a comparison to the previous year's performance in order to better understand the store's business operations.

This analysis is also performed based on customer segments, product categories, and sub-categories. In addition, it includes an analysis of the different regions according to Sales, Profit, and Profit Margin, with filters and other interactive slicers that allow users to customize their analysis.


# Dashboard Preview
## Main Dashboard
![Page Dashboard](image/Dashboard.png)
---

## Interactive Analysis Page
![Page Slicer](image/Slicer.png)
---

# Download
The Power BI project is available in two versions.

### Microsoft Power BI Version:
 [Download Power BI Project](store_project_ver_final_Microsoft_PBI.rar)
### Power BI Desktop Version
[Download Power BI Desktop Project](store_project_ver_final_PBI_Descktop.rar)



# Dataset

## Source

The dataset comes from Kaggle:

https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

## Metadata

### Sales Table

* **Row ID** → Unique ID for each row.
* **Order ID** → Unique Order ID for each customer.
* **Order Date** → Date when the order was placed.
* **Ship Date** → Shipping date of the product.
* **Ship Mode** → Shipping mode selected by the customer.
* **Customer ID** → Unique ID for each customer.
* **Customer Name** → Customer's name.
* **Segment** → Customer segment.
* **Country** → Customer's country.
* **City** → Customer's city.
* **State** → Customer's state.
* **Postal Code** → Customer's postal code.
* **Region** → Region where the customer belongs.
* **Product ID** → Unique ID for each product.
* **Category** → Product category.
* **Sub-Category** → Product sub-category.
* **Product Name** → Product name.
* **Sales** → Sales amount.
* **Quantity** → Quantity sold.
* **Discount** → Discount applied.
* **Profit** → Profit or loss.

### Date Table

* **Date** → Automatically generated.
* **Day** → Day.
* **Month**, **Month Abbreviation**, **Month Name** → Different month formats.

---

# Tools & Technologies

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Microsoft Excel (Data Source)

---

# Steps Completed

* Imported the CSV dataset into Power BI.
* Understood the dataset and defined the business questions.
* Cleaned the data and verified the data types using Power Query.
* Selected the KPIs, charts, and color palette.
* Created the Date table and its columns.
* Created relationships between the tables.
* Created DAX measures and parameters.
* Built the charts, KPI cards, filters, and adjusted the dashboard colors.
* Managed the interactions between the visuals.
* Created bookmarks.
* Created custom buttons using personalized images.

---

# Brief Analysis

In this section, we present some insights from the dashboard.

The main KPIs (Total Sales, Total Profit, Total Transactions, and Profit Margin) show an overall increase over time, which indicates an improvement in the Superstore's business performance. The only exceptions are a slight decrease in Total Sales in 2015 and a 5% decrease in Profit Margin in 2017.

Overall, the store achieved good performance, with an **average Profit Margin of 12.47%** across all years.

During these years, the Superstore generated **286K** in profit, mainly from three product types: **Copiers, Phones, and Accessories**, which together generated **142K** in profit. However, the store lost **18K** on **Tables** and about **4K** on **Bookcases** and **Supplies**.

The last three charts can be displayed in three different versions: **Sales, Profit, and Profit Margin**.

* **Customer Segment:** The **Consumer** segment generates the highest sales and profit, followed by the **Corporate** segment. However, the **Home Office** segment has the highest Profit Margin.

* **Product Category:** Technology is the category with the highest Sales, Profit, and Profit Margin. Office Supplies ranks second in Sales but is not very profitable, with only **2.49%** Profit Margin.

* **Region:** The regions can be divided into two groups. **West** and **East** show the strongest performance, while **South** and **Central** form the second group, with a noticeable performance gap between these two groups.
