# 📦 Logistics & Supply Chain Performance Dashboard

## 📌 Project Overview
This project focuses on analyzing logistics and supply chain operations data to uncover the main drivers of delivery delays, operational risk, and shipping costs.

The client scenario assumes that raw operational data was provided without clear visibility into why delays occur or how costs and risks interact. The objective was to transform this raw data into a clear, interactive Excel dashboard that supports data-driven operational decisions.

Using Excel and Power Query, the project converts complex logistics data into actionable insights that help operations managers monitor performance, identify bottlenecks, and improve reliability.

---

## 🎯 Project Goals
- Understand why delivery delays happen and when they peak  
- Analyze the relationship between shipping cost and service reliability  
- Identify high-risk routes and geographic zones  
- Track key operational KPIs in a single, easy-to-use dashboard  
- Support better routing, scheduling, and risk-based decisions  

---

## 🛠 Tools & Technologies
- Microsoft Excel  
- Power Query (Data Cleaning & Transformation)  
- Pivot Tables & Pivot Charts  
- Excel Dashboards & Slicers  

---

## ⚙️ Data Preparation (Power Query)
Key steps performed in Power Query:
- Cleaned and standardized raw logistics data  
- Fixed data types (dates, numeric values, text fields)  
- Created time-based columns (Year, Month, Day, Hour)  
- Built Geo Zones by rounding latitude and longitude  
- Created operational bands:
  - Traffic Band (Low / Medium / High)
  - Route Risk Band (Low / Medium / High)
  - Weather Band (Mild / Moderate / Severe)
- Defined business flags (Late Delivery, On-Time, High Delay Risk)  
- Built an aggregated daily table to improve dashboard performance  

---

## 📊 Key KPIs Tracked
The dashboard highlights the most important logistics performance indicators:
- Total Shipping Cost (USD)  
- Average Inventory Level  
- Average Fuel Consumption (L/hr)  
- Average Loading Duration (Hours)  
- Equipment Availability %  
- Disruption Risk %  
- Cargo Condition Status %  
- On-Time Delivery %  

These KPIs provide a high-level snapshot of operational health.

---

## 📈 Dashboard Analysis Sections

### 🔹 Cost Analysis
- Monthly shipping cost trends  
- Top 10 most expensive geographic zones  

### 🔹 Delay & Risk Analysis
- Delay probability by Route Risk and Traffic Level  
- Top 10 delay-prone zones  
- Risk classification distribution (High / Moderate / Low)  

### 🔹 Time-Based Insights
- Monthly on-time delivery trends  
- Hourly and weekday delay patterns  

### 🔹 Cost vs Performance
- Scatter analysis showing shipping cost vs delay probability  
- Demonstrates that higher cost does not always mean better reliability  

---

## 💡 Key Insights
- Delivery delays are not random and peak during weekday rush hours  
- High-risk routes account for the majority of delays  
- Higher shipping costs do not guarantee better on-time performance  
- Certain geo zones are both costly and high-risk, requiring attention  
- Overall on-time performance remains relatively low (~62%)  

---

## ✅ Business Value
This dashboard enables stakeholders to:
- Quickly identify delay drivers  
- Balance cost vs reliability  
- Prioritize high-risk routes and zones  
- Improve scheduling and routing decisions  
- Move from reactive to data-driven operations management  

---

## 📂 Project Deliverables
- Cleaned dataset using Power Query  
- Interactive Excel dashboard with slicers and KPIs  
- Operational insights and recommendations  
- Dashboard-ready reporting structure  

---

## 📸 Dashboard Preview
A visual snapshot of the final dashboard is included in this repository to demonstrate layout, KPIs, and analytical depth.

---

## 🚀 How This Project Can Be Used
- Operations & supply chain performance monitoring  
- Logistics cost optimization analysis  
- Excel dashboard portfolio example  
- Real-world data analytics case study  
