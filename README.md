# Apparent land–atmosphere coupling depends on where soil moisture is measured

Code and processed data used to generate the analyses and figures in Rigden et al. (submitted for peer-review).

## Contents

- `00A_DownloadData.ipynb`  
  Download USCRN daily observations.

- `00B_FormatData_clean.ipynb`  
  Preprocess and format data for analysis.

- `USCRN_paper_workflow_master_revised.ipynb`  
  Main analysis and figure generation.

- `uscrn_processed/`  
  Processed dataset required to reproduce figures.

## Data

Raw USCRN data are publicly available from NOAA and can be downloaded using `00A_DownloadData.ipynb`.

A large processed NetCDF file (`uscrn_daily_station_time_2000_2026.nc`) is not included due to GitHub file size limits. It can be regenerated from the preprocessing workflow.

## Reproducibility

To reproduce results:
1. Run `00A_DownloadData.ipynb`
2. Run `00B_FormatData_clean.ipynb`
3. Run `USCRN_paper_workflow_master_revised.ipynb`

## License

MIT License. Data are subject to their original providers.
