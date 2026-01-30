# intel-repurposing-strategy-analysis

## Objective
Analyze Intel’s device repurposing program in 2024 to evaluate energy savings, CO₂ reductions, and environmental impact. The goal is to provide data-driven recommendations to optimize sustainability efforts and maximize the environmental benefits of repurposed devices.

---

## Data
- **Datasets:** `intel.device_data` and `intel.impact_data`  
- **Key Metrics:**
  - Device type (Laptop/Desktop) and model year  
  - Usage purpose (Education, Corporate, Government, Environmental, Social Impact)  
  - Energy savings per year (kWh)  
  - CO₂ emissions avoided per year (kg)  
  - Recycling rate (%)  
  - Repurposing region (North America, Europe, Asia)  
- **Scope:** All repurposed devices in 2024 (~601,740 devices)

---

## Tools
- SQL for data aggregation, joins, and analysis  
---

## Analysis Overview
- Joined device and impact data to calculate **device age** and **age buckets** (`newer`, `mid-age`, `older`)  
- Aggregated total energy savings and CO₂ reductions by:
  - Device type  
  - Device age  
  - Region  
- Calculated regional contributions and identified high-impact device types for targeted sustainability efforts  

---

## Key Insights
- **Device Type:** Laptops make up the majority of repurposed devices and contribute the largest total energy savings and CO₂ reductions. Desktops contribute meaningfully to energy savings, particularly in Asia.  
- **Device Age:** Older devices save more energy (~48 kWh/year) and CO₂, while mid-age devices provide meaningful impact; newer devices provide smaller but still valuable benefits.  
- **Regional Impact:** Regions with high-carbon electricity grids (e.g., parts of Asia) yield higher CO₂ reductions per kWh saved. North America, with large device volumes, contributes substantial overall savings.  
- **Overall:** Intel repurposed over 600,000 devices in 2024, saving significant energy and reducing emissions equivalent to powering ~24 U.S. households or removing 1,472 cars from the road for a year.  

---

## Recommendations
- Prioritize **mid-age and older laptops**, particularly in **high-carbon-intensity regions** such as Asia.  
- Target desktops strategically in regions where their energy savings are proportionally high.  
- Consider adding **cost-effectiveness metrics** (energy or CO₂ saved per dollar) to balance sustainability with operational efficiency.  
- Scale repurposing strategically to maximize environmental impact while extending device lifespans.  

---

## Deliverables
- SQL queries used to join, clean, and aggregate the data   
- Summary report with energy savings, CO₂ reductions, and actionable recommendations  
---
