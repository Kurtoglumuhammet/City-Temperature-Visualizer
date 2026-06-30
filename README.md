# City Temperature Visualizer

This Python script queries a global temperature dataset based on user input (Region, Country, City, Date) and visualizes the average temperature for that specific day using Seaborn and Matplotlib.

## Features
* Filters large datasets using Pandas.
* Handles missing/placeholder data (e.g., -99 values).
* Provides bar chart visualization of the queried temperature.

## Requirements
* pandas
* matplotlib
* seaborn

**Note:** This script is designed to run on Google Colab and mounts a Google Drive for the dataset. If running locally, remove the `google.colab` imports and update the CSV file path.
