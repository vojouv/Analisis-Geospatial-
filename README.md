# 🏥 Accessibility Analysis of Hospital Services in Urban Areas using Network Analysis (Cimahi vs Cirebon)

This project focuses on evaluating and comparing the accessibility of hospital services in **Cimahi and Cirebon**, two medium-sized cities in West Java, Indonesia, using **network analysis techniques**. The research applies spatial and graph-based methods to better understand the distribution and accessibility of healthcare infrastructure in rapidly urbanizing regions.

---

## 📌 Background

Healthcare is a fundamental human need and a key factor in ensuring quality of life. One of the primary indicators of equitable access to health services is the availability of well-distributed and efficiently accessible healthcare facilities — particularly **hospitals**, as referral centers for advanced treatment.

In the face of rapid urban population growth, challenges arise not only in the **availability** of hospitals but also in their **location and accessibility**. Accessibility is highly influenced by:
- Road network structures
- Hospital distribution
- Population density and spatial layout

---

## 🧭 Objectives

- Evaluate the **spatial accessibility** of hospital services in Cimahi and Cirebon
- Compare the **efficiency and equity** of access between both cities
- Apply **network centrality metrics** to assess urban connectivity to health services
- Provide insight for better health facility planning and urban development

---

## 🛠 Methodology

The following techniques and tools are applied in this project:

- 🗺 **Extracting road networks** from OpenStreetMap (OSM)
- 📊 **Statistical analysis** of road and hospital network structure
- 🔗 **Network centrality analysis**:  
  - Closeness Centrality  
  - Degree Centrality  
  - Betweenness Centrality
- 📍 **Buffering and proximity analysis** to hospitals
- 🧭 **Accessibility mapping** using spatial queries and network reachability
- 🖥 **Interactive mapping & visualization** of road networks and hospital POIs

---

## 🧪 Study Area & Data

- **Cities Analyzed:** Cimahi & Cirebon (West Java, Indonesia)
- **Data Source:**  
  - Road networks and hospital locations from **OpenStreetMap (OSM)**
  - Administrative boundaries from open geospatial repositories
- **Tools:**  
  - Python (OSMNX, NetworkX, Geopandas, Folium)  
  - QGIS for spatial preprocessing and visualization

---

## 📉 Limitations

1. Analysis is limited to **two administrative cities** and does not include surrounding districts that may rely on these hospitals.
2. OSM data is **crowdsourced** and may contain inaccuracies or incomplete features.
3. The analysis is **static (snapshot-based)** and does not consider temporal dynamics such as population growth, road development, or new facility construction.



