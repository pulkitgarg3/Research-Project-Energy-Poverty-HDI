# 🔬 Research Project

## 🧩 Assessing the Impact of Energy Poverty on Human Development and Alignment with SDG 7: A State-Level Analysis in India

---

### 📖 Overview

This project investigates the **multidimensional nature of energy poverty** in India and its influence on the **Human Development Index (HDI)** at the state level. Using advanced econometric methods, the study constructs a **Multidimensional Energy Poverty Index (MEPI)**, analyzes its statistical relationship with HDI, and aligns the findings with **Sustainable Development Goal 7 (Affordable and Clean Energy for All)**.

The analysis is rooted in data from three National Family Health Survey (NFHS) rounds and incorporates indicators across access, affordability, and policy timelines — offering insights into regional disparities and recommending targeted interventions.

---

### 🎯 Objectives

1. **Construct a Multidimensional Energy Poverty Index (MEPI)**  
   - Incorporating electricity, clean cooking fuel, and financial inclusion indicators  
   - Apply PCA, Equal, and Entropy weighting schemes

2. **Analyze the impact of MEPI on Human Development**  
   - Employ Fixed-Effects Panel Regression  
   - Include interaction terms to capture temporal policy effects

3. **Cluster Indian States based on MEPI and HDI**  
   - Use K-means clustering to visualize disparities and development levels

4. **Identify trends and policy shifts over time**  
   - Highlight the effect of schemes like Ujjwala Yojana and Saubhagya

5. **Align the analysis with SDG 7 goals**  
   - Evaluate India’s progress towards universal clean and affordable energy

---

### 📚 Data Sources

- **NFHS-3, NFHS-4, NFHS-5 (2005–2021)**  
- **UNDP State-wise HDI dataset (1990–2022)**  
- **MoSPI – Energy Statistics India (2024)**  
- **RBI and Census – Socio-economic variables (e.g., literacy, IMR)**

---

### 🧮 Methodology

#### 1. MEPI Construction
- Indicators:
  - % of households with electricity
  - % of households using clean cooking fuel
  - % of women with access to a bank account
- **Primary method:** Principal Component Analysis (PCA)
- Also used: Equal and Entropy weighting for robustness checks

#### 2. Panel Regression Modeling
- Model:  
  `ln(HDI) = β₀ + β₁ * MEPI_PCA + β₂ * Sanitation + β₃ * Interaction_Terms + u_i + ϵ_it`
- Panel regression with **state fixed effects**
- Interaction terms added to capture temporal changes post-policy implementation

#### 3. Clustering Analysis
- Applied **K-means clustering** on MEPI and HDI data  
- Created visual maps of clusters to represent regional development disparities  
- Further regressions were run within each cluster

---

### 📊 Key Findings

- A **0.1 unit increase in MEPI** leads to a **7.8% decrease in HDI** (statistically significant)
- **Interaction analysis** reveals a reduced negative impact of energy poverty after 2015
- **Clustering** grouped states into:
  - **Cluster 0**: High MEPI, Low HDI (e.g., Bihar, Odisha)
  - **Cluster 1**: Low MEPI, High HDI (e.g., Kerala, Himachal)
  - **Cluster 2**: Moderate values (e.g., Maharashtra, Gujarat)
- **Sanitation** emerged as a statistically significant factor enhancing HDI

---

### 🗺️ Visual Analysis

- 📌 Heatmaps of MEPI (NFHS-3, 4, 5)
- 📌 Line graphs showing HDI vs MEPI trends over time
- 📌 State-level MEPI-HDI scatterplots
- 📌 Cluster maps highlighting regional disparities
- 📌 Growth rate comparisons of top/bottom 5 states

---

### 💡 Policy Recommendations

- 🌞 **Decentralized renewable energy systems** for high-MEPI regions
- 🍲 **Expand clean cooking fuel access** via LPG subsidies and PAYG models
- 🧾 **Financial inclusion programs** to empower rural households
- 📍 **Targeted district-level interventions** rather than national averages
- 📊 **Incorporate MEPI into SDG 7 monitoring** for real-time policy feedback

---

### ⚠️ Limitations & Scope for Future Research

- Limited by availability of district-level and post-2021 energy data  
- Potential **endogeneity** remains — future research could use IV/DiD models  
- Further exploration of **gender-disaggregated** and **energy source-specific** impacts encouraged

---

### 🛠 Tools & Technologies

- **Econometrics & Modeling:** STATA (PCA, Fixed Effects, K-Means)  
- **Data Processing:** Excel  
- **Visualization:** GIS-based mapping, heatmaps, line plots  
- **Documentation & Reporting:** LaTeX, PowerPoint

---

### 📂 Project Structure

Research-Project/
├── data/ # Raw and processed datasets
│ ├── NFHS/ # NFHS-3, 4, 5 datasets
│ ├── HDI/ # HDI time series
│ └── external/ # Additional socio-economic indicators
│
├── src/
│ ├── preprocessing/ # Cleaning and formatting scripts
│ ├── analysis/ # PCA, regression models, clustering
│ └── visualization/ # Heatmaps, trends, cluster maps
│
├── reports/
│ ├── final/ # Final report and presentation deck
│ └── supplementary/ # References, citation datasets
│
├── visualizations/ # Output charts and infographics
├── README.md # Project overview (this file)
├── LICENSE
└── requirements.txt # Dependencies and versions

---

### 📌 Highlight Quote

> *“To reach an HDI of 0.9, India’s required energy consumption is 45.7–75 GJ per capita per year, but in FY23, we stood at just 16.7 GJ.*”  
> — *Bhattacharyya et al. (2022), Energy Statistics India (2024)*

This project provides empirical evidence to **bridge the ambition-access gap** on India’s road to *Viksit Bharat*.

---

### 🤝 Author

**Pulkit Garg**  
MBA (Business Economics), Department of Business Economics  
University of Delhi  
📧 pulkitgarg@email.com  
🔗 [LinkedIn](https://www.linkedin.com/in/pulkit-garg03) | [GitHub](https://github.com/pulkitgarg3)

---

### 🔖 Tags

`#SDG7` `#EnergyPoverty` `#HDI` `#Econometrics` `#NFHS` `#PublicPolicy` `#PanelData` `#Stata` `#Analytics` `#IndiaDevelopment` `#OpenToWork`
