# Bengaluru House Price - EDA

>> Exploratory data analysis of 13,000+ Bengaluru property listings to uncover pricing trends across localities, property types, and amenities.

---

## Problem Statement

Bengaluru's real estate market is highly fragmented, with prices varying sharply by locality, property configuration, and listing quality.

Raw housing data is often messy and inconsistent, making it hard for buyers, analysts, or platforms to draw reliable conclusions. This project focuses on cleaning that data and surfacing clear, quantified pricing patterns.

---

## Approach Overview

The project moves from raw, inconsistent listing data to clear, quantified insights.

```text
Raw Listing Data
        │
        ▼
Stage 1: Data Cleaning
Fix inconsistent sqft formats, handle missing values, remove outliers

        │
        ▼
Stage 2: Univariate & Locality Analysis
Price distribution, price-per-sqft by locality

        │
        ▼
Stage 3: Bivariate & Multivariate Analysis
Price vs sqft, BHK, bathrooms, correlation heatmap

        │
        ▼
Stage 4: Feature Engineering
Derived price-per-sqft, parsed BHK from text fields

        │
        ▼
Key Insights & Visual Summary
```

---

## Dataset Summary

| Attribute          | Detail                                            |
| ------------------- | -------------------------------------------------- |
| Records              | ~13,000 listings                                    |
| Localities covered   | 240+                                                |
| Key features         | location, size, total sqft, bath, balcony, price    |
| Missing data         | society, balcony, bath columns                      |

---

## Key Insights

*
* 
* 
* 
* 

---
## Visual Analysis



Key visuals include price distribution (with log transform), top/bottom localities by price per sqft, and a correlation heatmap of numeric features.

---
## Project Structure

```text
eda-bengaluru-house-prices/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── eda_bengaluru_house_prices.ipynb
│
├── images/
│   ├── price_distribution.png
│   ├── locality_price_comparison.png
│   └── correlation_heatmap.png
│
├── requirements.txt
└── README.md
```

---

## Technology Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Installation

```bash
git clone https://github.com/<your-username>/eda-bengaluru-house-prices.git

cd eda-bengaluru-house-prices

pip install -r requirements.txt

jupyter notebook notebooks/eda_bengaluru_house_prices.ipynb
```

---

## Dataset

Dataset used:

Bengaluru House Price Data

https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data

The dataset contains ~13,000 property listings covering location, size, area type, availability, and price for homes across Bengaluru.

---

## Practical Value

This project demonstrates how exploratory analysis alone can surface actionable pricing intelligence.

### Buyer Guidance

Locality-level price benchmarks help buyers judge whether a listing is fairly priced.

### Market Transparency

Highlighting price-per-sqft variation exposes inconsistencies in how properties are priced across the city.

### Data Quality Awareness

The cleaning process illustrates common data-quality issues in real-world listing data and how to resolve them.

### Foundation for Modeling

The cleaned dataset and engineered features (e.g. price-per-sqft) form a ready base for a future price-prediction model.
