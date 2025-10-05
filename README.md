# SCT_DS_04
# 🚗 US Traffic Accidents Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-green)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-red)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11%2B-yellow)](https://seaborn.pydata.org/)

## 📋 Task Description

Analyze **traffic accident data** to identify patterns related to road conditions, weather, and time of day. Visualize accident hotspots and contributing factors.

## 🔍 How was it done?

The **US Accidents dataset** from Kaggle containing millions of accident records across 49 states was used. Due to the massive dataset size (29.86 GB), a **random sample of 200,000 records** was analyzed for efficiency. The analysis followed these steps:

1. **Data Loading & Sampling** - Loaded 200,000 random accident records for efficient processing
2. **Time Feature Extraction** - Extracted hour, day, month, and day of week from timestamps
3. **Pattern Analysis** - Identified trends across different time periods and conditions
4. **Geographic Analysis** - Determined accident hotspots by city and state
5. **Weather Impact Assessment** - Analyzed weather conditions, temperature, and visibility during accidents
6. **Road Features Analysis** - Examined the presence of traffic signals, junctions, crossings, etc.
7. **Visualization** - Created 13 comprehensive visualizations showing patterns and contributing factors

Python libraries including pandas, matplotlib, seaborn, and numpy were used for data processing, analysis, and visualization.

## 📊 Dataset Source

**Kaggle - US Accidents Dataset (2016-2023)**
- **URL:** https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents
- **Original Size:** ~7.7 million records (29.86 GB)
- **Sample Used:** 200,000 records
- **Time Period:** February 2016 - March 2023
- **Coverage:** 49 US states
- **Attributes:** 47 features including location, time, weather conditions, road features, and severity

## 💡 Key Findings

- **Peak Accident Hours:** 7-9 AM and 4-6 PM (rush hours)
- **Most Dangerous Day:** Friday shows highest accident frequency
- **Seasonal Pattern:** Winter months (Dec-Feb) have more accidents
- **Top Accident States:** California, Texas, and Florida lead in accident counts
- **Weather Impact:** Most accidents occur in fair/clear weather (due to higher traffic volume)
- **Visibility:** Lower visibility significantly increases accident severity
- **Road Features:** Traffic signals and junctions are common accident locations
- **Time of Day:** Afternoon (12-5 PM) has the highest accident rate
- **Severity Distribution:** Majority of accidents are Severity 2 and 3

## 🎨 Visualizations

The analysis includes 13 visualizations:

### Time Patterns
- Accidents by hour of day (line graph)
- Accidents by day of week (bar chart)
- Accidents by month (bar chart)
- Time of day distribution (bar chart)
- **Heatmap** showing hour vs day of week patterns

### Geographic Hotspots
- Top 10 cities with most accidents
- Top 10 states with most accidents

### Contributing Factors
- Accident severity distribution
- Weather conditions during accidents
- Temperature distribution
- Visibility distribution
- Road features present (traffic signals, junctions, etc.)
- Severity by time of day (stacked bar)

## 🔧 Tech Stack

- **Python 3.8+**
- **Pandas** - Data manipulation and sampling
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualizations and heatmaps
- **NumPy** - Numerical operations
- **Jupyter Notebook** - Interactive analysis

## 📈 Results Summary

| Metric | Value | Description |
|--------|-------|-------------|
| **Records Analyzed** | 200,000 | Sample from full dataset |
| **Date Range** | 2016-2023 | 7+ years of data |
| **States Covered** | 49 | Nearly all US states |
| **Peak Hour** | 5:00 PM | Evening rush hour |
| **Most Dangerous Day** | Friday | Highest accident frequency |
| **Top State** | California | Most accidents recorded |
| **Average Severity** | ~2.3 | On scale of 1-4 |
| **Common Severity** | 2 | Most frequent level |
| **Weather Conditions** | 10+ types | Including clear, rain, snow, fog |
| **Road Features** | 13 types | Traffic signals, junctions, etc. |

## 🚀 How to Run

1. Download the dataset from Kaggle
2. Upload `US_Accidents_March23.csv` to Jupyter Notebook
3. Run each cell sequentially
4. Wait 2-3 minutes for initial data loading
5. View all visualizations and insights

## 📝 File Name

**Notebook:** `accident_analysis.ipynb`

## 🎯 Key Insights

### Rush Hour Impact
Morning (7-9 AM) and evening (4-6 PM) rush hours show significant spikes in accidents, suggesting traffic volume as a major contributing factor.

### Weekend vs Weekday
Weekdays show higher accident rates than weekends, with Friday being the peak day, likely due to end-of-week fatigue and higher traffic.

### Seasonal Variations
Winter months experience more accidents, possibly due to adverse weather conditions and reduced visibility.

### Geographic Concentration
Accidents are concentrated in highly populated states and urban areas with dense traffic networks.

### Weather Paradox
Surprisingly, most accidents occur during fair weather, indicating that traffic volume matters more than weather conditions alone.

---

**Internship Task 4** - Data Science Internship
