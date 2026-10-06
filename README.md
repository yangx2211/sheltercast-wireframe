# ShelterCast

An interactive concept wireframe for animal shelter capacity planning, created for our Time Series Forecasting group project.

**[Open the wireframe](https://yangx2211.github.io/sheltercast-wireframe/)**

## Try the workflow

1. **Setup:** Click **Import demo data**, or select two CSV files (one intake file and one outcome file). Enter current dog and cat occupancy and safe capacity.
2. **Forecasts:** Click **Generate four-week outlook** to explore the illustrative occupancy charts and capacity warnings.
3. **Planning:** Select a species and week, choose possible actions, and click **Submit plan** to see a confirmation.

## Prototype scope

This wireframe demonstrates the proposed user workflow. It does not run or train a forecasting model. All forecast values are illustrative; the project's Jupyter notebook contains the forecasting analysis and backtesting.

CSV selection previews filenames only. File contents are not read or uploaded, and selected files do not change the example forecast. Occupancy and capacity inputs update the illustrative charts and warnings. Submitted plans remain in memory for the current page session and are cleared on reload.

## Run locally

Open `index.html` in a browser. The interface, styles, images, and JavaScript are included in this single file; no installation or build step is required.

## Hosting

Published with GitHub Pages from the `main` branch and repository root. Updating `index.html` on `main` updates the hosted wireframe after deployment.
