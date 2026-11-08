# # GLP-1 Prescription Patterns & Socioeconomic Analysis

### Overview
This project investigates the relationship between socioeconomic indicators and GLP-1 prescription patterns across the United States using Python and publicly available healthcare and demographic data.

Developed as part of STOR 320 at the University of North Carolina at Chapel Hill, the project uses exploratory data analysis (EDA) to identify patterns and evaluate potential associations between prescription activity and socioeconomic conditions.

### Research Objective
To examine whether socioeconomic factors, including median household income, poverty rates, and unemployment rates, are associated with variations in GLP-1 prescription volume across U.S. states.

### Data Sources
- **Centers for Medicare & Medicaid Services (CMS):** 2024 Medicare Part D prescription data.
- **U.S. Census Bureau:** Socioeconomic indicators, including median household income, poverty rates, and unemployment rates.

### Technologies & Tools
- Python
- pandas and NumPy
- Matplotlib and Seaborn
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Regression Visualization
- Google Colab / Jupyter Notebook

### Methodology
1. Cleaned and prepared Medicare prescription and Census socioeconomic datasets.
2. Merged relevant indicators into a consolidated dataset for analysis.
3. Explored distributions and relationships between prescription activity and socioeconomic variables.
4. Generated correlation matrices, scatterplots, and regression visualizations.
5. Interpreted statistical relationships and identified notable patterns.

### Key Findings
- Unemployment showed the strongest observed correlation with GLP-1 prescription volume among the three socioeconomic indicators examined (Pearson r = 0.33).
- The analysis highlights measurable associations between socioeconomic conditions and prescription activity.
- Findings are exploratory and do not establish causal relationships.

### Limitations
- Correlation does not imply causation.
- Medicare Part D data do not capture all GLP-1 prescriptions in the United States.
- Differences in population size, Medicare enrollment, and prescribing patterns may influence observed relationships.

### Project Context
This analysis was completed as part of a collaborative STOR 320 course project at UNC-Chapel Hill.

### Future Improvements
- Normalize prescription counts by population or Medicare enrollment.
- Explore additional demographic and healthcare-access indicators.
- Apply multivariable regression to account for potential confounding factors.
