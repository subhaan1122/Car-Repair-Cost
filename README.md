🚗 Car Repair Cost Analysis:

This project analyzes a dataset containing car repair data, including various attributes such as scratch size, repair time, dent type, and costs associated with dents and scratches. The analysis aims to identify patterns in repair costs, correlations between features, and significant insights that could help in cost prediction and optimization.

📌 Overview:

- Dataset: car.xlsx
- Objective: Analyze repair costs for different car brands and parts, and explore correlations with various features like scratch size, repair time, and dent type.
- Tools: pandas, matplotlib, seaborn
- Key Metrics: Distribution analysis, correlation heatmap, box plots, scatter plots

⚙️ How It Works:

1- Data Loading & Preprocessing:

- Loads the car repair data from an Excel file using pandas.
- Displays the first few rows, dataset info, and checks for missing values and duplicates.

2- Data Analysis & Visualization:

- Histograms for numerical features to observe their distribution.
- Count plots for categorical features (e.g., brand, part).
- Scatter plots to observe the relationships between repair cost and other features like scratch size and time to repair.
- Heatmap for the correlation matrix of numerical features.
- Box plots to visualize the distribution of Cost_of_Dent and Cost_of_Scratch across different car brands and parts.

3- Insights & Summary:

Provides observations about the data, including relationships between scratch size, repair time, dent type, and repair costs.

📊 Visualizations:

- Distribution of Numerical Features:
The script generates histograms to visualize the distribution of numerical features such as scratch size, repair time, and cost.

- Count Plots for Categorical Features:
Categorical features such as car brand and part type are visualized using count plots to see how their frequencies vary.

- Scatter Plots:
  
Two scatter plots are generated to explore:
Scratch Size vs. Total Cost
Time to Repair vs. Total Cost

- Correlation Heatmap:
A heatmap is created to identify any correlations between numerical features like scratch size, repair time, and total cost.

- Box Plots for Repair Costs:
Box plots are plotted to analyze the relationship between different brands and parts with respect to the cost of dents and scratches.

📉 Insights:

- Scratch Size and Total Cost Correlation: There is a positive correlation between scratch size and total cost—larger scratches generally lead to higher repair costs.
- Time to Repair and Total Cost: Time to repair shows a mild positive relationship with total cost. More time-consuming repairs tend to be costlier.
- Dent Type Impact: Dent type (shallow vs. deep) does not have a major impact on cost variation for scratch size or repair time.
- Correlation Heatmap: No significant multicollinearity was found among the numerical features, indicating that features can be used independently for modeling.
- Repair Trends: Most repairs involve medium-sized scratches with moderate costs, and the box plots show how Cost_of_Dent and Cost_of_Scratch vary across different brands and parts

🌟 Show some ❤️ by starring this project!
