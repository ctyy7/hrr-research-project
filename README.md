# HRR Research Project

## Research Question

How do different mental conditions, specifically stress and calm states, affect heart rate recovery after exercise?

## Project Overview

This project investigated whether heart rate recovery (HRR) differed between stress and calm conditions. HRR was calculated by subtracting heart rate 60 seconds after exercise from the post-exercise heart rate.

The project used 16 total trials. Each trial recorded the trial number, date, condition, pre-exercise heart rate, post-exercise heart rate, heart rate after 60 seconds, HRR, exertion scale, stress scale, and side notes.

## Methods

Heart rate data was collected across calm and stress conditions. For each trial, HRR was calculated using:

HRR = post-exercise heart rate - heart rate after 60 seconds

The data was organized in CSV files and analyzed in a Jupyter notebook. The analysis included summary statistics, visualizations, and an independent samples t-test comparing HRR between the stress and calm conditions.

## Tools Used

- Python
- pandas
- matplotlib
- NumPy
- SciPy
- Jupyter Notebook
- GitHub

## Main Files

- `notebooks/01_create_research_table.ipynb` — main Jupyter notebook for data organization, analysis, graphs, and statistical testing
- `data/hrr_data.csv` — final HRR dataset
- `data/research_data.csv` — original research dataset
- `figures/graph1_final.png` — mean HRR by condition with standard deviation error bars
- `figures/graph2_final.png` — HRR over time by condition
- `figures/graph3_final.png` — individual trial HRR values with trendlines

## How to Run the Notebook

1. Clone or download this repository.
2. Open Terminal.
3. Navigate to the project folder:

```bash
cd hrr-research-project
