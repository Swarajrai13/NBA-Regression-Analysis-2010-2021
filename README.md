# NBA-Regression-Analysis-2010-2021
## This is the repository for the regression analysis I conducted in 2022 of statistical drivers of winning in the NBA between 2010-2021.

In this project, I scraped data from the internet on NBA team statistics from the early 2000s up to the 2020-2021 season. I subsetted this data to the modern period of the last 10 years worth of data and conducted a range of statistical tests including basic correlation/fit tests, regression analysis + modeling, k-means clustering, cluster plots, and cross-validation techniques to determine the statistical significance of which stats in basketball best predict regular-season performance outcomes.

After conducting data management, analysis, and visualization, conveying important concepts and outcomes to expert and non-expert interactors was done through a written report in the style of a scientific research paper. This included an abstract, Introduction, Methods, Results, and Conclusions/Implications for the reader to draw as much insight as possible from the contents of this research project.

## Contents:
- *finalproject_rai01.html*: R Markdown file of the entire data management, analysis, and visualization life-cycle.

- *Final paper_srai01.pdf*: A written report in the style of a scientific research paper documenting the project background, hypothesis, methodology, results, and conclusions and implications.

- *cluster plot.jpg*: Cluster plot to help understand how similarly performing teams are sorted into 4 distinct clusters that demonstrate major overlap

- *Principal Component Analysis plot.jpg*: PCA plot to visualize the variability of certain statistics to narrow down main statistical drivers of "winningness" in the NBA

- *K-means clustering.jpg*: Machine Learning technique for grouping unlabeled data into clusters. The goal is to find an optimal number of clusters in the data, which in this case, appears be 4/5. This is in-line with the cluster plot that can be found in this repository.
