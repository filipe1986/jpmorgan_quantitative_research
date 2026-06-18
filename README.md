# J.P. Morgan Quantitative Research – Commodity Price Extrapolation 📈

This repository contains my completed production pipeline for the **J.P. Morgan Quantitative Research** program simulation on Forage. The goal of this project is to analyze, interpolate, and accurately forecast natural gas prices using advanced data engineering and statistical modeling.

## 🚀 Key Features
- **Data Engineering:** Used Python and Pandas to apply linear interpolation, downsampling monthly commodity data into a clean, continuous daily timeline.
- **Statistical Modeling:** Isolated the macro-economic price trend using SciPy's `linregress` tool, then extracted and normalized monthly seasonal deviations.
- **Defensive UI Design:** Built a native desktop graphical user interface (GUI) using Tkinter. It forces separate inputs for Year, Month, and Day to eliminate user formatting errors.

## 🛠️ Tech Stack
- **Language:** Python 3
- **Libraries:** Pandas, Matplotlib, SciPy, Tkinter

## 📊 Final Forecast Visualization
When a target date is inputted through the native interface, the model dynamically calculates the baseline trend projection, combines the cyclical seasonal adjustment factor, and outputs a complete visualization tracking historical pricing against the newly extrapolated timeline.
