# Mining Quality — Flotation Plant

This folder contains an exploratory notebook that predicts mineral/ore quality (e.g., % silica concentrate) using the Flotation Plant dataset. The main artifact is `mining_quality.ipynb`.

## Notebook
- `mining_quality.ipynb` — data loading, cleaning, correlation analysis, feature selection, modeling (Linear, Ridge, RandomForest, GradientBoosting) and evaluation (R2, RMSE, MAE, cross‑validation).

## Key steps in the notebook
- Load dataset and inspect shape / types
- Data cleaning: drop duplicates, replace separators, coerce numeric types
- Correlation analysis and dropping highly collinear features
- Baseline modeling with RandomForest and selected features
- Model comparison (Linear, Ridge, RandomForest, GradientBoost) and cross‑validation

## Limitations
- Data conversions may coerce invalid values to NaN — verify data formatting prior to running at scale.
- Some helper functions (e.g., RMSE wrapper) may need to be defined or imported if running outside the notebook context.

