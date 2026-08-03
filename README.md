# ML-US-Cars-Accidents
This is a machine learning project focused on predicting accident severity for US car accidents, based on contextual features available at the time of the event.

## Setup

1. Ensure Python 3.11+ is installed.
2. Create and activate a virtual environment:
   - `python -m venv .venv`
   - `.venv\Scripts\activate`
3. Install dependencies:
   - `pip install -r requirements.txt`

## Project structure

- `Data/` - original dataset files in Parquet format.
- `Extra/` - project description and dataset schema.
- `src/` - source code for data loading, feature engineering, modeling and utilities.
- `notebooks/` - Jupyter notebooks for analysis and experimentation.
- `reports/` - output reports and documentation.

## How to start

- Use the dataset sample in `Data/US_accidents_dataset_subsample.parquet` for fast iteration.
- Build EDA and model experiments in `notebooks/`.
- Keep code organized under `src/` as the project grows.

## Notes

- The repository currently includes the baseline project structure and dependency file.
- Next step: add analysis notebooks and modeling code in `src/`.
