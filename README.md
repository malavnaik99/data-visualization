# Explore Trends in Emissions, Pollution, and Health Metrics Across U.S. States

## Overview
This project analyzes the relationships between environmental pollution, emissions, and cardiovascular health across U.S. states. Using data analytics and visualization techniques, we uncover insights into:
- The contribution of different sectors and fuels to emissions.
- Seasonal and long-term trends in air pollution.
- The impact of pollution and emissions on cardiovascular health metrics.

By integrating data from three comprehensive datasets, the project provides actionable insights to guide public health strategies and environmental policies.

## Key Highlights
- **Datasets Analyzed**:
  1. **Pollution Data**: Trends in air quality across U.S. states (2000–2022).
  2. **Heart Care and Hospital Data**: Patient demographics, health metrics, and treatment trends.
  3. **Emission Data**: State-wise emissions by sector and fuel type.
  
- **Technologies Used**:
  - **Databases**: PostgreSQL for structured data; MongoDB for semi-structured JSON data.
  - **Data Processing**: Python with Pandas, NumPy, Seaborn, and Matplotlib.
  - **Visualization**: Plotly and Dash for interactive dashboards.
  - **ETL Process**: Data extracted from multiple sources, cleaned, transformed, and stored in databases for analysis.

## Key Findings
1. **Pollution Trends**:
   - Ozone (O₃) peaks during summer; CO and SO₂ concentrations rise in winter.
   - States like California and Texas show consistently high pollution levels.

2. **Health Metrics**:
   - Positive correlations found between cardiovascular diseases and pollution levels.
   - Blood pressure and BMI are key health metrics impacted by pollution.

3. **Emissions**:
   - Texas and California are the highest contributors to emissions.
   - Natural gas and petroleum are the major pollutants across states.

## Methodology
1. **Data Storage and Loading**:
   - Pollution and emission datasets stored in PostgreSQL.
   - Heartcare data stored in MongoDB.
   
2. **Data Cleaning**:
   - Handled missing values and duplicates.
   - Standardized pollutant measurements for uniformity.
   
3. **Visualization**:
   - Interactive dashboards highlight key trends in pollution, emissions, and health metrics.
   - Seasonal and state-wise trends presented via line graphs, heatmaps, and bar charts.

4. **ETL Process**:
   - Extracted data from MongoDB and PostgreSQL.
   - Transformed for analysis using Python libraries.
   - Loaded transformed data back into databases.

## Dashboard
The interactive dashboard integrates insights from all datasets, providing:
- State-wise emissions and pollution trends.
- Health metrics and treatment availability across states.
- Visualizations of fuel consumption by sector and year.

## Results
- Environmental factors like emissions and pollution directly correlate with higher rates of cardiovascular diseases.
- States with high emissions often exhibit lower health scores and less access to healthcare.

## Future Work
- Expand the analysis to include data from other countries.
- Employ advanced machine learning techniques to model and predict environmental and health outcomes.
- Address class imbalances in datasets for improved predictive analysis.

## How to Run
1. Clone the repository:
   ```bash
   git clone [repository_url]
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the dashboard:
   ```bash
   python app.py
   ```

## Contributors
- **Malav Naik**  
- **Pratik Sunar**  
- **Shivansh Bhatnagar**  
MSc in Data Analytics, National College of Ireland

## License
This project is licensed under the MIT License.

