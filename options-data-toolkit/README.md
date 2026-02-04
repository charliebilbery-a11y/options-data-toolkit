# options-data-toolkit

Utilities and interfaces for fetching, normalizing, and structuring options market data in a research-friendly format.

## Overview
This repository provides reusable building blocks for working with options market data:
- Provider interfaces for fetching option chains
- Normalization utilities that convert raw option data into flat, analysis-ready tables
- Mock data providers for local testing and research

The focus is on **data engineering and research workflows**, not trading strategies or execution systems.

## What this repo is
- Options chain normalization
- Provider abstractions (mock, REST-style, etc.)
- Clean schemas for downstream research and visualization

## What this repo is not
- No trading strategy logic
- No execution or order management
- No proprietary signals or parameters

## Intended use
This toolkit is designed to be used by:
- Research notebooks
- Visualization dashboards
- Backtesting frameworks
- Educational or experimental projects

## Status
Early-stage research toolkit. APIs may evolve.
