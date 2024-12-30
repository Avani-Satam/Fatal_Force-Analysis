# Data Science Project: Social and Economic Analysis

This repository contains a data science project focused on analyzing various social and economic factors in the United States. The analysis aims to uncover insights related to education, income, race, poverty, and fatal encounters with law enforcement. The project uses multiple datasets and applies data preprocessing, visualization, and statistical analysis techniques to achieve its goals.

## Project Description
The primary objective of this project is to analyze and identify correlations between various socio-economic factors and critical societal issues. For instance, it explores:

- The relationship between income levels and education attainment.
- Demographic distributions and their impact on poverty rates.
- Trends in police-related fatalities and their correlation with other variables.

## Datasets Used
The project utilizes the following datasets:

1. **Fatal_Force_(start).ipynb**:
   - A Google Colab Notebook that includes the core analysis and visualizations for the project.

2. **Share_of_Race_By_City.csv**:
   - Contains data on racial demographics across different U.S. cities.
   - Fields: City, Population, Racial Breakdown (e.g., % White, % Black, % Hispanic, etc.).

3. **Pct_People_Below_Poverty_Level.csv**:
   - Details the percentage of people living below the poverty level.
   - Fields: City/State, Poverty Percentage.

4. **Pct_Over_25_Completed_High_School.csv**:
   - Represents the percentage of adults over 25 years old who have completed high school.
   - Fields: City/State, % Completed High School.

5. **Median_Household_Income_2015.csv**:
   - Provides median household income data for the year 2015.
   - Fields: City/State, Median Income.

6. **Deaths_by_Police_US.csv**:
   - Tracks fatalities caused by police encounters.
   - Fields: Date, Location, Victim Demographics, Incident Details.

## Project Structure
```
.
|-- Fatal_Force_(start).ipynb   # Google Colab Notebook with the main analysis
|-- Share_of_Race_By_City.csv   # Dataset for racial demographics
|-- Pct_People_Below_Poverty_Level.csv  # Dataset for poverty levels
|-- Pct_Over_25_Completed_High_School.csv  # Dataset for education levels
|-- Median_Household_Income_2015.csv  # Dataset for income levels
|-- Deaths_by_Police_US.csv  # Dataset for police-related fatalities
```

## Methodology
1. **Data Cleaning**:
   - Missing values handled appropriately.
   - Data normalized for comparison across datasets.

2. **Exploratory Data Analysis (EDA):**
   - Visualizations created using libraries like Matplotlib and Seaborn.
   - Statistical summaries and correlation heatmaps to identify key relationships.

3. **Insights and Observations**:
   - Patterns and trends highlighted for socio-economic factors.
   - Observations documented in the Google Colab Notebook.

## Tools and Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Google Colab

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/social-economic-analysis.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Google Colab Notebook and run the analysis:
   ```bash
   Open Fatal_Force_(start).ipynb in Google Colab
   ```

## Results
- Detailed visualizations and statistical summaries can be found in the Google Colab Notebook.
- Key findings are documented in the markdown cells within the notebook.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Avani Satam
avanisatam@gmail.com


