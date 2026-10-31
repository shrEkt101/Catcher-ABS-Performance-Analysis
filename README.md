# Outline of my project folder: please read this first

I recommend the code cells for all notebooks be collapsed while viewing the notebooks. Some cells are quite big (especially for interactives), making it easy to miss comments I made in between them.

For each folder, please go through the notebooks/files in the following order:

## Problem 1

1. `exploration.ipynb`: I did most of my data exploration along with observations/analysis in this notebook.
2. `p_challenge.ipynb`: Model training for predicting p_challenge was done in this notebook.
3. `p_success_g_challenge.ipynb`: Model training for predicting p_success_g_challenge was done in this notebook. Comments/analysis similar to ones made in p_challenge were omitted, so it is more brief than p_challenge.
4. `data-test-predictions.xlsx`: Test data along with predictions for all required fields. Whenever any of the inputs for either model was missing, I left the outputs as NaN.

`predictions.ipynb` was just used to generate the predictions for data-test, so it can be skipped. I did this in a separate file as the notebooks for model training/evaluation was too long.

## Problem 2

1. `Catcher_Report.pdf`: A simplified one page report of the specified catcher's performance during a single game. Please look at catcher_report.ipynb for a more detailed analysis of the catcher's season performance, which is more reliable than a single game's stats.
2. `catcher_report.ipynb`: The notebook I used to create/generate my own stats and do analysis for this report. Contains more details and analyses. Ideally this should be read alongside the report.


## Further evidence of my thinking

`Scratchwork.pdf`: Most of my scratchwork for problem 1, including planning, questions I had to ask myself, methods I thought of trying, etc, are in this pdf. I did most of my drafting for problem 2 in catcher_report.ipynb.

## Note on interactive cells

The last cell of each notebook is interactive. You can click on keys to highlight a subset of the dataset. Hovering over individual pitches also shows the adjusted strikezone, explaining some seemingly anomalous points.