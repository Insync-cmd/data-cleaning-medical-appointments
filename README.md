# data-cleaning-medical-appointments
Data cleaning &amp; preprocessing of the Kaggle Medical Appointment No Shows dataset using Python (Pandas). Includes notebook, cleaned dataset, and a short summary.


# Medical Appointment - Data Cleaning

**Project:** Data cleaning & preprocessing of the Kaggle "Medical Appointment No Shows" dataset  
**Author:** Saravana Chandran  
**Date:** 22-09-2025

## Overview
This repository contains a step-by-step data cleaning process for the "Medical Appointment No Shows" dataset using Python and Pandas. The goal is to produce a clean dataset ready for analysis or modeling.

## Files
- `notebooks/01_data_cleaning_medical_appointments.ipynb` — Colab-ready notebook with explanations & code.
- `data/raw/` — original dataset (zips or raw CSV).
- `data/cleaned/medical_appointment_cleaned.csv` — cleaned dataset output.
- `reports/CLEANING_SUMMARY.md` — short summary of changes made.
- `requirements.txt` — dependencies.

## Key cleaning steps
1. Inspect data (shape, dtypes, missing, duplicates).
2. Rename columns to snake_case.
3. Parse date columns to datetime.
4. Standardize text (strip, lower, unify categories).
5. Handle missing values (median for numeric, mode/'unknown' for categorical).
6. Remove duplicates and invalid records (e.g., age < 0 or > 120).
7. Save cleaned dataset and a summary.

## How to run (local)
1. Clone the repo.
2. Put the raw dataset into `data/raw/`.
3. Open the notebook in Jupyter/Colab and run all cells, or run `scripts/cleaning_pipeline.py`.

## License
MIT

## Contact
<Your Name> — <your email / GitHub profile>
