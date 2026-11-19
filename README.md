# Data Quality Metrics Explained with Pandas

> Course: Programming for Descriptive and Predictive Analytics · Unit 02 · Semester 1

## Overview

Seven small, self-contained demonstrations of the dimensions of data quality: **completeness, accuracy, timeliness, consistency, uniqueness, duplication and data usage**. Each dimension is illustrated with a tiny synthetic dataframe and a concrete Pandas operation, so the notebook works as a reusable teaching toolkit rather than a single-case analysis.

## Repository structure

- `notebooks/data-quality-metrics.ipynb` - seven executed demonstrations.
- `data/dirtydata.csv` - 32-row sample with missing values used to extend the exercises.

## Methods

- `isna()`, `notna()` and null counts for completeness.
- Type checks and range validation for accuracy.
- `datetime` parsing and freshness checks for timeliness.
- Cross-column consistency rules.
- `duplicated()` and `drop_duplicates()` for uniqueness and duplication.
- Basic usage/KPI checks derived from the data itself.

## Results

The notebook produces readable textual output for each dimension instead of a single summary number. It intentionally uses synthetic data so that each defect is isolated and easy to recognize.

## Requirements

`pandas`, `numpy` and `jupyter`. No external data download is required; the sample CSV is included.

## How to run

```bash
jupyter notebook notebooks/data-quality-metrics.ipynb
```

---
Author: Karla Maria Monroy Alvarez
