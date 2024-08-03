
# Amazon Data EDA

## Overview

This project involves an exploratory data analysis (EDA) of Amazon product data. The goal is to uncover insights and patterns within the dataset, focusing on factors such as price, rating, and review counts. The analysis includes visualizations and statistical summaries to help understand the relationships and distributions of the data.

## Table of Contents

1. [Dataset](#dataset)
2. [Installation](#installation)
3. [Project Structure](#project-structure)
4. [Files Description](#files-description)
5. [Analysis](#analysis)
6. [Visualizations](#visualizations)
7. [Results](#results)
8. [Conclusion](#conclusion)
9. [Future Work](#future-work)
10. [Contributing](#contributing)
11. [Contact](#contact)

## Dataset

The dataset used in this analysis consists of Amazon product information, including attributes such as price, rating, and review counts.

## Installation

To replicate this analysis, you need to have Python installed. The necessary packages can be installed using the `requirements.txt` file.

```bash
git clone https://github.com/Ahadmoen/Amazon_DATA_EDA.git
cd Amazon_DATA_EDA
pip install -r requirements.txt
```

## Project Structure

```plaintext
Amazon_DATA_EDA/
├── data/
│   └── amazon_data.csv          # The dataset used for analysis
├── notebooks/
│   ├── EDA.ipynb                # Jupyter notebook with the EDA
│   └── Amazon_data_EDA (2).ipynb# Additional Jupyter notebook with detailed EDA
├── scripts/
│   └── eda.py                   # Python script for EDA
├── visualizations/
│   └── plots/                   # Directory to store generated plots
├── tableau/
│   └── Amazon_Dashboard_byRating.twb # Tableau workbook with data visualization
├── excel/
│   └── cleaned_amazon_data.xlsx # Cleaned dataset used for EDA
├── requirements.txt             # Required Python packages
└── README.md                    # Project README
```

## Files Description

### Data Directory

- **data/amazon_data.csv**: This file contains the raw dataset used for the EDA. It includes various attributes of Amazon products such as price, rating, and review count.

### Jupitor Notebooks Directory

- **notebooks/Amazon_data.jupyter.ipynb**: This Jupyter notebook contains the complete exploratory data analysis process. It includes data cleaning, descriptive statistics, visualizations, and insights derived from the data.

### Tableau Directory

- **tableau/Amazon_Dashboard_byRating.tableau.twb**: This Tableau workbook contains interactive visualizations of the Amazon product data. The dashboard focuses on analyzing product ratings and their distribution.

### Excel Directory

- **excel/cleaned_data and analysis.xlsx**: This Excel file contains the cleaned version of the Amazon product dataset. and performs basic calculations and descriptve and correlation works on it

### Requirements File

- **requirements.txt**: This file lists all the Python packages required to run the analysis. It includes libraries such as pandas, matplotlib, seaborn, and others.

### README File

- **README.md**: This file provides an overview of the project, including the dataset, installation instructions, project structure, and descriptions of each file.

## Analysis

The analysis includes the following steps:

1. **Data Cleaning**: Handling missing values, correcting data types, and removing outliers.
2. **Descriptive Statistics**: Calculating mean, median, mode, and standard deviation for numerical features.
3. **Data Visualization**: Creating visual representations of the data to identify patterns and trends.
4. **Correlation Analysis**: Examining relationships between different attributes.

## Visualizations

The visualizations created in this project include:

- **Histograms**: Distribution of prices, ratings, and review counts.
- **Box Plots**: Identifying outliers and understanding the spread of the data.
- **Scatter Plots**: Examining relationships between price and rating, rating and review count, etc.
- **Heatmaps**: Correlation matrix to see how different features are related.

## Results

Key findings from the analysis:

- **Price Distribution**: Most products are priced within a specific range.
- **Rating Trends**: Higher-rated products tend to have a higher number of reviews.
- **Correlation Insights**: Certain product attributes show significant correlations, providing insights into customer preferences.

## Conclusion

The EDA of Amazon product data revealed significant insights into pricing, rating trends, and customer preferences. This analysis can help in understanding consumer behavior and improving product offerings.

## Future Work

- Deep dive into specific categories of products.
- Time series analysis of review trends.
- Sentiment analysis of customer reviews.

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss the changes you want to make.

## Contact

For any questions or inquiries, please contact Ahad Moen at linkedin: www.linkedin.com/in/ahad-moen and Email: moenahad@gmail.com.

---
