# Power BI Dashboard – Car Sales Analysis (Demo Project)

## Overview
This Power BI dashboard is created using **dummy / sample data**.  
The purpose of this project is to **demonstrate dashboard design, interactivity, and Power BI features**, not to represent real-world car sales data.

## Dataset
The dataset contains basic car-related information such as:
- Brand  
- Car Model Name  
- Country  
- Month  
- Price  

An additional calculated column **Car Type** is created using DAX to classify cars into:
- **Economy**
- **Mid Range**
- **Luxury**

This classification is only for demonstration purposes.

## Dashboard Components
The dashboard consists of the following visuals:

### 1. Table Visual
- Displays detailed car information including brand, model, country, month, price, and car type.
- Helps users view raw data in a structured format.

### 2. Line Chart
- Shows trends based on selected data (for example, price over months).
- Updates dynamically based on slicer selections.

### 3. Slicer – Car Type
- Allows users to filter data by **Economy**, **Mid Range**, or **Luxury**.
- When a car type is selected:
  - The **line chart** updates automatically.
  - The **table** shows only the selected category.

## Key Feature – Interactivity
The most important part of this dashboard is **interaction**:
- Selecting a value in the **Car Type slicer** dynamically updates all visuals.
- This demonstrates how Power BI dashboards respond to user input in real time.

## Purpose of the Project
- To demonstrate Power BI dashboard creation
- To showcase DAX calculated columns
- To show how slicers control visuals
- To present interactive reporting behavior

## Note
All data used in this project is **dummy data** created solely for learning and demonstration purposes.

---
