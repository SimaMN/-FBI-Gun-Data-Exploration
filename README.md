
# Gun and Census Data Analysis

## Project Overview

This project investigates the relationship between gun purchase trends and various demographic and socioeconomic factors in the United States. By analyzing data from the FBI's National Instant Criminal Background Check System (NICS) alongside U.S. Census data, the project aims to answer key questions about gun ownership patterns and how they correlate with state demographics. Specifically, it examines the following questions:

1. What census data is most associated with high gun per capita?
2. Which states have had the highest growth in gun registrations?
3. What is the overall trend of gun purchases in recent years?

## Data Sources

- **NICS Data**: This dataset contains monthly firearm background checks conducted by the FBI in each state. It serves as a proxy for tracking gun purchase trends over time.
- **U.S. Census Data**: Census data provides demographic, socioeconomic, and population-related information, which helps contextualize gun ownership patterns across different states.

## Project Structure

```plaintext
├── data/                   # Directory containing raw data files
│   ├── nics_data.csv       # Processed NICS gun data
│   └── census_data.csv     # Census data with relevant demographic information
├── analysis/               # Scripts and notebooks for data analysis
│   ├── data_cleaning.py    # Script to clean and preprocess raw data
│   └── data_analysis.ipynb # Jupyter notebook with detailed analysis
├── results/                # Directory for output data and visualizations
├── README.md               # Project overview and details
└── requirements.txt        # Python dependencies for the project
```

## Installation

To set up the project, follow these steps:

1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd gun-census-data-analysis
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

The analysis is contained within Jupyter notebooks and Python scripts in the `analysis/` directory. To run the analysis:

1. Open `data_analysis.ipynb` in Jupyter Notebook:
   ```bash
   jupyter notebook analysis/data_analysis.ipynb
   ```
2. Follow the cells to view the data exploration, analysis, and visualizations addressing the research questions.

3. For data cleaning and preprocessing, execute `data_cleaning.py`:
   ```bash
   python analysis/data_cleaning.py
   ```

## Key Findings

1. **Demographic Correlations**: Certain demographic factors such as population density, median income, and urbanization level have shown significant associations with gun ownership per capita.
2. **Gun Registration Growth**: States with higher recent population growth tend to have increasing rates of gun purchases, with some states showing more accelerated growth than others.
3. **Purchase Trends**: Nationally, gun purchase trends reveal both seasonal patterns and long-term shifts, potentially influenced by policy changes, sociopolitical events, and economic factors.

## Visualizations

The `results/` directory contains key visualizations from the analysis, including:
- State-wise gun purchase trends over time
- Correlation charts between gun per capita and demographic factors
- Heatmaps illustrating high-growth states in terms of gun ownership

## Dependencies

The project relies on the following Python libraries:
- `pandas` (Data manipulation)
- `numpy` (Numerical operations)
- `matplotlib` and `seaborn` (Data visualization)

To install these, ensure the `requirements.txt` file is used, or install manually if required.

## Conclusion

This analysis provides insights into the demographic factors associated with gun ownership and trends in gun purchases across the United States. Understanding these patterns can help inform discussions around policy, public health, and social issues related to gun ownership.
