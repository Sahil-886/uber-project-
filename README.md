Aggregated & Preprocessed Traffic Data Pipeline

Author: Sahil Makhamale

This project builds a robust data preprocessing pipeline for a traffic volume dataset. It converts raw timestamped junction data into a clean, hourly aggregated, feature-rich dataset ready for machine learning model training and submission.

The pipeline focuses on correctness, reproducibility, and time-series feature engineering.

 Project Goals

Load and validate raw traffic dataset

Clean and standardize columns and datatypes

Handle missing values and duplicates safely

Aggregate traffic counts at hourly level per junction

Engineer time-based and lag features

Scale target variable for ML readiness

Export final processed dataset for modeling
