# ARTI406 - Assignment 2

## Dataset Description

This assignment uses the Kaggle dataset `algozee/teenager-menthal-healy`.
The downloaded dataset file is:

- `Teen_Mental_Health_Dataset.csv`

The dataset contains **1,200 rows** and **13 columns** about teenage mental health, lifestyle, and social media behavior.

## Columns

- `age`: teenager age
- `gender`: gender category
- `daily_social_media_hours`: daily social media usage in hours
- `platform_usage`: main platform category
- `sleep_hours`: daily sleep hours
- `screen_time_before_sleep`: screen time before sleeping
- `academic_performance`: academic performance score
- `physical_activity`: physical activity level
- `social_interaction_level`: low, medium, or high social interaction
- `stress_level`: stress level score
- `anxiety_level`: anxiety level score
- `addiction_level`: social media addiction level score
- `depression_label`: binary depression label

## Assignment Work

The notebook `ARTI406 - Assignment 2.ipynb` performs:

- loading the latest Kaggle dataset with `kagglehub`
- fallback loading from the local CSV file
- data type and summary-statistics checks
- missing-value assessment and imputation demonstration
- IQR-based outlier detection and handling
- Min-Max normalization
- Z-score standardization
- correlation analysis
- PCA visualization and interpretation

## Generated Images

The notebook saves the following plots in the `images/` folder:

- `images/missing_values.png`
- `images/outliers_boxplot.png`
- `images/correlation_heatmap.png`
- `images/pca_projection.png`
- `images/depression_label_distribution.png`

