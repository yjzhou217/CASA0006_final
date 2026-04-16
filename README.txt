Seattle Parking Project Submission

This document includes material of CASA0006 Data Science coursework
The research topic is an analysis of spatial variations in the utilisation of on-street paid parking spaces in Seattle’s city centre and the factors influencing them.

## Notes on Large Files
Due to GitHub’s file size limits, some of the larger raw data and spatial data files have not been uploaded to this repository and have been stored separately on Google Drive:

https://drive.google.com/drive/folders/1LDUiIl2yemsWp9dk5flWo4HIk_fWzauW

Before running the notebook, if you wish to fully reproduce the results, please download the relevant large files and place them in the local `data/` folder.

Large files:
- output/downtown4_march_2025_raw.csv
- data/Zoned_Development_Capacity_Layers_2016-shp/3568c7ec-ce1a-470f-a78e-3efd5886dc192020329-1-x3g6mb.i43zm.dbf
- data/commercial_core_march_2025_raw.csv
- data/first_hill_march_2025_raw.csv
- data/belltown_march_2025_raw.csv
- data/Building_Outlines_2023_-7575316039447773230/Building_Outlines_2023.shp
- data/Building_Outlines_2023_-7575316039447773230/Building_Outlines_2023.dbf
- data/pioneer_square_march_2025_raw.csv

## File contents
- `0006assessment.ipynb`：the final Submission
- `data/`：part of the dataset (under 50M)
- `output/`：Some of the result files generated whilst the notebook was running (under 50M)

## Data Notes
This project primarily uses open data from the City of Seattle, including:
- 2025 Paid Parking Occupancy
- Seattle Streets
- Parcels
- SDOT Pay Stations

Study area:
- Belltown
- Commercial Core
- Pioneer Square
- First Hill

## Notes
This repository is intended for the submission of coursework and instructions on how to reproduce the results; the contents of the notebooks should match the final PDF submitted.