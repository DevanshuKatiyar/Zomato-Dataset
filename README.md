# Restaurant Data Analysis README

## Overview:

Welcome to the Restaurant Data Analysis project! In this project, I've conducted an analysis of restaurant data focusing on various attributes such as cuisine types, price range, and ratings. Below is a sample dataset and the summary of the analysis conducted:

## Dataset Sample:

| Restaurant ID | Restaurant Name                    | Country Code | City           | Address                                                      | Locality              | Locality Verbose                               | Longitude | Latitude | Cuisines                                | Average Cost for two | Currency        | Has Table booking | Has Online delivery | Is delivering now | Switch to order menu | Price range | Aggregate rating | Rating color | Rating text | Votes |
|---------------|------------------------------------|--------------|----------------|--------------------------------------------------------------|-----------------------|------------------------------------------------|-----------|----------|-----------------------------------------|---------------------|-----------------|-------------------|-------------------|------------------|----------------------|-------------|------------------|--------------|--------------|-------|
| 6317637       | Le Petit Souffle                  | 162          | Makati City    | Third Floor, Century City Mall, Kalayaan Avenue, Poblacion | Century City Mall     | Century City Mall, Poblacion, Makati City     | 121.0275  | 14.5654  | French, Japanese, Desserts             | 1100                | Botswana Pula(P) | Yes               | No                | No               | No                   | 3           | 4.8              | Dark Green   | Excellent    | 314   |
| 6304287       | Izakaya Kikufuji                  | 162          | Makati City    | Little Tokyo, 2277 Chino Roces Avenue, Legaspi Village      | Little Tokyo          | Little Tokyo, Legaspi Village, Makati City  | 121.0141  | 14.5537  | Japanese                               | 1200                | Botswana Pula(P) | Yes               | No                | No               | No                   | 3           | 4.5              | Dark Green   | Excellent    | 591   |
| 6300002       | Heat - Edsa Shangri-La            | 162          | Mandaluyong City | Edsa Shangri-La, 1 Garden Way, Ortigas                     | Edsa Shangri-La       | Edsa Shangri-La, Ortigas, Mandaluyong City  | 121.0568  | 14.5814  | Seafood, Asian, Filipino, Indian     | 4000                | Botswana Pula(P) | Yes               | No                | No               | No                   | 4           | 4.4              | Green        | Very Good    | 270   |
| ...           | ...                                | ...          | ...            | ...                                                          | ...                   | ...                                            | ...       | ...      | ...                                     | ...                 | ...             | ...               | ...               | ...              | ...                  | ...         | ...              | ...          | ...          | ...   |

## Work Done:

### Data Mining:
- Extracted information on the number of cuisines offered by each restaurant.
- Created new columns in the dataframe representing each cuisine type and converted them into binary variables for analysis.

### Exploratory Data Analysis (EDA):
- Conducted EDA to gain insights into the dataset.
- Analyzed distributions and relationships between different variables.
- Created boxplots to visualize the relationship between price range and rating color.
- Explored correlations between various features to understand their impact on restaurant ratings.

### Linear Regression:
- Employed linear regression to analyze the relationship between different variables and predict restaurant ratings.
- Utilized the insights gained from EDA to inform the feature selection process for the regression model.

## Repository Structure:
- **data**: Contains the raw dataset and any processed data files.
- **notebooks**: Jupyter notebooks used for data preprocessing, EDA, modeling, and analysis.
- **results**: Results and outputs generated from the analysis, including visualizations and reports.

## Getting Started:
1. Clone this repository to your local machine.
2. Ensure you have Python 3.x installed along with necessary libraries (e.g., pandas, numpy, matplotlib, seaborn, scikit-learn).
3. Navigate to the `notebooks` directory and open the Jupyter notebooks to explore the analysis and results.
4. Follow along with the steps outlined in the notebooks to reproduce the analysis or modify it as needed.

## Contributing:
- Contributions to this project are welcome! Feel free to fork this repository, make changes, and submit pull requests.
- For major changes, please open an issue first to discuss proposed updates or improvements.



Thank you for your interest in my personal project! I hope you find the insights generated from the analysis valuable.
