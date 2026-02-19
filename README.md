# 🚗 Car Marketplace Analysis Project

## 📌 Project Overview

This project focuses on analyzing the **Indian Used Car Marketplace** dataset collected through web scraping.  
The primary objective is to understand pricing trends, brand distribution, fuel and transmission preferences, and the major factors influencing used car prices.

Using **Exploratory Data Analysis (EDA)**, this project extracts meaningful insights to help:

- Buyers make informed purchase decisions  
- Sellers price vehicles strategically  
- Marketplaces understand demand patterns  

This project demonstrates the complete data analysis workflow — from web scraping to insight generation.

---

## ⭐ Project Highlights

- 📊 Analyzed real-world used car marketplace data  
- 🌐 Performed web scraping using Python  
- 🧹 Cleaned and transformed raw data  
- 🔍 Identified key price influencing factors  
- 🏙️ Compared pricing trends across cities  
- 🚘 Analyzed brand-wise and fuel-type distribution  
- 📉 Studied car age vs price depreciation  
- 📈 Built professional visualizations for insights  

---

## 🛠️ Tech Stack & Tools

### Programming Language:
- Python  

### Libraries Used:
- Pandas (Data manipulation)  
- NumPy (Numerical operations)  
- Matplotlib (Data visualization)  
- Seaborn (Statistical visualization)  
- BeautifulSoup (Web scraping)  
- Requests (HTTP requests)  

### Tools & Platforms:
- Jupyter Notebook  
- Git & GitHub  

---

## 🌐 Web Scraping Process

The dataset was collected from an online used car marketplace website using Python.

### Steps:

1. Sent HTTP requests to fetch webpage content  
2. Parsed HTML using BeautifulSoup  
3. Extracted important features:
   - Brand  
   - Price  
   - Fuel Type  
   - Transmission  
   - Year  
   - KM Driven  
   - City  
4. Stored the extracted data into CSV format  
5. Prepared dataset for further analysis  

This process helped gather structured marketplace data for EDA.

---

## 🧹 Data Cleaning & Preparation

Before analysis, the dataset contained:

- Missing values  
- Duplicate entries  
- Inconsistent formatting (₹ symbol, commas, text like “km”)  
- Unnecessary columns  

### Cleaning Steps:

- Removed duplicate records  
- Handled missing values  
- Converted price and km driven into numeric format  
- Standardized column names  
- Created new feature: **Car Age (Current Year – Manufacturing Year)**  
- Corrected data types  

After cleaning, the dataset became structured and analysis-ready.

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to identify patterns, relationships, and trends in the dataset.

### Major Analysis Performed:

- Top 8 brands by number of used car listings  
- Correlation between Price, Year, and KM Driven  
- Top 10 cities with highest average car prices  
- Fuel Type vs Transmission distribution  
- Car Age vs Median Price  
- Mileage trend with increasing car age  

A correlation matrix was used to understand relationships between numerical variables.

---

## 💡 Key Insights

- 🚘 **Car Age is the strongest factor affecting price.**  
- 📉 Sharp price depreciation occurs after 2 years.  
- ⛽ Petrol cars dominate the used car market.  
- ⚙️ Manual transmission vehicles are more common than automatic.  
- 🏙️ Used car prices vary significantly across cities.  
- 📊 Price and mileage show a weak negative correlation.  
- 🏷️ Brand popularity impacts resale presence and pricing.  

---

## 📈 Visualizations Created

- 📊 Bar Chart – Top 8 Brands by Listings  
- 🔥 Heatmap – Correlation Matrix  
- 📊 Bar Chart – Top 10 Cities by Average Price  
- 📉 Count Plot – Fuel Type vs Transmission  
- 📈 Line/Bar Plot – Car Age vs Median Price  
- 📊 Distribution Plot – Price Distribution  

These visualizations helped convert raw data into clear business insights.

---

## 🎓 What I Learned

Through this project, I gained hands-on experience in:

- Real-world data scraping  
- Data cleaning and preprocessing  
- Handling missing and inconsistent data  
- Performing exploratory data analysis  
- Creating professional visualizations  
- Extracting business insights from raw data  

This project strengthened my understanding of the complete data analysis lifecycle.

---

## 🚀 Future Enhancements

- 🤖 Build a Machine Learning model to predict used car prices  
- 📊 Develop an interactive dashboard using Power BI or Tableau  
- 🌐 Deploy as a web-based application  
- 📌 Include more features like ownership type and insurance status  
- 📈 Expand dataset for deeper market analysis  

---

## ✅ Conclusion

This project provided a comprehensive understanding of trends in the Indian used car marketplace.

Key conclusions:

- Car age significantly impacts pricing  
- Fuel type and transmission affect availability  
- Brand and city influence resale value  
- Mileage impacts price when combined with other factors  

The insights derived can support better pricing strategies and data-driven decision-making for buyers and sellers.

---

## 👩‍💻 Author

**Vaishnavi Mahadev Chougule**  
B.Sc. in Computer Science  
Shivaji University, Kolhapur  

---

## 🔗 Connect With Me  

- 💼 LinkedIn: https://www.linkedin.com/in/vaishnavi-chougule-3b7206323      
- 💻 GitHub: https://github.com/vaishnavi-chougule    
