# Cereal-Dataset-Analysis
Multivariate statistical analysis of a cereal dataset using R. Includes data cleaning, exploratory data analysis, correlation analysis, and PCA to explore nutritional factors. Visualizations and key findings provide insights into the relationships within the dataset.
**Cereal Dataset:** The cereal dataset from the `liver` R package was used to understand the relationship between different nutritional values.

### Objectives 
   - Clean and preprocess the data by removing qualitative variables.
   - Perform exploratory data analysis (EDA) using visualizations.
   - Compute the correlation matrix for the numerical variables.
   - Conduct principal component analysis (PCA) to understand variance distribution and dimensionality reduction.
   - Visualize the dataset in two dimensions using PCA.
   - 
### Repository Structure
`Cereal_Analysis.Rmd` - R Markdown file containing the cereal dataset analysis.

### How to Use
To reproduce the analyses, clone this repository and open the R Markdown files (`.Rmd`). You can knit these files in RStudio to generate the HTML or Markdown outputs.
```bash
# Clone the repository
https://github.com/dandyy11/Cereal-Dataset-Analysis.git


### Findings
Distribution of Calories: The calorie distribution in cereals is right-skewed, indicating that most cereals have lower calorie counts, with the most common range being around 100-120 calories. Some cereals have significantly higher calorie counts, suggesting the presence of outliers.
Correlation Analysis: Strong positive correlations were observed between certain pairs, such as weight and cups, sugars and calories, and calories and fat. This suggests that cereals with higher fat content tend to have more calories and those with higher serving weights require more cups per serving.
Principal Component Analysis (PCA): The PCA results indicated that the first three principal components captured the most significant portion of variance in the dataset. This suggests that the dataset's dimensionality can be reduced effectively without losing a substantial amount of information.
2D Visualization: A 2D scatter plot using the first two principal components revealed distinct patterns and outliers in the dataset, highlighting variations in the nutritional content of cereals.

### Conclusion
The analysis of the cereal dataset revealed key insights into the nutritional content of various cereals. The correlation analysis identified strong relationships between nutritional variables, and the PCA effectively reduced the dataset's dimensionality while retaining most of the variance. This multidimensional analysis provides a deeper understanding of the factors contributing to the nutritional profile of cereals, which can be useful for both manufacturers and consumers in making informed choices.
