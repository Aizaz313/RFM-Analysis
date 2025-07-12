# RFM Analysis Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellowgreen)

Customer segmentation using RFM (Recency, Frequency, Monetary) analysis to identify high-value customers and optimize marketing strategies.

## Overview

This project demonstrates a complete RFM analysis workflow:
1. **Data Preparation**: Merges transaction and customer demographic data
2. **RFM Calculation**: Computes Recency, Frequency, and Monetary scores
3. **Customer Segmentation**: Classifies customers into loyalty tiers
4. **Visualization**: Generates insightful data visualizations

Key insights include:
- Customer lifetime value prediction
- Loyalty tier classification (Platinum, Gold, Silver, Bronze)
- Demographic analysis of high-value customers

## Technical Implementation

### Features
- **Data Merging**: Combines transaction and customer data
- **RFM Scoring**: Calculates scores using quartile segmentation
- **Customer Tiers**: Creates 11 detailed customer segments
- **Age Analysis**: Visualizes customer age distributions
- **Export Capability**: Saves results to CSV for further analysis

### Dependencies
```bash
pandas
numpy
matplotlib
seaborn
jupyter
python-dateutil
