# Exploratory Data Analysis & Feature Engineering Across Automotive and Retail Datasets

> Performed end-to-end exploratory data analysis and feature engineering on automotive and retail datasets to uncover pricing drivers, consumer trends, and data quality insights.

**Author:** Amisha Farhana Shaik  
**Project Type:** Exploratory Data Analysis | Feature Engineering | Data Cleaning | Business Insight Development  

---

## Business Context

This project demonstrates applied exploratory data analysis (EDA) and structured data preparation across two real-world datasets:

1. Used car pricing dataset (Toyota Corolla resale market)
2. U.S. wine retail dataset (41,731 wine records)

The objective was to extract actionable business insights, prepare features for modeling, and understand key drivers influencing pricing and demand.

---

# Part 1: Used Car Pricing Analysis

## Dataset Overview

Analyzed 1,436 used Toyota Corolla listings with features including:

- Price
- Age (months)
- Manufacturing year
- Kilometers driven
- Horsepower (HP)
- Fuel type
- Engine capacity
- Automatic transmission
- Metallic paint

---

## Key Insights

### Price Distribution
- Average price: ~$10,730  
- Median price: $9,900  
- Right-skewed distribution (few high-priced outliers)
- Majority of cars priced below the mean

**Insight:** Market dominated by affordable mid-range vehicles.

---

### Age & Depreciation
- Average age: ~56 months
- Majority of cars older than 40 months
- Older inventory dominates resale market

**Business Implication:** Price heavily influenced by depreciation curve.

---

### Fuel Type Impact

- Diesel vehicles command higher median prices
- Petrol vehicles decline faster with mileage
- CNG vehicles show stable mid-range pricing

Diesel cars especially retain higher value at lower mileage levels.

---

### Kilometers & Features Interaction

- Clear negative relationship between KM driven and price
- Cars with air conditioning consistently priced higher
- Feature premiums most visible in lower-mileage vehicles

**Insight:** Mileage normalization is essential before predictive modeling.

---

## Data Preparation

- Normalized kilometer variable
- Created dummy variables for fuel type
- Partitioned dataset for modeling readiness

This prepared the dataset for downstream regression or predictive pricing models.

---

# Part 2: Wine Retail Dataset Analysis

## Dataset Overview

- 41,731 rows
- 65 columns
- Attributes include:
  - Points (ratings)
  - Price
  - Badges (Best Buy, Editor’s Choice, etc.)
  - Vintage year
  - Alcohol content
  - Flavor descriptors
  - Vineyard location

---

## Data Quality Assessment

- Badge column contained 35,000+ missing values
- Minor missing values in price and vintage year
- No duplicate entries detected

**Insight:** Missing badge data requires careful handling before modeling.

---

## Consumer & Trend Insights

### Badge & Quality Filtering

Used sorting and filtering logic to:

- Identify high-quality wines under $20
- Compare organic vs non-organic offerings
- Evaluate point-to-price relationships

---

### Market Trends Identified

- Strong growth in natural and organic wines
- Rosé experienced rapid growth (118% increase over 5 years)
- Increased demand for domestic wine alternatives post-COVID
- Growing millennial influence in wine purchasing

---

## Business Implications

- Affordable, highly rated wines drive consumer interest
- Organic/natural labeling increasingly impacts purchase decisions
- Domestic wine production presents inventory diversification opportunity
- Data-driven sorting improves product positioning strategy

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Distribution & Skewness Interpretation
- Feature Engineering (Normalization, Dummies)
- Outlier Detection
- Data Cleaning & Missing Value Assessment
- Business Insight Extraction
- Market Trend Interpretation

---

## Core Takeaways

- Price distributions often skewed — medians matter more than means.
- Feature engineering significantly improves model readiness.
- Retail datasets require structured filtering for meaningful insights.
- Data cleaning is foundational before predictive modeling.

---

This project demonstrates applications in:

Pricing Analytics | Retail Data Analysis | Feature Engineering | Consumer Trend Analysis | Data Preparation for Machine Learning
