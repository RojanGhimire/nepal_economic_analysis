# Nepal Inflation & Remittance Analysis (2010–2024)

## 📌 Project Overview
This project analyzes Nepal's **inflation trends** and **remittance inflows** over the period 2010–2024 using official economic data.  
The goal is to explore how remittances may influence economic stability and visualize key trends affecting households and the national economy.

---

## 🛠 Tools & Libraries
- **Python** – Programming language for data analysis  
- **Pandas** – Data manipulation and cleaning  
- **NumPy** – Statistical analysis and calculations  
- **Matplotlib** – Visualizing trends and relationships  

---

## 📊 Data Sources
1. **World Bank** – Consumer Price Index (CPI) / Inflation data  
2. **World Bank** – Remittance inflows data (Personal remittances received, USD)  

All datasets are publicly available and processed for Nepal only.

---

## 🔍 Analysis Performed
1. **Data Cleaning:** Removed missing values, standardized column names, converted data types.  
2. **Exploratory Data Analysis (EDA):**  
   - Trend analysis of inflation and remittance over 2010–2024  
   - Statistical summaries: mean, median, correlation between remittance and inflation  
3. **Visualization:**  
   - Line plots showing inflation and remittance trends  
   - Dual-axis plots to compare inflation and remittance together  
   - Scatter plot for relationship between remittance inflows and inflation  
4. **Insights:** Derived meaningful economic observations from trends and correlations.

---

## 📈 Key Insights
- **Remittance inflows increased steadily** after 2015, providing significant support to household incomes.  
- **Inflation spikes** correlate with global economic shocks, such as fuel crises and the COVID-19 pandemic.  
- The **correlation between remittance and inflation** is weak, suggesting that remittances primarily support household consumption rather than affecting inflation directly.  
- Nepal’s economy is **heavily dependent on remittances**, highlighting their role in economic stability.

---

## 📂 Repository Structure

This is how the project is organized:

📦 nepal-economic-analysis <br>
 ┣ 📊 data/                  # Raw datasets (inflation & remittance)<br>
 ┃ ┣ inflation.csv<br>
 ┃ ┗ remittance.csv<br>
 ┣ 📓 nepal_inflation_remittance_analysis.ipynb  # Main analysis notebook<br>
 ┣ 📈 charts/                 # Visualizations saved as images<br>
 ┃ ┣ line_plot.png<br>
 ┃ ┗ scatter_plot.png<br>
 ┗ 📄 README.md               # Project overview & insights<br>

