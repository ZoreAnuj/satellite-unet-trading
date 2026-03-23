# Satellite U-Net for Trading Signals

This project applies U-Net semantic segmentation to satellite imagery to generate counter-trend trading signals and geospatial economic indicators. It explores the intersection of computer vision and quantitative finance by extracting actionable insights from overhead visual data.

## Key Features
*   Processes temporal satellite imagery to identify spatial patterns.
*   Implements a U-Net model for semantic segmentation of economic activity.
*   Translates segmentation masks into quantitative trading signals.
*   Backtests signal performance to evaluate predictive alpha.

## Tech Stack
*   Python, PyTorch
*   Rasterio, GDAL
*   NumPy, Pandas
*   Jupyter Notebooks

## Getting Started
1.  Clone the repo: `git clone https://github.com/zoreanuj/satellite-unet-trading.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Run the example notebook: `jupyter notebook notebooks/example_analysis.ipynb`