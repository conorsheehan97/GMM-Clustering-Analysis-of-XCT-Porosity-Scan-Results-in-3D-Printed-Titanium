# GMM Clustering Analysis of XCT Porosity Scan Results in 3D Printed Titanium
## Overview
This project aims to implement Gaussian Mixture Model (GMM) clustering to analyze XCT porosity scan results in 3D printed Titanium components. The goal is to investigate how porosity morphology develops with increasing gas flow rates during the printing process.

## Background
Porosity defects in Titanium bone implants are analyzed using X-Ray CT scans, providing comprehensive data on pore geometry and quantity. This project focuses on understanding how the proportion of irregular (potentially more damaging) pores changes with different gas flow rates used in three separate builds of Titanium components.

## Methodology
### Data Collection:
 - XCT porosity scan data collected from three separate builds of Titanium components, each at a different gas flow rate.

### Cluster Analysis:
 - Initial evaluation of the dataset for optimal number of clusters using various evaluation methods.
 - Implementation of Gaussian Mixture Model (GMM) clustering to identify distinct clusters within the porosity scan data.

### Analysis:
Analysis of how the proportions of these clusters vary with respect to gas flow rates, aiming to understand the impact of gas flow on porosity morphology.

### Models Used
#### KMeans Clustering
 - Gaussian Mixture Model (GMM)
### Libraries Used
 - Pandas
 - Numpy
 - Matplotlib
 - Seaborn
 - Scikit-learn

## Conclusion
This project explores the application of Gaussian Mixture Model (GMM) clustering to analyze XCT porosity scan data from 3D printed Titanium components. By investigating cluster proportions across different gas flow rates, we aim to provide insights into how porosity morphology evolves during the additive manufacturing process. The findings could contribute to optimizing manufacturing parameters for improved Titanium bone implants.

Contributions and feedback are welcome to enhance this project's capabilities and broaden its applications in materials science and manufacturing.
