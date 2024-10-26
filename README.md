
# Hypothesis Testing on TV Promotion Budgets and Sales

This project performs hypothesis testing and a one-way ANOVA analysis to evaluate the impact of different levels of TV promotion budgets on sales. The analysis uses statistical tests, including Tukey’s HSD post hoc analysis, to explore significant differences in sales based on budget levels.

## Project Findings

### Summary of Analysis
This notebook provides an analysis of the effect of varying TV promotion budgets (high, medium, low) on sales:

- **ANOVA Test**: Tested whether there are statistically significant differences in sales among different budget levels.
- **Tukey’s Post Hoc Test**: Identified pairwise differences in mean sales between high, medium, and low budgets.
  
### Key Results
- **Estimated Mean Sales Differences**:
  - High vs. Low: $208.81M (95% CI: $200.99M - $216.64M)
  - High vs. Medium: $101.51M (95% CI: $93.69M - $109.32M)
  - Medium vs. Low: $107.31M (95% CI: $99.71M - $114.91M)
- **Statistical Significance**: The differences were statistically significant, supporting the impact of TV promotion budgets on sales.

### Model Insights
- **Regression Analysis**: A linear regression model with an R² of 0.871 confirms a significant relationship between TV budget and sales.

## Table of Contents
1. Project Overview
2. Dataset
3. Data Exploration
4. Hypothesis Testing
5. Post Hoc Analysis
6. Results and Interpretations
7. Conclusion
8. Technologies Used


## Project Overview
This analysis aims to test whether different TV promotion budgets significantly affect sales. Using one-way ANOVA and post hoc Tukey’s HSD analysis, it identifies significant pairwise differences between budget levels and evaluates the relationship between promotion budget and sales.

## Dataset
The dataset used in this analysis, `_tv_promotion_sales_data.csv`, includes the following columns:
- **TV Promotion Level**: High, Medium, Low
- **Sales**: Sales generated (in millions)

## Data Exploration
Exploration steps include:
- Displaying initial rows of data
- Checking for null values
- Cleaning the data
- Visualizing the distribution of sales across budget levels

## Hypothesis Testing
To test for significant differences, a one-way ANOVA was conducted. The null hypothesis that no difference exists between budget levels was rejected.

## Post Hoc Analysis
Tukey’s HSD test was applied to determine pairwise differences among the budget levels, confirming significant differences in sales between all groups.

## Results and Interpretations
- **ANOVA Results**: Significant differences across all TV promotion budget levels.
- **Model Summary**: A regression model provides additional insights into the relationship between budget size and sales.

## Conclusion
The analysis concludes that TV promotion budgets significantly impact sales, with higher budgets yielding higher sales figures.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels

