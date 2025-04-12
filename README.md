# EDA-CMHC-Maine-Market-Intel

Exploratory Data Analysis done for CMHC vs Maine for the state of Maine, USA. This is done on County level and Zip level, to get a sense of network coverage, surgical proximity and network-leakage for CMHC w.r.t its primary competitor in the region - MaineHealth.

## Project Overview

This project analyzes healthcare data for Central Maine Healthcare (CMHC) compared to its primary competitor, MaineHealth, across the state of Maine. The analysis focuses on several key metrics:

1. **Market Share Analysis**: Visualization of CMHC's market penetration across different zip codes
2. **Network Coverage**: Geographical distribution of healthcare services
3. **Surgical Proximity**: Analysis of distance to surgical facilities 
4. **Network Leakage**: Examination of services being referred outside of the CMHC network

## Data Sources

The project uses the following data sources:
- Geographic zip code data for Maine
- CMHC service statistics by zip code
- Healthcare referral patterns
- Facility location data

## Visualizations

The project includes several interactive heatmaps:
- `cmhc_heatmap_market_share.html`: Visualizes market share by zip code
- `cmhc_heatmap_leakage.html`: Shows network leakage patterns
- `cmhc_heatmap_surgical_proximity.html`: Displays proximity to surgical facilities

## Directory Structure

```
EDA-CMHC-Maine-Market-Intel/
├── data/                   # Data files
│   ├── raw/                # Original data files
│   └── processed/          # Cleaned and processed data
├── notebooks/              # Jupyter notebooks
├── visualizations/         # Generated heatmaps and other visualizations
├── src/                    # Source code for utility functions
└── requirements.txt        # Required Python packages
```

## Getting Started

### Prerequisites

- Python 3.8+
- Required packages listed in requirements.txt

### Installation

1. Clone this repository
2. Install required packages:
   ```
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebooks to reproduce analysis

## Key Findings

- Market share varies significantly across Maine zip codes
- Distance to facilities is a key factor in healthcare utilization
- Patterns of network leakage reveal opportunities for service expansion

