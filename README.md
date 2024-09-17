#Iris Dataset Visualization
This repository contains Python scripts for visualizing the Iris dataset using Matplotlib and Seaborn. Each script demonstrates different types of plots to explore various aspects of the Iris dataset. The Iris dataset, which consists of measurements of iris flowers from three different species, is commonly used for practicing data visualization and analysis.

#Files
general_statistics_plot.py - Python script for generating a pair plot of the Iris dataset.
species_frequency_pie_plot.py - Python script for generating a pie chart of species frequency.
sepal_relationship_scatter_plot.py - Python script for generating a scatter plot of sepal length vs. sepal width.
feature_distribution_plot.py - Python script for showing the distribution of sepal and petal features.
sepal_jointplot.py - Python script for creating a joint plot of sepal length vs. sepal width.
setosa_sepal_kde_plot.py - Python script for generating a KDE plot of sepal length vs. sepal width for the Setosa species.
setosa_petal_kde_plot.py - Python script for generating a KDE plot of petal length vs. petal width for the Setosa species.
#Requirements
Ensure you have the following Python libraries installed:

#pandas
#seaborn
#matplotlib
#scikit-learn (for loading the Iris dataset)
You can install the required libraries using pip:
1. #General Statistics Plot
#File: general_statistics_plot.py

This script uses Seaborn's pairplot to create a matrix of scatter plots and histograms. The pairplot function visualizes pairwise relationships and distributions among the features of the Iris dataset, color-coded by species. This helps in understanding the relationships between different features and their distributions.
2. #Pie Plot for Species Frequency
#File: species_frequency_pie_plot.py

This script generates a pie chart showing the frequency of each species in the Iris dataset. It provides a visual representation of the distribution of the three species.
3. #Relationship Between Sepal Length and Width
#File: sepal_relationship_scatter_plot.py

This script creates a scatter plot to explore the relationship between sepal length and sepal width. Points are color-coded by species, providing insight into how these two features are related and distributed among the species.
4. #Distribution of Sepal and Petal Features
#File: feature_distribution_plot.py

This script creates histograms with KDE overlays for each feature in the Iris dataset. It shows how the length and width of sepals and petals are distributed across the dataset.
5. #Jointplot of Sepal Length vs Sepal Width
#File: sepal_jointplot.py

This script uses Seaborn's jointplot to visualize both the joint distribution and the marginal distributions of sepal length and sepal width. It combines scatter plots with histograms to show how these features are related and distributed.
6. #KDE Plot for Setosa Species (Sepal Length vs Sepal Width)
#File: setosa_sepal_kde_plot.py

This script creates a KDE plot to estimate the probability density of sepal length and sepal width for the Setosa species. It provides a smoothed view of the distribution for these features.
7. #KDE Plot for Setosa Species (Petal Length vs Petal Width)
#File: setosa_petal_kde_plot.py

This script generates a KDE plot for petal length versus petal width specifically for the Setosa species, allowing for an analysis of these features’ density distribution.
