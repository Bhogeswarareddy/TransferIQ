# Week 3 Report
# Week 3 — Feature Engineering Progress

## Goals
- Transform cleaned datasets into ML-ready features.
- Implement initial feature engineering pipeline for:
  - Player performance (StatsBomb)
  - Sentiment (Twitter)
  - Injuries
  - Contracts

## Deliverables
- `data/features/features_time_series.parquet` (performance trends)
- `data/features/features_aggregates.parquet` (sentiment aggregates)
- Injury + Contract features: placeholders created (no parquet yet)

## Notes
- StatsBomb performance features: time-series trends per player.
- Sentiment: aggregated placeholders (Twitter API to be integrated later).
- Injury/Contract: scripts executed successfully but need real data.
- Next step: merge all feature sets into `features_master.parquet` for modeling.

## Success Criteria
- Feature scripts run end-to-end without errors ✅
- Parquet files generated for performance & sentiment ✅
- Ready to start Week 4 baseline modeling 🚀

