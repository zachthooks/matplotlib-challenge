# matplotlib-challenge
Project Overview

This notebook performs exploratory data analysis on data from a pharmaceutical study, investigating the effects of various drug regimens on mouse tumor growth. It involves cleaning, analyzing, and visualizing the data to uncover trends and insights.
Files Included

  pymaceuticals_starter.ipynb: Jupyter Notebook containing the full analysis.
  data/Mouse_metadata.csv: Metadata about the mice involved in the study.
  data/Study_results.csv: Results of the study, including tumor volume measurements and treatment regimens.

Dependencies

Ensure the following libraries are installed before running the notebook:

  pandas: For data manipulation.
  matplotlib: For generating plots.
  scipy: For statistical analysis.

You can install these dependencies using:

    pip install pandas matplotlib scipy

Notebook Structure

  Data Import: Reads data from the CSV files and merges them into a single DataFrame.
  Data Cleaning: Identifies and removes duplicate entries to ensure accurate analysis.
  Analysis and Visualization:
  Computes statistics such as the number of unique mice in the dataset.
  Further cells likely involve data visualization and analysis to examine the effect of drug regimens on tumor volume.

How to Use

  Place the Mouse_metadata.csv and Study_results.csv files in a data folder within the project directory.
  Open pymaceuticals_starter.ipynb in Jupyter Notebook or JupyterLab.
  Run each cell sequentially to load, clean, and analyze the data.

Key Outputs

  Summary statistics of the data.
  Visualizations of tumor volume against variables like time, drug regimen, and mouse weight.
