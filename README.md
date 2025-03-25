# Association_Analysis : Market Basket Analysis with Interactive Visualizations
This repository contains a comprehensive project on Market Basket Analysis using Python. The project explores a retail transactions dataset, performs data cleaning and preprocessing, applies the Apriori algorithm to mine frequent itemsets, and generates association rules. Interactive visualizations created with Plotly, Seaborn, and NetworkX help in uncovering and presenting insights in a professional manner.

Project Overview
Data Exploration:
Analyze the dataset structure, display data types, and summarize key statistics. The analysis includes counting transactions by country and visualizing item frequency distributions.

Data Cleaning & Preprocessing:
Handle missing values, remove duplicates, and filter out canceled transactions. Transform transaction data into a one-hot encoded format suitable for association rule mining.

Frequent Itemset Mining:
Utilize the Apriori algorithm to extract frequent itemsets based on a minimum support threshold.

Association Rule Generation:
Generate association rules from frequent itemsets using confidence as the metric. Explore the rules sorted by support, confidence, and lift.

Interactive Visualizations:
Create interactive charts using Plotly:

Bar Charts: Interactive visualizations for transactions by country and item frequency distributions.

Heatmaps: Detailed interactive heatmaps for support, confidence, and lift between itemsets.

Network Graphs: Visualize association rules as an interactive network graph using NetworkX and Plotly.

Scatter Plot: Explore relationships between lift and confidence.

Additional static visualizations with Matplotlib and Seaborn complement the interactive dashboards.

Technologies & Libraries
Python 3.x

Pandas: Data manipulation and analysis.

Matplotlib & Seaborn: Data visualization.

Plotly Express & Plotly Graph Objects: Interactive data visualizations.

NetworkX: Graph-based visualization of association rules.

mlxtend: Frequent itemset mining (Apriori algorithm) and association rules.

WordCloud: Visual representation of frequent items.
