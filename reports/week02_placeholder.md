# Week 2 Report
# Week 2 Progress Report

## Goal
Integrate all four data sources into the project pipeline.

## Tasks Completed
- ✅ Downloaded StatsBomb competitions data → processed into `statsbomb_clean.parquet`
- ✅ Parsed Transfermarkt data (from cache) → processed into `transfermarkt_clean.parquet`
- ✅ Collected Twitter mentions (placeholder) → processed into `twitter_clean.parquet`
- ✅ Added Injury history dataset (placeholder) → processed into `injury_clean.parquet`

## Deliverables
- Cleaned parquet files are available locally in `data/processed/`
  - `statsbomb_clean.parquet`
  - `transfermarkt_clean.parquet`
  - `twitter_clean.parquet`
  - `injury_clean.parquet`

## Notes
- Current datasets are placeholders for structure validation.
- Next step (Week 3): Expand features (player_name, club, age, market_value, injuries, sentiment_score, performance metrics).
- Data files are **excluded from GitHub** via `.gitignore` to keep the repo lightweight.


