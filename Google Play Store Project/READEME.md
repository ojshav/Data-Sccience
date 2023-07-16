# Google Play Store App Analytics Data Science Project

This GitHub repository contains a data science project focused on performing a comprehensive analysis of the Android app market by comparing thousands of apps in the Google Play Store. The project involves various data manipulation techniques, such as sampling, handling duplicate entries, and converting data types. Additionally, it utilizes the Plotly library to generate visually appealing visualizations, including pie charts, donut charts, bar charts, box plots, and scatter plots.

## Project Overview

The goal of this project is to gain insights into the Android app market by analyzing a dataset of Google Play Store apps. The analysis covers various aspects, such as app categories, ratings, reviews, installs, and more. By exploring this dataset, we aim to identify trends, patterns, and relationships that can help app developers, marketers, and stakeholders make data-driven decisions.

## Learning Points

Throughout the project, we explored and applied various data manipulation and visualization techniques. Some of the key learning points include:

1. **Random Sampling**: We learned how to pull a random sample from a DataFrame using the `.sample()` function. This method allows us to obtain a representative subset of the data for analysis without bias.

2. **Handling Duplicates**: We explored how to identify and handle duplicate entries in the dataset using `.duplicated()` and `.drop_duplicates()`. Removing duplicates ensures data integrity and prevents overrepresentation of certain apps.

3. **Data Type Conversion**: We encountered scenarios where data was stored as strings or objects instead of numeric types. We learned how to use `.to_numeric()` to convert these data types into numeric values, making them suitable for analysis.

4. **Plotly Visualizations**: We leveraged Plotly, a powerful Python library, to create stunning visualizations. We explored generating pie charts, donut charts, bar charts, box plots, and scatter plots to present the data in an informative and visually appealing manner.

## Summary of Findings

The data analysis and visualizations revealed valuable insights into the Google Play Store app market. We gained a better understanding of the distribution of apps across different categories, the popularity of various app genres, and how user ratings and reviews influence app performance. Moreover, we explored relationships between the number of installs and app categories, which can be crucial for developers and marketers when planning app releases.

The interactive nature of Plotly visualizations allowed us to explore the data from different angles and identify trends and outliers effectively. The pie and donut charts provided a clear overview of app category distribution, while bar charts helped compare app metrics between different groups. Box plots and scatter plots enabled us to spot potential correlations and identify potential outliers within the data.

## Repository Structure

The repository is organized as follows:

```
/
|-- data/
|   |-- google_play_store_apps.csv
|-- notebooks/
|   |-- app_analytics.ipynb
|-- README.md
```

- The **data** directory contains the dataset file `google_play_store_apps.csv`, which serves as the input for the data analysis and visualization.

- The **notebooks** directory contains the Jupyter Notebook file named `app_analytics.ipynb`. This notebook contains the entire data analysis process, including data cleaning, manipulation, and visualization using Python code.

- The **README.md** file (this file) provides an overview of the project, learning points, and repository structure.

## Usage

To explore the analysis and visualizations, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/google-play-store-app-analytics.git
   ```

2. Install the required dependencies by running:
   ```
   pip install pandas plotly
   ```

3. Open the `app_analytics.ipynb` Jupyter Notebook in the **notebooks** directory using Jupyter Notebook or JupyterLab.

4. Execute the code cells to run the data analysis and generate the visualizations.

5. Feel free to modify the notebook and experiment with different visualizations or analysis techniques.

## Contributions

Contributions to this project are welcome! If you have any suggestions, improvements, or additional analyses, feel free to open an issue or submit a pull request.

When contributing to this repository, please ensure that your code adheres to best practices and is well-documented. Clearly explain the purpose and approach of your contribution.


