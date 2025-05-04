# dendrite-ds-screening-test
# Dendrite.ai - Data Science Screening Test

## Overview

This repository contains my submission for the Dendrite.ai Data Science internship screening test.  
The script dynamically builds a machine learning pipeline using Scikit-learn, based entirely on a provided JSON configuration.

## Contents

- `screening_test_ds.py` – Main executable script (Colab-compatible)
- `iris.csv` – The sample dataset
- `algoparams_from_ui.json.rtf` – Configuration file describing features, models, and processing
- `README.md` – This file

## How to Run (Google Colab)

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the 3 files into your Google Drive
3. Open and run `final_colab_script.py` from Colab
4. Ensure file paths to the JSON and CSV are correct
5. The pipeline will preprocess, reduce features, train models, and print evaluation metrics.

## Notes

- The script uses Scikit-learn pipelines and `GridSearchCV`
- Supports regression models and multiple feature reduction techniques
- Config-driven logic allows it to adapt to any similar JSON input


