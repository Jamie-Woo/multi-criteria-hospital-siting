#  Dementia Care Hospital Site Selection (2024 Summer Alpha Tester Project)

This project analyzes regional data to identify the optimal location for establishing a new **Dementia Care Hospital** in South Korea. The project was conducted as part of the 2024 Summer Alpha Tester program(from IBAS, Big-Data club in Inha Univ.) and aims to support national dementia policies by leveraging spatial data science and multi-criteria decision analysis.

##  Project Summary

-  **Objective**: To select the most suitable location for a new dementia care hospital using PCA (Principal Component Analysis) and MCDM (Multi-Criteria Decision Making) techniques.
-  **Step 1**: Analyze regional indicators using PCA to determine the most suitable administrative district (시군구) — **Suwon City** was selected.
-  **Step 2**: Identify candidate hospitals in Suwon that meet the Ministry of Health and Welfare criteria.
-  **Final Selection**: Use the **TOPSIS** method (Technique for Order Preference by Similarity to Ideal Solution) to rank hospitals based on:
    - Accessibility (bus & subway distance)
    - Demand (elderly population)
    - Environmental factors (green space)
    - Welfare accessibility (senior welfare centers)
-  **Top-Ranked Facility**: **Withus Geriatric Hospital (위더스요양병원)**

##  Technologies & Tools

- Python (pandas, scikit-learn, folium, geopy)
- GeoJSON, GPKG (for spatial data)
- MCDM: TOPSIS methodology
- PCA for dimensionality reduction and weighting

##  Expected Impact

- Provides a data-driven methodology for future dementia hospital site selection.
- Improves resource allocation and minimizes infrastructure investment by reusing suitable existing hospitals.
