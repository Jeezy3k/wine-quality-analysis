# Wine Quality Analysis

Exploring the Wine Quality Dataset to analyze chemical properties and quality ratings of red and white wines.

## Overview

This project analyzes the Wine Quality Dataset to understand the relationships between physicochemical properties and expert quality ratings. The analysis includes data visualization, statistical summaries, and confidence interval estimation using both traditional and bootstrap methods.

## Key Findings

- **Quality Distribution**: Wine ratings follow a bell curve distribution, with most wines rated 5-6 on a 10-point scale
- **Alcohol Content**: Red and white wines have similar mean alcohol content (~10.4% ABV)
- **Statistical Validation**: Traditional and bootstrap confidence intervals produce consistent results

## Skills Demonstrated

- Data processing with CSV files and list structures
- Data visualization with matplotlib (bar charts, line graphs, histograms)
- Statistical analysis (mean, mode, standard deviation)
- Confidence interval estimation (traditional and bootstrap methods)

## Dataset

**Source**: [Wine Quality Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality)

**Citation**: Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). Wine Quality [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C56S3T

**Features**:
- Fixed acidity, volatile acidity, citric acid
- Residual sugar, chlorides
- Free/total sulfur dioxide
- Density, pH, sulphates
- Alcohol content
- Quality rating (0-10 scale)
- Wine type (red/white)

## Usage

```bash
jupyter notebook wine_quality_analysis.ipynb
```

## Technologies

- Python 3
- matplotlib
- statistics (standard library)
- csv (standard library)
