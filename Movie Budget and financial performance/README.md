# Movie Budget and Financial Performance Data Science Project

This GitHub repository contains a data science project that aims to explore the relationship between movie budgets and box office revenue. The project utilizes data scraped from [the-numbers.com](https://www.the-numbers.com/movie/budgets) on **May 1st, 2018**. The primary question we seek to answer is: Do higher film budgets lead to more box office revenue? By analyzing the movie budgets and financial performance data, we aim to uncover insights into the potential correlation between budget investments and revenue returns in the film industry.

## Project Overview

The film industry often invests significant resources in movie production, marketing, and distribution. One key factor that influences a movie's financial success is its budget. Understanding whether higher budgets correspond to higher box office revenue can provide valuable insights to movie producers, studios, and investors, guiding their decision-making processes. The dataset from [the-numbers.com](https://www.the-numbers.com/movie/budgets) contains comprehensive information about movie budgets and box office performance, making it an ideal resource for this analysis.

## Learning Points

Throughout the project, we covered several essential concepts and techniques in data analysis and visualization. Some of the key learning points include:

1. **Data Cleaning**: We learned how to use nested loops to remove unwanted characters from multiple columns, ensuring that the data is in a suitable format for analysis.

2. **Filtering DataFrames**: We explored filtering Pandas DataFrames based on multiple conditions using both `.loc[]` and `.query()` methods, enabling us to extract specific subsets of the data relevant to our analysis.

3. **Bubble Charts with Seaborn**: We created bubble charts using the Seaborn library, a powerful tool for visualizing relationships between three variables in a dataset.

4. **Styling Seaborn Charts**: We learned how to style Seaborn charts using pre-built styles and by modifying Matplotlib parameters, allowing us to customize the visual appearance of our plots.

5. **Data Transformation**: We used floor division (integer division) to convert years into decades, a common technique in data preprocessing to aggregate data at a coarser granularity.

6. **Linear Regression Analysis**: We performed linear regressions on the data and used Seaborn to superimpose the regression line on our scatter plots. Additionally, we discussed how to evaluate the regression model's fit using the r-squared metric.

7. **Regression with scikit-learn**: We ran regressions using scikit-learn, a popular machine learning library, and calculated the coefficients to understand the relationships between movie budgets and box office revenue.

## Summary of Findings

Through our analysis of movie budgets and financial performance data, we discovered important insights into the relationship between film budgets and box office revenue. By visualizing the data using bubble charts and performing linear regression analyses, we identified trends and patterns that shed light on the correlation between budget investments and revenue returns in the movie industry.

Our findings can be valuable to film producers, studios, and investors in several ways. Understanding the correlation between budgets and box office revenue can help in budget allocation decisions, risk assessment, and overall financial planning for movie projects. It provides guidance on resource allocation, potential revenue expectations, and can contribute to more informed decision-making in the filmmaking process.



## Usage

To explore the analysis and visualizations, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/movie-budget-financial-performance.git
   ```

2. Install the required dependencies by running:
   ```
   pip install pandas seaborn scikit-learn
   ```

3. Open the `movie_budget_analysis.ipynb` Jupyter Notebook in the **notebooks** directory using Jupyter Notebook or JupyterLab.

4. Execute the code cells to run the data analysis, visualization, and regression models.

5. Feel free to modify the notebook and experiment with different visualizations or analysis techniques.

## Contributions

Contributions to this project are welcome! If you have any suggestions, improvements, or additional analyses, feel free to open an issue or submit a pull request.

When contributing to this repository, please ensure that your code adheres to best practices and is well-documented. Clearly explain the purpose and approach of your contribution.

