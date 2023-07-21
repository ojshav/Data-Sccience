# Nobel Prize Analysis Data Science Project

This GitHub repository contains a data science project focused on analyzing the Nobel Prize data. The Nobel Prize, established through the will of Alfred Nobel, is awarded to individuals or organizations that have made significant contributions to humanity in the fields of chemistry, literature, physics, physiology or medicine, economics, and peace. The project involves uncovering insights from the Nobel Prize data, exploring trends, and visualizing various aspects of the prize's history.

## Project Overview

The Nobel Prize is one of the most prestigious awards in the world, recognizing exceptional contributions to society and human welfare. This project aims to analyze the Nobel Prize data to uncover trends, patterns, and interesting insights. By exploring the data, we can gain a better understanding of the distribution of prizes across different categories, identify noteworthy laureates, and explore how the prizes have evolved over time.

## Learning Points

Throughout the project, we covered a wide range of data manipulation and visualization techniques. Some of the key learning points include:

1. **Handling NaN Values**: We learned how to identify and investigate missing or NaN values in the dataset, ensuring data integrity and making informed decisions about how to handle them.

2. **Data Type Conversion**: We explored converting object and string data types to numeric values, preparing the data for analysis and visualization.

3. **Plotly Visualizations**: We created donut charts, bar charts, and choropleths using Plotly to visualize the Nobel Prize data, allowing for interactive and engaging representations of the data.

4. **Rolling Average**: We used a rolling average to smooth out time-series data and visualize trends over time, providing a clearer picture of the data's patterns.

5. **Data Aggregation and Grouping**: We utilized Pandas' `.value_counts()`, `.groupby()`, `.merge()`, `.sort_values()`, and `.agg()` methods to analyze and aggregate the Nobel Prize data based on different criteria.

6. **Seaborn Visualizations**: We employed Seaborn to create various visualizations, such as Sunburst charts, bar charts with different segments, and histogram plots to explore data distribution and descriptive statistics.

7. **Linear Regression with Seaborn**: We used Seaborn's `.lmplot()` to show best-fit lines across multiple categories, providing insights into relationships within the data.

## Summary of Findings

The analysis of the Nobel Prize data revealed fascinating insights into the history and distribution of the prestigious awards. Through visualizations like choropleths, donut charts, and bar charts, we explored how different categories of Nobel Prizes have been awarded over time and how different regions have contributed to the laureates' accomplishments. Additionally, linear regression analysis helped us understand potential trends and correlations within the data, and histogram plots allowed us to visualize the data distribution and draw descriptive statistics.

The project's findings can offer valuable information to researchers, historians, and anyone interested in understanding the impact of Nobel Prizes on society and human progress. The visualizations provide an accessible and engaging way to communicate the historical significance and patterns of the Nobel Prize awards.

## Repository Structure

The repository is organized as follows:

```
/
|-- data/
|   |-- nobel_prize_data.csv
|-- notebooks/
|   |-- nobel_prize_analysis.ipynb
|-- README.md
```

- The **data** directory contains the dataset file `nobel_prize_data.csv`, which serves as the input for the data analysis and visualization.

- The **notebooks** directory contains the Jupyter Notebook file named `nobel_prize_analysis.ipynb`. This notebook contains the entire data analysis process, including data cleaning, manipulation, visualization, and statistical analysis using Python code.

- The **README.md** file (this file) provides an overview of the project, learning points, and repository structure.

## Usage

To explore the analysis and visualizations, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/nobel-prize-analysis.git
   ```

2. Install the required dependencies by running:
   ```
   pip install pandas plotly seaborn
   ```

3. Open the `nobel_prize_analysis.ipynb` Jupyter Notebook in the **notebooks** directory using Jupyter Notebook or JupyterLab.

4. Execute the code cells to run the data analysis, visualization, and statistical models.

5. Feel free to modify the notebook and experiment with different visualizations or analysis techniques.

## Contributions

Contributions to this project are welcome! If you have any suggestions, improvements, or additional analyses, feel free to open an issue or submit a pull request.

When contributing to this repository, please ensure that your code adheres to best practices and is well-documented. Clearly explain the purpose and approach of your contribution.

