# Research-Project

# Assesing the Impact of Energy Poverty on Human Development Index (HDI) and Aligning with SDG7: A State-Wise Analysis
---
## Project Description
This research project investigates the multidimensional nature of energy poverty and its impact on human development in India. By leveraging data from the National Family Health Surveys (NFHS-3, NFHS-4, NFHS-5) and other socio-economic indicators, the study constructs a **Multidimensional Energy Poverty Index (MEPI)**, evaluates its relationship with the **Human Development Index (HDI)**, and explores its alignment with **SDG7 (Affordable and Clean Energy for All)**. The project employs exploratory data analysis, pooled regression modeling, and geographical visualizations to identify regional disparities and provide actionable policy recommendations.
---
## Objective
The primary objectives of this research are:

1. **To construct and analyze the Multidimensional Energy Poverty Index (MEPI) for Indian states**:  
   - MEPI is developed using access to electricity and clean cooking fuel, with weights derived from their correlation with energy poverty.  
   - This index enables state-wise and temporal comparisons of energy poverty across NFHS-3, NFHS-4, and NFHS-5.  

2. **To assess the relationship between energy poverty and human development**:  
   - The study evaluates the impact of energy poverty, as measured by MEPI, on HDI using a pooled regression model.  
   - It incorporates other socio-economic indicators, such as the wealth index, female literacy rate, and infant mortality rate, to provide a comprehensive analysis.  

3. **To explore the alignment of energy poverty trends with SDG 7 goals**:  
   - By comparing changes in energy poverty and access to modern energy sources with SDG 7 benchmarks, the study examines the role of policy interventions in promoting affordable and clean energy.  

4. **To identify regional disparities and propose targeted policy recommendations**:  
   - The study highlights state-level variations in energy poverty and human development, identifying lagging regions and suggesting interventions to address these disparities.  

5. **To conduct exploratory data analysis (EDA) for key variables**:  
   - The study visualizes trends in MEPI, HDI, and other socio-economic variables, providing descriptive insights that support the analytical findings.

---
## Data Sources
The project utilizes the following datasets:

1. **National Family Health Surveys (NFHS):**  
   - NFHS-3 (2005-06), NFHS-4 (2015-16), and NFHS-5 (2019-21).  
   - Indicators: Access to electricity, clean cooking fuel, sanitation, drinking water, and wealth index.  
2. **Human Development Index (HDI):**  
   - State-wise HDI values sourced from UNDP reports (1990-2022).  
3. **Socio-Economic Indicators:**  
   - Female literacy rates and infant mortality rates from NFHS and Census reports.  
   - State GDP per capita (SGDP) from Reserve Bank of India (RBI) and MOSPI.

---
## Methodology

1. **Data Preprocessing and Cleaning**:  
   - Consolidated data from NFHS-3, NFHS-4, and NFHS-5 into a pooled dataset for 29 states.  
   - Standardized and normalized variables for regression modeling.  

2. **Construction of MEPI**:  
   - MEPI was constructed using two indicators:  
     - Access to Electricity (weight: 0.4).  
     - Access to Clean Cooking Fuel (weight: 0.6).  
   - Weightage determined based on correlation analysis with MEPI.  

3. **Exploratory Data Analysis (EDA)**:  
   - Conducted visualizations to examine trends in HDI, MEPI, and socio-economic variables.  
   - Visual tools: Line charts, bar charts, and heatmaps showcasing state-wise and temporal patterns.  

4. **Regression Analysis**:  
   - Pooled regression model to analyze the impact of MEPI and other independent variables (wealth index, female literacy, IMR, etc.) on HDI.  
   - Included dummy variables for NFHS rounds to capture time-specific effects.  

5. **Geographical Representation**:  
   - Created heatmaps and state-level visualizations of MEPI and HDI across NFHS rounds.  
   - Highlighted regional disparities and temporal progress in energy poverty reduction.

---
## Current Progress

1. **Data Collection and Preparation**:  
   - Completed data compilation and preprocessing from NFHS, UNDP, and other sources.  
2. **MEPI Construction**:  
   - Developed MEPI values for three NFHS rounds and conducted state-wise comparisons.  
3. **Exploratory Analysis**:  
   - Visualized trends in MEPI, HDI, and socio-economic indicators.  
   - Identified patterns and outliers through heatmaps and correlation analysis.  
4. **Regression Setup**:  
   - Defined regression model with dependent and independent variables.  
   - Included dummy variables for time effects.  
5. **Preliminary Insights**:  
   - Observed a significant reduction in energy poverty over time but with persistent regional disparities.  
   - Identified strong correlations between HDI and socio-economic indicators such as wealth index and female literacy.

---
## Future Work

1. **Regression Analysis**:  
   - Run the pooled regression model and validate results using statistical tests.  
   - Examine the role of MEPI and other independent variables in influencing HDI.  

2. **Policy Recommendations**:  
   - Use findings to propose region-specific strategies for energy poverty alleviation.  
   - Link outcomes to SDG7 to assess progress toward sustainable development goals.  

3. **Report Compilation**:  
   - Finalize the research report with detailed methodology, findings, and conclusions.  
   - Include insights from EDA and regression analysis.

---
## Project Structure

├── data/               # Contains raw and processed datasets.  
│   ├── NFHS/           # NFHS-3, NFHS-4, and NFHS-5 datasets and preprocessing scripts.  
│   ├── HDI/            # State-wise HDI data from 1990 to 2022.  
│   └── external/       # Additional datasets (e.g., socio-economic indicators).  
│  
├── src/                # Source code for data processing, analysis, and visualization.  
│   ├── preprocessing/  # Scripts for cleaning and normalizing data.  
│   ├── analysis/       # Exploratory data analysis (EDA) and regression modeling scripts.  
│   └── visualization/  # Scripts for generating heatmaps, line charts, and bar graphs.  
│  
├── visualizations/     # Output graphs and maps generated from analysis.  
│   ├── MEPI/           # Heatmaps, state-wise trends, and line charts for MEPI.  
│   ├── HDI/            # Visualizations for HDI trends and state comparisons.  
│   └── others/         # Graphs for independent variables (e.g., sanitation, literacy).  
│  
├── reports/            # Research documents and progress updates.  
│   ├── interim/        # Interim reports and drafts.  
│   ├── final/          # Final research report.  
│   └── supplementary/  # Supplementary materials like references and notes.  
│  
├── README.md           # Project overview and details (this file).  
├── LICENSE             # License for the project.  
└── requirements.txt    # Dependencies and libraries for reproducing the project.

