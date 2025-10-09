# Machine Learning Project

## Overview

This is a machine learning project to do various analyses and predictions on the data.

## Project Structure

- `***.ipynb` - Jupyter notebook(s) with the analysis
    - `segmentation.ipynb` - Segmentation analysis
    - `linear-regression.ipynb` - Linear regression analysis of the output of the segmentation
- `madrid_rent_data.xlsx` - Madrid rent data
- `madrid_rent_data_clustered.csv` - Madrid rent data with the clusters assigned to each row from the segmentation
- `requirements.txt` - Python dependencies

## Setup

1. Create a virtual environment:
```bash
python -m venv venv
```

2. Activate the virtual environment:
```bash
# On macOS/Linux:
source venv/bin/activate

# On Windows:
venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```