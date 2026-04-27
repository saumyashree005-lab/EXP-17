# NAME : SAUMYA SHREE
# PRN : 25070123161

# THEORY:

Data visualization is the graphical representation of data to understand patterns, trends, and relationships. In Python, visualization is commonly performed using libraries like pandas, matplotlib, seaborn, and numpy.
* pandas is used for data handling and creating DataFrames.
* matplotlib is used for basic plotting like line charts, bar charts, histograms, and scatter plots.
* seaborn is used for advanced and more visually appealing statistical plots.
* numpy is used for numerical calculations like mean.
  
# FUNCTIONS AND COMMANDS USED:

1. Importing Libraries
import pandas as pd → Used for data manipulation and DataFrame creation.
import matplotlib.pyplot as plt → Used for plotting graphs.
import seaborn as sns → Used for advanced data visualization.
import numpy as np → Used for numerical operations (like mean).
2. Data Creation
pd.DataFrame(data) → Creates a DataFrame from dictionary data.
3. Line Plot
plt.plot(x, y) → Creates a basic line chart.
plt.figure(figsize=(w,h)) → Sets figure size.
plt.xlabel() / plt.ylabel() → Labels axes.
plt.title() → Sets graph title.
plt.legend() → Displays legend.
plt.show() → Displays the plot.
4. Bar Chart
plt.bar(x, y) → Creates a bar graph.
plt.text() → Adds labels on bars (used for advanced bar graph).
plt.grid() → Adds grid lines.
5. Histogram
plt.hist(data, bins=) → Shows distribution of data.
edgecolor → Adds border to bars.
alpha → Controls transparency.
np.mean() → Calculates mean value.
plt.axvline() → Draws a vertical line (used to show mean).
6. Scatter Plot
plt.scatter(x, y) → Shows relationship between variables.
7. Seaborn Visualizations
sns.lineplot() → Advanced line graph.
sns.barplot() → Advanced bar chart.
sns.histplot() → Histogram using seaborn.
sns.scatterplot() → Scatter plot using seaborn.
8. Additional Concepts
Conditional Visualization → Coloring points based on category (Pass/Fail).
Annotations → Displaying values on bar charts.
Multiple DataFrames → Working with more than one dataset.

# GRAPHS CREATED IN THIS EXPERIMENT:
* Line Chart (Study Hours Trend)
* Advanced Line Chart (Study Hours vs Marks)
* Bar Chart (Marks per Day)
* Advanced Bar Chart (with value labels)
* Histogram (Marks Distribution)
* Histogram with Mean Line
* Scatter Plot (Study Hours vs Marks)
* Conditional Scatter Plot (Pass/Fail)
* Seaborn Line Plot (Sales Trend)
* Seaborn Bar Plot (Profit Analysis)
* Seaborn Histogram (Sales Distribution)
* Seaborn Scatter Plot (Sales vs Profit)

# CONCLUSION:

Data visualization using Python helps in understanding data easily through graphical representation. Using libraries like matplotlib and seaborn, we can analyze trends, distributions, and relationships effectively. This experiment demonstrates how different types of graphs can be used to extract meaningful insights from data.
