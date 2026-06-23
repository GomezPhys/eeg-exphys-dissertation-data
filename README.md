# EEG Exphys Dissertation Data

Repository for organizing dissertation data, analysis code, metadata, and reproducible outputs for EEG and exercise physiology work.

## Repository Layout

- `data/raw/`: original data exports. Keep these immutable after ingest.
- `data/processed/`: cleaned or transformed datasets derived from raw data.
- `metadata/`: data dictionaries, acquisition notes, participant/session manifests, and protocol details.
- `notebooks/`: exploratory analysis notebooks.
- `scripts/`: reusable processing and analysis scripts.
- `results/figures/`: generated figures for review and dissertation writing.
- `results/tables/`: generated statistical tables and summaries.
- `docs/`: project notes, methods documentation, and writeups.

## Data Handling Notes

Do not commit identifiable participant information or protected health information. Store large raw files with Git LFS or an external data store when needed, and document how to retrieve them in `metadata/`.
