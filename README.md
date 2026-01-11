Global Child Well-Being Analysis (UNICEF SOWC)

Goal: Analyze global child well-being indicators to identify disparities across regions and income levels, and communicate these patterns through clear, interpretable visualizations.

Tools: R, ggplot2, dplyr, Excel
Methods: Data cleaning, exploratory data analysis (EDA), comparative visualization, descriptive statistics

1) Problem / Research Question

International organizations and policymakers rely on large-scale survey data to assess child well-being and prioritize interventions. However, these datasets are complex and difficult to interpret without careful analysis and visualization.

This project asks:

How do child well-being outcomes vary across countries and regions, and what broad socioeconomic patterns emerge at a global level?

2) Dataset

Dataset: UNICEF – State of the World’s Children (SOWC)

Scope: Global, country-level indicators

Key dimensions:

Health outcomes

Education indicators

Socioeconomic measures

Data sources provided in CSV and Excel formats

Note: Data quality and availability vary by country and indicator, requiring careful handling of missing values and inconsistent reporting.

3) What I Did (Process)
Data Preparation

Cleaned and standardized raw UNICEF data using R

Resolved missing values and inconsistent formatting

Verified summaries and aggregates using Excel

Selected relevant indicators for cross-country comparison

Analysis & Visualization Strategy

Conducted exploratory analysis to identify regional and income-based patterns

Designed comparative visualizations to highlight disparities across countries and regions

Iteratively refined plots to improve clarity, readability, and interpretability

Focused on communicating insights clearly to non-technical audiences

4) Final Outputs

The final deliverables consist of a set of visualizations and written analysis that:

Compare child well-being indicators across regions

Highlight persistent global disparities

Support interpretation by policymakers, educators, and public health stakeholders

5) Key Results (What I Found)

Large disparities in child well-being outcomes persist across income levels and regions.

Several indicators exhibit strong regional clustering, suggesting structural and systemic influences.

Visualization design choices (scales, grouping, labeling) significantly affected how patterns were perceived and understood.

Interpretation:
Clear visualization is essential for making global inequality visible. Even simple descriptive comparisons can reveal meaningful patterns when data are properly cleaned and presented.

6) Limitations

Analysis is descriptive and does not establish causality.

Data availability varies across countries and indicators.

Aggregation at the country level may mask within-country variation.

7) Future Improvements

If I expanded this project, I would:

Add interactive dashboards (e.g., Tableau or Shiny)

Incorporate additional years or complementary datasets

Apply statistical modeling to explore associations more formally

Include geographic mapping to add spatial context

8) How to Run

Clone the repository

Open the project in RStudio

Install required packages:

dplyr, ggplot2

Ensure the dataset files are in the project directory


9) Outputs

Cleaned dataset used for analysis

Exploratory visualizations highlighting global disparities

Written interpretation of findings

10) Skills Demonstrated:

Data cleaning and preprocessing

Exploratory data analysis (EDA)

Data visualization and communication

Working with real-world international datasets

Translating quantitative findings into clear insights
