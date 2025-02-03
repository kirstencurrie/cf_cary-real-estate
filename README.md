# cf_cary-real-estate
Analysis of Cary, NC real estate properties using data science techniques to uncover market trends, value drivers, and investment insights. 

- **[Link to Cary, NC Real Estate Tableau Storyboard](https://public.tableau.com/app/profile/kirsten.currie/viz/CaryNC_PropertyValueAnalysis/CaryProperties?publish=yes)**

# Cary, NC Real Estate Analysis Project

## Overview

This project analyzes real estate properties in Cary, North Carolina, providing insights for prospective investors and those interested in understanding the local property market. The analysis explores various factors contributing to property values in the Cary area, which is known for its higher home prices compared to other suburbs in the Raleigh/Chapel Hill/Durham "Research Triangle" region.

## Project Structure

The analysis is divided into six Jupyter notebooks, each focusing on different aspects of the data:

1. **Exploratory Analysis**
2. **Exploring Relationships**
3. **Geographical Analysis**
4. **Machine Learning: Regression**
5. **Machine Learning: Clustering**
6. **Time Series Analysis**

## Data Source

The analysis utilizes government data on Cary real estate properties. This dataset provides a comprehensive view of the local real estate landscape and historical property prices.

- **Cary Real Estate Data**: [link](https://data.townofcary.org/explore/dataset/property/table/?disjunctive.county&disjunctive.apaownershipdesc&disjunctive.apasitedesc&disjunctive.phycity&disjunctive.cary_city&disjunctive.landclass&sort=owner)
- **U.S. Zipe Code Shape Files**: [link](https://www.census.gov/programs-surveys/geography/technical-documentation/records-layout/2020-zcta-record-layout.html)

## Key Findings

- **Property Types**: The analysis revealed interesting outliers, such as the airport property valued at $738,378,563 and the William Umstead State Park with the highest land value of $734,963,000.
- **Historical Properties**: The oldest property identified was the Joel Lane House, built in 1760.
- **Land Classification**: Breaking down properties by land class provided more meaningful insights for residential vs. commercial properties.
- **Value Drivers**: Contrary to initial hypotheses, property acreage showed only a weak correlation (6%) with estimated property value.
- **Age and Value**: Cluster analysis consistently showed a trend of newer properties selling at higher prices.

## Methodology

### Exploratory Data Analysis
- Data cleaning and preprocessing
- Visualization of key features and relationships

### Statistical Analysis
- Correlation analysis
- Linear regression
- Clustering analysis

### Geographical Analysis
- Choropleth mapping of property data

### Time Series Analysis
- Decomposition of time series data
- Stationarity testing (Dickey-Fuller Test)

## Key Visualizations

- Correlation matrices and heat maps
- Scatterplots and pair plots
- Choropleth maps
- Clustering visualizations

## Limitations and Future Work

- A significant portion (one-third) of the dataset had missing "yearbuilt" values, potentially affecting age-related analyses.
- Some property values appeared unusual or potentially misrepresented (e.g., properties listed for $1).
- Future research could explore factors causing older properties to retain value, such as location or recent renovations.

## Tools and Technologies Used

- Python
- Jupyter Lab
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- Tableau Public (for visualization)

## How to Use This Repository

1. Clone the repository
2. Install required libraries: `pip install -r requirements.txt`
3. Open the Jupyter notebooks in order, starting with "6.1 Cary Exploratory Analysis.ipynb"

## Contributors

[Kirsten Currie]

