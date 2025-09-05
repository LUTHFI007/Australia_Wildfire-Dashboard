# 🌏 Australia Wildfire Dashboard  

This project is an **interactive dashboard** built with [Dash](https://dash.plotly.com/) and [Plotly](https://plotly.com/python/).  
It allows users to explore **historical wildfire data in Australia** by selecting a **Region** and a **Year**, then visualizing:  

- 🔥 A **Pie Chart** of the *Monthly Average Estimated Fire Area*  
- 🌱 A **Bar Chart** of the *Monthly Average Count of Pixels for Presumed Vegetation Fires*  

---

## 📊 Dashboard Features  

- **Dropdown Menu**: Choose the **Year** of interest  
- **Radio Buttons**: Select the **Region** (e.g., NSW, NT, QL, etc.)  
- **Graphs**:
  - Pie chart for *Average Fire Area*  
  - Bar chart for *Vegetation Fire Pixel Count*  
- Clean, two-section layout:  
  - Left → Inputs (Region, Year)  
  - Right → Outputs (Graphs)  

---

## ⚙️ Requirements  

Install the required Python packages before running the app:  

```bash
pip install setuptools
pip install packaging
pip install pandas dash
pip install httpx==0.20 dash plotly
