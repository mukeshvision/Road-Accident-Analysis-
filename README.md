# Road Accident Analysis Dashboard | Power BI

This Power BI project provides a comprehensive visual analysis of road accident data to identify trends, high-risk conditions, and areas of concern. The dashboard compares **Current Year (CY)** and **Previous Year (PY)** casualties, analyzes accident severity, light and weather conditions, vehicle types, and urban vs. rural distribution to support better policy and safety decisions.

---

## Project Objective

The goal of this project is to uncover valuable insights from road accident data using interactive Power BI dashboards. This helps transport authorities and analysts:
- Understand monthly and seasonal trends in road casualties
- Identify high-risk factors like poor lighting, adverse weather, or specific vehicle types
- Compare yearly casualty trends to evaluate safety interventions

---

## Tools & Technologies

- Microsoft Power BI
- Excel for data preprocessing
- DAX for custom measures
- Power Query for data shaping

---

## Key Dashboard Features

### 1. **CY vs PY Casualties Analysis**
- Compares monthly-trained casualties between current and previous years
- Highlights performance drop or improvement visually

### 2. **Accident Severity Breakdown**
- Visual segmentation of accidents into fatal, serious, and slight
- Supports targeting specific accident types for reduction

### 3. **Vehicle Type Involvement**
- Analyzes which vehicle types (cars, bikes, trucks) are most involved
- Helps prioritize vehicle-based safety initiatives

### 4. **Environmental Factors**
- Accidents by:
  - **Light Conditions** (daylight, darkness with/without street lights)
  - **Weather Conditions** (rain, fog, fine weather)
- Insights into how external conditions impact road safety

### 5. **Urban vs Rural Area Comparison**
- Identifies geographical patterns in accident severity and frequency
- Supports location-based enforcement and road design planning

---

## Dataset Overview

- **Source**: US Government Road Accident Records (Kaggle)
- **Format**: Excel (.xlsx)
- **Key Columns**:
  - `Accident_Date`, `Time`, `Accident_Severity`
  - `Number_of_Casualties`, `Vehicle_Type`, `Light_Conditions`, `Weather_Conditions`
  - `Urban_or_Rural_Area`, `Road_Type`, `Speed_limit`, `Local_Authority_(District)`

