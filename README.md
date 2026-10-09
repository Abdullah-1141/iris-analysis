# Iris Dataset Analysis

A Python data analysis project using Pandas and Jupyter Notebook, managed with `uv`.

## Project Structure

- `data/iris.csv`: Original Iris dataset downloaded using `curl`.
- `output/species_summary.csv`: Average numeric measurements for each species.
- `output/filtered_iris.csv`: Flowers with `sepal_length > 6`.
- `iris_analysis.ipynb`: Jupyter Notebook containing the analysis.
- `pyproject.toml`: Project configuration and dependencies.
- `uv.lock`: Locked dependency versions.

## Setup and Execution Instructions

1. Install Python and `uv`.
2. Open a terminal in the project folder.
3. Install the project dependencies:

   ```bash
   uv sync
   ```

4. Start Jupyter Notebook:

   ```bash
   uv run jupyter notebook
   ```

5. Open `iris_analysis.ipynb` and run the notebook cells from start to finish.

## Analysis Summary

- Loaded and explored the Iris dataset using Pandas.
- Checked for missing values and duplicate rows.
- Calculated descriptive statistics and species-level averages.
- Filtered flowers based on sepal length and petal width.
- Identified the species with the highest average petal length.
- Sorted the dataset by sepal length in descending order.
- Exported the analysis results to CSV files.

## Output Files

- `output/species_summary.csv`
- `output/filtered_iris.csv`

## Findings

The dataset contains 150 rows and 5 columns, representing three Iris species. See the Jupyter Notebook for the detailed analysis results.