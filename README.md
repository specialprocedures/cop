# Climate Coverage Analysis: COP Conference Impact on News Media

Analysis of climate change news coverage patterns around UN Climate Change Conferences (COP) from 2015-2025 for a [blog post]() on igdr.ch.

## Visualizations

The analysis produces several key visualizations:

1. **Time Series Chart**: Daily climate article counts with 30-day rolling average and annual trends
2. **Year-on-Year Change**: Annual percentage changes in climate coverage
3. **COP Effect Chart**: Coverage increase during COP conferences vs. prior 12-month averages
4. **Pre/Post Glasgow Comparison**: Coverage patterns before and after COP26 (Glasgow 2021)
5. **Grouped Bar Chart**: Direct comparison of COP period vs. preceding period coverage (2021-2025)

## Files

- `cop.ipynb` - Main analysis notebook
- `10_yr_timeline.json` - Daily article counts data (2015-2025)
- `10_yr_timeline_sources.json` - Source publication metadata
- `query.json` - The query used to pull the data

## Output Files

When run, the notebook generates:
- `climate_ts.html` - Interactive time series with COP events (desktop)
- `climate_ts_mobile.html` - Mobile-optimized time series
- `climate_yearly_pct_change.html` - Year-on-year percentage changes
- `cop_effect.html` - COP conference impact visualization
- `climate_pre_post_glasgow.html` - Pre/post COP26 comparison
- `cop_effect_grouped.html` - Grouped comparison of COP vs. baseline periods

## Usage

1. Install required dependencies: `pip install pandas plotly jupyter scikit-learn`
2. Open `cop.ipynb` in Jupyter Lab/Notebook or VS Code
3. Run all cells to reproduce the analysis

## Data

All data sourced from [NewsAPI.ai](https://newsapi.ai/)