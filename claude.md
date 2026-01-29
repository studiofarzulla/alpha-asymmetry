---
zettelkasten-id: 20250910052535
created: 2025-09-10 05:25
---

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a forex analysis project focused on EUR/JPY trading data and alpha asymmetry analysis. Currently contains Excel audit data from August 2025.

## Project Status

**Initial setup phase** - Repository contains forex audit data but no code implementation yet.

## Planned Development Structure

### Python-based Analysis Project
The project will use Python for financial data analysis with the following structure:

```
alpha_assymetry/
├── src/           # Analysis modules
├── data/          # Raw and processed forex data
├── reports/       # Generated analysis reports
├── tests/         # Test files
└── temp/          # Temporary files (not committed)
```

## Commands (To Be Implemented)

### Python Environment Setup
```bash
# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # Unix/MacOS

# Install dependencies (when requirements.txt exists)
pip install -r requirements.txt
```

### Planned Analysis Commands
- `python analyze.py` - Run forex data analysis
- `python generate_report.py` - Generate analysis reports
- `python import_data.py` - Import Excel data
- `python backtest.py` - Run backtesting strategies

## Key Technical Considerations

### Data Processing
- The Excel file `audit_EURJPY.forex_20250818 (1).xlsx` contains forex audit data
- Use pandas with openpyxl for Excel file handling
- Implement data validation before processing

### Analysis Focus
- Alpha asymmetry identification in EUR/JPY pairs
- Market inefficiency quantification
- Bid-ask spread pattern analysis
- Price movement asymmetries

### Report Generation
All reports should be saved to `reports/` directory with naming convention:
- `FOREX_ANALYSIS_[PAIR]_[DATE].md`
- `ASYMMETRY_REPORT_[DATE].md`
- `BACKTEST_[STRATEGY]_[DATE].md`

## Development Guidelines

### Python Code Style
- Use pandas DataFrames for tabular data
- Type hints for all functions
- snake_case for functions/variables
- Group imports: standard library, third-party, local

### Error Handling
- Validate numerical inputs to prevent calculation errors
- Use specific exception handling
- Log all data transformations

### Security
- Never commit sensitive trading data or API keys
- Use environment variables for credentials
- Store only anonymized data in version control