# GDP Analysis (2020-2025)
## 📊 Overview

Comprehensive analysis of GDP data across 196 countries from 2020 to 2025. This project demonstrates data cleaning,
trend analysis, growth rate calculations, and predictive modeling using Python and machine learning.

## 🎯 Project Objectives

- Analyze GDP trends for 196 countries over 6 years
- Identify fastest-growing economies and investment opportunities
- Calculate Compound Annual Growth Rate (CAGR) for each country
- Predict GDP values for 2026 using machine learning
- Create visualizations for economic insights

## 🔧 Technologies Used

- **Python 3.8+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical plotting
- **Scikit-learn** - Machine learning models
- **Jupyter Notebook** - Interactive development

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Jupyter Notebook

## 📈 Key Features

### 1. Data Processing
- **Data Cleaning**: Handling missing values and data type conversion
- **Data Validation**: Ensuring data quality and consistency
- **Statistical Summary**: Comprehensive dataset overview

### 2. Trend Analysis
- Individual country GDP trends visualization
- Year-over-year growth analysis
- Peak GDP year identification for each country

### 3. Comparative Analysis
- Top N countries by GDP performance
- Global average GDP calculation and trending
- Cross-country performance benchmarking

### 4. Growth Rate Analysis
- CAGR calculation for all 196 countries
- Identification of fastest-growing economies
- Countries outperforming global average

### 5. Predictive Modeling
- Linear regression for GDP forecasting
- 2026 GDP predictions with confidence intervals
- Model validation and performance metrics

## 📊 Key Insights

### Top 5 Fastest Growing Countries (CAGR 2020-2025)
1. **Guyana** - 29.52%
2. **Venezuela** - 16.75%
3. **Kyrgyzstan** - 15.68%
4. **Haiti** - 14.99%
5. **Georgia** - 14.11%

### Major Economies by Absolute Growth
- **United States**: $9.15 trillion growth
- **India**: $1.51 trillion growth
- **Germany**: $807.8 billion growth
- **Turkey**: $720.3 billion growth
- **Brazil**: $649.9 billion growth

### Global Statistics
- **196 countries** analyzed
- **29 countries** exceed global average growth
- **$139.85B** average global GDP increase (2020-2025)
- **Strong recovery** patterns post-2020

## 🔍 Usage Examples

### Analyze Specific Country
```python
# Interactive country selection
country_name = input("Enter country name: ")
analyze_country_trend(country_name)
```

### Find Top Performers
```python
# Get top N countries by GDP
top_n = int(input("Number of top countries: "))
display_top_countries(top_n, year='2025')
```

### Calculate Growth Rates
```python
# CAGR analysis
cagr_results = calculate_cagr(df)
display_growth_leaders(cagr_results, top=10)
```

### GDP Prediction
```python
# Predict 2026 GDP
predictions = predict_gdp_2026(df, country='India')
visualize_prediction(predictions)
```

## 📋 Requirements

```txt
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.5.0
seaborn>=0.11.0
scikit-learn>=1.0.0
jupyter>=1.0.0
```

## 🎨 Visualizations

The project generates various professional charts:
- Line plots for GDP trends
- Bar charts for country comparisons
- Distribution plots for CAGR analysis
- Prediction plots with confidence intervals
- Global average trend visualization




⭐ **Star this repository if you found it helpful!**

🔗 **Clone and explore the data yourself!**
