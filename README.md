## Assignment 5 -  Visualizing Data Veracity Challenges in Multi-Label Classification

NAME - TANISHKA BAIS

ROLL NO - NA22B076

The assignment focuses on simplifying the visualization of a multi-label dataset by reducing label complexity. Since plotting all 14 labels directly would be overwhelming, we create a new target variable for visualization with only three distinct categories:

TopSingles → Represents the two most frequent single-label classes (grouped together).

TopMultiCombo → Represents the most frequent multi-label combination.

Other → Represents all remaining labels and combinations.

The dimensionality reduction techniques t-SNE and Isomap are applied to the dataset for visualization, allowing us to compare how different methods preserve structure in the data.

### Key Steps:

##### 1.Data Preprocessing

Converted multi-hot encoded labels into simplified categories.

Identified top 2 single labels and top multi-label combination.

Assigned "TopSingles", "TopMultiCombo", and "Other" categories for visualization.

##### 2. Dimensionality Reduction

Applied t-SNE with different perplexities (e.g., 5, 30) to observe local/global structure.

Applied Isomap to preserve global geometry.

Created side-by-side comparison plots.

##### 3. Visualization

Color-coded scatter plots with only 3 distinct categories to make interpretation clear.

Compared how "TopSingles" and "TopMultiCombo" distribute under t-SNE vs. Isomap.

### Repository Contents

Assignment_5_DA5401.ipynb → Main Jupyter notebook with full code, explanations, and visualizations.

README.md → This file (overview + instructions).

yeast.arff -> Dataset containing 2417 data points and 117 columns where first 103 columns are features and the remaining 14 columns are target classes.


### Learnings:

1. Understanding how to simplify complex label structures for visualization.

2. Applying t-SNE and Isomap for dimensionality reduction.

3. Comparing local vs. global structure preservation in embeddings.

