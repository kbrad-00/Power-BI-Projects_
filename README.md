# 📊 Data Jobs Dashboard (Power BI)

## 📚 Project Inspiration
This project was inspired by the Power BI data analytics tutorial created by Luke Barousse.

I followed Luke’s tutorial to build the main **Data Jobs Dashboard**, which analyzes job postings in the data industry. The tutorial guided the process of building the data model, writing DAX measures, and creating the primary dashboard visuals using the provided dataset.

While the main dashboard structure closely follows the tutorial, I expanded the project by designing an additional **drill-through dashboard** to explore individual job roles in greater detail.

---

# 🎯 Project Goal

Navigating the data job market can feel overwhelming, with information about skills, salaries, and job requirements scattered across different websites.

I created this dashboard to help simplify that process.

As someone interested in entering the data field, I often found myself asking questions like:

- What skills should I study?
- Which data jobs are most in demand?
- What tools do employers expect candidates to know?

This dashboard analyzes a **real-world dataset of 2024 data-related job postings**, containing information about job titles, salaries, required skills, and locations.

The goal is to turn that raw data into clear insights that help answer those questions.

Designed with **job seekers, career switchers, and aspiring data professionals** in mind, the dashboard provides an interactive way to explore:

- which skills appear most frequently in job postings  
- how salaries compare across different data roles  
- where jobs are located globally  
- what job platforms and work conditions are common  

By bringing these insights into one place, this project helps make the data job market easier to understand and allows users to quickly identify which skills and career paths are worth focusing on.

---

# 🗂 Dataset

The dataset contains **2024 data-related job postings** and includes information such as:

- Job titles  
- Salary estimates (yearly and hourly)  
- Required skills  
- Job locations  
- Work-from-home availability  
- Degree requirements  
- Job benefits and schedule types  

This dataset allows the dashboard to analyze job market trends and skill demand within the data analytics industry.

---

# 🧰 Tools & Technologies Used

- **Power BI Desktop** – Data visualization and dashboard development  
- **Power Query** – Data cleaning and transformation (ETL)  
- **DAX (Data Analysis Expressions)** – Creating calculated measures and metrics  
- **Star Schema Data Modeling** – Organizing fact and dimension tables for efficient analysis  

---

# 📊 Dashboard Overview

This Power BI dashboard analyzes job market data and provides insights into salaries, skill demand, job platforms, and work conditions.

The project includes multiple interactive views that allow users to explore job market trends and drill deeper into specific roles.

---

# 🖥 Main Data Jobs Dashboard

![Main Dashboard](datadashboard%20main.png)

The **Main Data Jobs Dashboard** provides a high-level overview of the data job market.

Key insights shown on this page include:

• **Total Job Postings** – Displays the total number of data-related job listings in the dataset.  
• **Skills per Job** – Shows the average number of skills required per job posting.  
• **Median Salary Metrics** – Highlights the median yearly and hourly salary across all jobs.  
• **Top Skills in Data** – A bar chart displaying the most frequently mentioned skills in job postings, helping identify which tools and technologies are most in demand.  
• **Top Paying Data Roles** – Shows which job titles have the highest median salaries.

Interactive elements such as **slicers and buttons** allow users to filter the dashboard by job title or country and toggle between job counts and percentages.

---

# 🔎 Job Title Drill-Through Dashboard

![Drill Through Dashboard](datadashboard%20drill.png)

The **Job Title Drill-Through Dashboard** allows users to explore detailed insights for a specific job role.

By clicking on a job title in the main dashboard, users can drill through to this page to see role-specific analytics.

This page includes:

• **Median Yearly and Hourly Salary Gauges** – Displays salary ranges and averages for the selected role.  
• **Work From Home Percentage** – Shows how often the role appears in remote job listings.  
• **Degree Requirement Percentage** – Indicates how many job postings mention a degree requirement.  
• **Health Insurance Availability** – Displays the proportion of jobs that offer health insurance benefits.  
• **Global Job Distribution Map** – Shows where job postings for the selected role are located around the world.  
• **Job Posting Platforms** – Highlights which platforms most commonly host postings for the role.  
• **Job Schedule Type** – Displays the distribution of full-time, part-time, contract, and internship roles.

This drill-through page enhances the dashboard by providing **role-level insights**, allowing users to analyze the characteristics of specific data careers.

---

# 📈 Salary Comparison Analysis

## Job Percent vs Median Hourly Salary

![Hourly Salary Comparison](job%20percent%20and%20median%20hourly%20sal.png)

This visualization compares **job availability with hourly salary levels** across different data roles.

It highlights which roles offer higher hourly compensation relative to how frequently they appear in job postings.

---

## Job Percent vs Median Yearly Salary

![Yearly Salary Comparison](job%20percent%20and%20median%20yearly%20salary.png)

This chart compares **job demand with yearly salary levels**, helping identify roles that combine strong demand with high compensation.

It provides insight into which data careers may offer the best long-term opportunities.

---

# 🧠 Skills Demonstrated

This project demonstrates several key **data analytics and Power BI skills**:

### 🎨 Dashboard Design
Creating a clean and intuitive layout to clearly present job market insights and salary trends.

### ⚙️ Power Query (ETL)
Preparing and transforming the dataset by cleaning fields, shaping tables, and organizing the data for analysis.

### 🔗 Data Modeling
Building a **star schema data model** with fact and dimension tables to improve performance and analytical flexibility.

### 🧮 DAX Calculations
Developing measures and calculations to generate key metrics such as job counts, salary insights, and skill demand.

---

# 📊 Visualizations Used

- 📈 **Bar & Column Charts** – Comparing job roles and skill demand  
- 🗺️ **Map Charts** – Visualizing global job distribution  
- 🔢 **KPI Cards** – Highlighting important metrics like job counts and salary statistics  
- 🍩 **Donut Charts** – Displaying job characteristics such as remote work availability and benefits  

---

# 🖱 Interactive Features

- 🎚 **Slicers** – Filter the dashboard by job title and country  
- 🔘 **Buttons & Bookmarks** – Toggle between:
  - Job Count vs Job Percentage
  - Yearly vs Hourly Salary
- 🔎 **Drill-Through Analysis** – Navigate to detailed role-level insights

---

# 📂 Dashboard File

You can find the Power BI file for this project here:

`Data_Jobs_Dashboard_2.0.pbix`

---

# 🚀 Project Value

This project demonstrates the ability to:

- Build interactive dashboards in Power BI  
- Design efficient data models  
- Create analytical insights using DAX  
- Implement advanced Power BI interactivity (bookmarks, slicers, and drill-through pages)

It also highlights the ability to **extend tutorial-based learning with custom dashboard development**, a key skill for real-world data analytics projects.
