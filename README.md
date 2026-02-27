# Medical Data Visualizer

A data visualization project that analyzes medical examination data to explore the relationship between cardiac disease, body measurements, blood markers, and lifestyle choices.

## Features

- **Data Processing**: Calculates BMI and categorizes patients as overweight/not overweight
- **Data Normalization**: Standardizes cholesterol and glucose values for analysis
- **Categorical Plot**: Visualizes the distribution of health factors split by cardiovascular disease presence
- **Correlation Heatmap**: Shows relationships between different health metrics

## Requirements

```
pandas
matplotlib
seaborn
numpy
```

## Usage

The project includes two main visualization functions:

1. **`draw_cat_plot()`** - Creates a categorical plot showing counts of health factors
2. **`draw_heat_map()`** - Generates a correlation matrix heatmap with cleaned data

## Data

The analysis uses `medical_examination.csv` which contains patient data including:

- Height and weight measurements
- Blood pressure readings
- Cholesterol and glucose levels
- Lifestyle factors (smoking, alcohol consumption, physical activity)
- Cardiovascular disease diagnosis

## Installation

```bash
pip install pandas matplotlib seaborn numpy
```

Run the Jupyter notebook `medical_data_visualizer.ipynb` to see the analysis and visualizations.
