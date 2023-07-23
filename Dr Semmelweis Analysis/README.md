# Dr. Semmelweis Handwashing Discovery Data Science Project

This GitHub repository contains a data science project centered around the groundbreaking discovery of Dr. Ignaz Semmelweis, a Hungarian physician born in 1818, who worked at the Vienna General Hospital. In the 1800s, when the prevailing belief was that illnesses were caused by "bad air" or evil spirits, Dr. Semmelweis took a different approach. He analyzed data and observed a concerning number of women dying from childbed fever (puerperal fever) in the maternity wards. His investigation led to a revolutionary discovery that would significantly impact medical practices.

## Project Overview

The focus of this project is to understand and analyze Dr. Semmelweis's findings and his discovery of the importance of handwashing in preventing the spread of infection in maternity wards. By diving into the historical data and using data visualization techniques, we aim to gain insights into the impact of handwashing on reducing mortality rates and how this discovery changed medical practices in the 19th century.

## Learning Points

Throughout the project, we explored various data visualization and analysis techniques. Some of the key learning points include:

1. **Histograms Visualization**: We learned how to use histograms to visualize the distributions of data, helping us understand the spread and patterns within the dataset.

2. **Overlaying Histograms**: We discovered how to superimpose histograms with different lengths on top of each other, enabling us to compare multiple data series effectively.

3. **Kernel Density Estimation (KDE)**: We explored using KDE to smooth out kinks in histograms, providing a clearer representation of the underlying data distribution.

4. **Improving KDE**: We learned how to specify boundaries on the KDE estimates, enhancing the visualization and insights gained from the KDE plot.

5. **Statistical Significance Testing**: We used Scipy to test for statistical significance by analyzing p-values, allowing us to make data-driven conclusions.

6. **Time Series Chart Highlighting**: We explored techniques to highlight different parts of a time series chart using Matplotlib, enhancing the visual representation of the data.

7. **Configuring Legends in Matplotlib**: We learned how to add and configure legends in Matplotlib, improving the interpretability of visualizations.

8. **NumPy's .where() Function**: We used NumPy's .where() function to process elements based on specific conditions, enhancing data processing capabilities.

## Summary of Findings

Through data visualization and analysis, we were able to understand Dr. Semmelweis's discovery and its profound impact on medical practices. The visualizations provided valuable insights into the significant reduction in mortality rates in maternity wards after the implementation of handwashing protocols. The statistical significance testing supported the robustness of the findings, reaffirming the importance of data-driven decision-making in medical practices.

The project sheds light on the historical significance of Dr. Semmelweis's work and serves as a testament to the power of data analysis in transforming and improving healthcare practices.

## Repository Structure

The repository is structured as follows:

```
/
|-- data/
|   |-- semmelweis_dataset.csv
|-- notebooks/
|   |-- handwashing_discovery.ipynb
|-- README.md
```

- The **data** directory contains the dataset file `semmelweis_dataset.csv`, which serves as the input for the data analysis and visualization.

- The **notebooks** directory contains the Jupyter Notebook file named `handwashing_discovery.ipynb`. This notebook contains the entire data analysis process, including data cleaning, manipulation, visualization, and statistical analysis using Python code.

- The **README.md** file (this file) provides an overview of the project, learning points, and repository structure.

## Usage

To explore the analysis and visualizations, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/Dr_Semmelweis_Handwashing_Discovery.git
   ```

2. Install the required dependencies by running:
   ```
   pip install pandas matplotlib scipy
   ```

3. Open the `handwashing_discovery.ipynb` Jupyter Notebook in the **notebooks** directory using Jupyter Notebook or JupyterLab.

4. Execute the code cells to run the data analysis, visualization, and statistical tests.

5. Feel free to modify the notebook and experiment with different visualizations or analysis techniques.

## Contributions

Contributions to this project are welcome! If you have any suggestions, improvements, or additional analyses, feel free to open an issue or submit a pull request.

When contributing to this repository, please ensure that your code adheres to best practices and is well-documented. Clearly explain the purpose and approach of your contribution.

