# Global Temperature Trend

An interactive single-page web app visualizing global average temperature anomalies from 1880 to 2023, based on the NASA GISS Land-Ocean Temperature Index.

## Features

- **Interactive line chart** with a blue-to-red color gradient — cold years blue, warm years red
- **Linear trend line** overlaid as an orange dashed line
- **Stats cards** showing the hottest year on record, latest anomaly vs. the 1951–1980 baseline, and total warming since 1880
- **Decade averages toggle** to smooth the data into 10-year block averages
- **Dark theme** — fully responsive

## Data

Temperature anomalies (°C) relative to the 1951–1980 baseline, sourced from the [NASA GISS Surface Temperature Analysis (GISTEMP)](https://data.giss.nasa.gov/gistemp/). Data is embedded directly in the app — no network requests required.

## Usage

Open `index.html` in any modern browser. No build step or server required.

## Key Stats (as of 2023)

| Metric | Value |
|---|---|
| Hottest year on record | 2023 (+1.17°C) |
| Total warming since 1880 | +1.33°C |
| Baseline period | 1951–1980 |
