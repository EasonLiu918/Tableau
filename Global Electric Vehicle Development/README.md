# ISOM3330 - Global Electric Vehicle Development Dashboard

An interactive Tableau workbook that explores the rise of electric vehicles (EVs) around the world, built on **IEA Global EV Data 2024**.  
It lets users compare sales trends, BEV/PHEV market shares and regional adoption paths from 2010-2023, with forecast lines for future insight. :contentReference[oaicite:0]{index=0}:contentReference[oaicite:1]{index=1}

---

### 1 . Project files

| File | Purpose |
|------|---------|
| `project_electric_vehicle.twbx` | Packaged Tableau dashboard (open directly in Tableau Desktop) |
| `isom3330_project_global_electric_vehicle_development.pdf` | Short report describing data, design logic and use cases |

---

### 2 . Quick start

1. **Software** – Tableau Desktop 2023.3 or newer.  
2. **Open** `project_electric_vehicle.twbx`; all data is embedded, no connection setup required.  
3. **Interact**:
   * *Country filter* – focus on one or more markets.
   * *Powertrain switch* – toggle between **BEV** and **PHEV** views.
   * *Year selector* – change the pie-chart cross-section.
   * Hover or click for tooltips and drill-down.

---

### 3 . Data source

| Source | Link / Notes |
|--------|--------------|
| International Energy Agency – Global EV Data 2024 | Annual sales, market share, EV stock and charging infrastructure for 50+ economies |

Data range: **2010-2023**; dimensions: *Region*, *Year*, *Powertrain Type*, *Unit*; measures: *Sales volume*, *EV share %*, *Value*. :contentReference[oaicite:2]{index=2}:contentReference[oaicite:3]{index=3}

---

### 4 . Dashboard layout

1. **Global EV Sales Trend** – line chart with optional forecast.  
2. **BEV vs PHEV Trend** – second line chart driven by the parameter switch.  
3. **Powertrain Share** – pie chart for a user-selected year.  
Filters and parameters cascade to keep all three views in sync. :contentReference[oaicite:4]{index=4}:contentReference[oaicite:5]{index=5}

---

### 5 . Intended users & scenarios

* **Policymakers** – benchmark national incentive impact.
* **Industry analysts / OEMs** – gauge market maturity and plan capacity.
* **Researchers** – correlate charging infrastructure with adoption speed. :contentReference[oaicite:6]{index=6}:contentReference[oaicite:7]{index=7}

---

### 6 . How to extend

* Replace the embedded extract with a live IEA database or your own CSV.  
* Add calculated fields (e.g., CAGR, per-capita penetration).  
* Embed the workbook on Tableau Public for wider sharing.

---

### 7 . License

This project is educational (HKUST ISOM 3330).  
IEA data © International Energy Agency, used under academic fair-use.

