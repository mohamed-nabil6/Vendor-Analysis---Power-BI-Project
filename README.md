
# Vendor Analysis - Power BI Project

This project is a **Vendor Analysis Dashboard** created in Power BI, designed to provide insights into vendor performance, annual invoice trends, and quantity metrics. The dashboard segments vendors based on quantity and invoice value, enabling data-driven decision-making for vendor management and procurement.

---

## Project Overview

### Objective

The goal of this dashboard is to:
- Evaluate vendor performance on an annual and monthly basis.
- Identify top vendors based on invoice amounts and quantity supplied.
- Compare year-over-year (YoY) vendor performance.
- Segment vendors by invoice and quantity clusters to better understand distribution and performance patterns.

### Key Features

- **Annual Overview**: Provides a snapshot of KPIs including total invoices, vendor count, product count, and total quantity.
- **Year-over-Year (YoY) Comparison**: Highlights vendor performance changes across years.
- **Monthly Trends**: Visualizes monthly invoice trends to identify peak and low-performing months.
- **Vendor Clustering**: Groups vendors based on quantity and invoice value to simplify analysis and segmentation.

---

## Dashboard Structure

The Power BI dashboard is organized into three main reports:

### 1. Annual Vendor Performance & Invoice Trends


![Annual Vendor Performance   Invoice Trends](https://github.com/user-attachments/assets/60184daf-3846-4e2a-8769-b29aa9179bab)

**Description**: This report provides an overview of vendor performance and invoice trends throughout the current and previous year.

- **KPIs**:
  - **Total Invoices**: Shows the total invoice value.
  - **Vendor Count**: Total number of active vendors.
  - **Product Count**: Total number of products sourced.
  - **Total Quantity**: Aggregate quantity ordered from vendors.

- **Charts**:
  - **Current Year vs. Last Year by Vendor**: A bar chart displaying vendor invoice values for the current and previous year, aiding in YoY performance evaluation.
  - **Total Invoice by Month**: A line chart tracking monthly invoice values, with annotations for the highest and lowest performing months.
  - **Total Invoice & Vendor Name**: A ranked list showing vendors by total invoice amount.

### 2. Year-over-Year Invoice Comparison


![Year-over-Year Invoice Comparison](https://github.com/user-attachments/assets/e0e0fd9f-7c8d-4439-90aa-278026f92c10)

**Description**: This report focuses on the year-over-year comparison of vendor invoice amounts, highlighting changes in performance.

- **Charts**:
  - **Yearly Comparison by Vendor**: Detailed comparison of invoice values for each vendor over the past two years.
  - **Total Invoice & Vendor Name**: A ranked list of vendors by invoice totals, facilitating quick identification of top-performing vendors.

### 3. Vendor Performance and Invoice Analysis


![Uploading Vendor Performance and Invoice Analysis.png…]()

**Description**: This report categorizes vendors by clusters based on quantity and invoice value, providing insights into vendor segmentation.

- **Charts**:
  - **Top Vendor Invoices**: Identifies the top vendors based on total invoice amounts.
  - **Quantity Clusters**: Groups vendors based on quantity ranges (e.g., “less than 100,” “2k-4k”), helping identify distribution patterns.
  - **Invoice Clusters**: Groups vendors by total invoice values.
  - **Total Quantity & Vendor Count by Quantity Cluster**: Displays total invoices, vendor count, and total quantity by quantity clusters.
  - **Total Invoice & Vendor Count by Sales Cluster**: Visualizes invoices, vendor count, and quantity segmented by sales clusters.

---

## Data Filters

The dashboard includes several filters to allow users to narrow down their analysis:

- **Year**
- **Quarter**
- **Month**
- **Vendor Name**
- **Product Description**
- **Invoice and Quantity Clusters**

## DAX Measures

Here are some key DAX measures used in the dashboard:

---
