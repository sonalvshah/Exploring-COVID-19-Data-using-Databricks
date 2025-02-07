# **Analyzing the Relationship Between COVID-19 Vaccination Rates and Case/Mortality Trends**  

## **Project Overview**  
This project investigates whether higher **COVID-19 vaccination rates** are associated with **lower case numbers and reduced excess mortality**. By analyzing global data from **Our World in Data, the World Bank, and Wikipedia**, we assess vaccination impact across continents using **Databricks for data processing, analysis, and visualization**.  

## **Data Sources**  
- **Our World in Data** – COVID-19 case, vaccination, and mortality statistics  
- **World Bank** – Economic indicators, including GDP  
- **Wikipedia** – Additional demographic and country-specific details  

## **Methodology**  

### **1️⃣ Data Preparation & Cleaning**  
- The dataset is uploaded and processed using **Databricks**.  
- Missing, zero, or negative values in vaccination and case columns are removed.  
- The analysis focuses on data from **September and October 2021**, adding relevant time-based features.  

### **2️⃣ Statistical Analysis & Visualization**  
- **Continental trends** are analyzed by calculating average vaccination rates, new case counts, and excess mortality figures.  
- **Bar charts** are used to visualize the relationship between **vaccination rates and case numbers** across continents.  
- **Correlation analysis** quantifies the association between vaccination rates and new COVID-19 cases.  

### **3️⃣ Handling Missing GDP Data**  
- GDP data for **14 countries** is retrieved from the **World Bank and Wikipedia** to fill missing values.  
- This enriched dataset helps assess economic factors alongside vaccination and case trends.  

### **4️⃣ Summary Statistics & Findings**  
- A summary table highlights key insights, including **mean, standard deviation, and frequency** of variables like vaccination rates, case rates, and GDP.  
- The results support or challenge the hypothesis that **higher vaccination rates lead to fewer cases and reduced mortality**.  

## **Key Insights**  
📌 The analysis reveals trends in how vaccination rates impact COVID-19 case and mortality figures across different regions. The findings provide valuable insights into pandemic management and public health policies.  


