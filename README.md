# SFPD Crime Dashboard Analysis

## Overview
This project aims to analyze crime data from the San Francisco Police Department (SFPD) spanning from 2018 to 2022. The analysis includes data preprocessing, exploratory data analysis, and visualization using Tableau to develop an interactive dashboard.

## Project Structure
- **data/**: Contains the dataset and its description.
- **notebooks/**: Jupyter notebooks for data preprocessing, analysis, and dashboard creation.
- **dashboard/**: Tableau workbook file for the dashboard.
- **scripts/**: Python scripts for data preprocessing and analysis.
- **images/**: Contains screenshots of the dashboard.

## Data Description
The dataset includes reported incidents by SFPD from 2018 to 2022. It categorizes crimes into various types, including robberies, assaults, and automobile accidents, with detailed information on locations, dates, times, and case statuses.

## Research Questions
1. Is there a seasonal pattern in the crimes reported in the city?
2. What are the ten most reported incident categories?
3. What are the most common resolutions for reported incidents?
4. When do most vehicle thefts occur?

## Methodology
- **Data Preprocessing**: Handling missing values, data transformation, and feature engineering.
- **Data Analysis**: Exploring trends, seasonal patterns, and incident categories using statistical techniques.
- **Visualization**: Creating an interactive dashboard in Tableau to present key insights.

## Techniques Used
- **Data Preprocessing**
  - Data Cleaning
  - Feature Engineering
  - Handling Missing Values
- **Data Analysis**
  - Exploratory Data Analysis (EDA)
  - Trend Analysis
  - Seasonal Analysis
- **Visualization**
  - Interactive Dashboards using Tableau

## Key Findings
- The trend of reported crimes showed a decline from 2018 to 2020, with an increase in 2021.
- October consistently has the highest number of incidents, while February has the lowest.
- Larceny Theft is the most reported incident category, followed by Malicious Mischief.
- The majority of cases are reported in the Central and Northern police districts.
- Vehicle thefts mostly occur during the daytime.

## Dashboard Overview
The Tableau dashboard provides an interactive interface to explore crime data by year, month, neighborhood, and police district. Key features include:
- **KPI**: Tracks the number of incidents over time.
- **Bar Charts**: Shows top incident categories and report filing types.
- **Map**: Visualizes incident intensity by geographic location.
- **Status of Cases**: Displays the current status of cases in each police district.

## Conclusion
The analysis offers valuable insights into crime patterns and trends in San Francisco, helping to inform law enforcement and policy decisions. 

## Getting Started
1. **Clone the Repository**
    ```sh
    git clone https://github.com/yourusername/SFPD_Crime_Dashboard_Analysis.git
    ```
2. **Install Dependencies**
    ```sh
    pip install -r requirements.txt
    ```
3. **Run the Notebooks**
    - Open and run the Jupyter notebooks in the `notebooks/` directory for data preprocessing and analysis.
4. **Open Tableau Dashboard**
    - Open the `SFPD_Crime_Dashboard.twb` file in Tableau to interact with the dashboard.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Data provided by [San Francisco Police Department](https://datasf.gitbook.io/datasf-dataset-explainers/sfpd-incident-report-2018-to-present).
- Project developed as part of the Communication and Visualization for Data Analytics course at the College of Professional Studies.
