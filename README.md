# Time Series Features for Human Activity Monitoring
This repository contains the implementation of a system for extracting time series features for human activity monitoring, along with visualizations for different activities and body parts for 15 individuals.

### <a href='https://www.uni-mannheim.de/dws/research/projects/activity-recognition/#dataset_realworld'> Dataset</a>

## Feature 1
In this task, we apply the HVG and NVG methods to compute the following network measures:

* Average Degree
* Network Diameter
* Average Path Length

The data is tabulated for different subjects (1-15) and axes (Head and Chest). We create scatter plots to visualize the results for climbing up, climbing down, walking, and running activities for both Head and Chest in all directions (x, y, z).

## Feature 2
In the second task, we compute complexity and permutation entropy for the time series data in all three directions (x, y, z). The following parameters are considered:

* Embedded Dimensions (3, 4, 5, 6)
* Embedded Delay (1, 2, 3)
* Signal Length (1024, 2048, 4096)

Similar to Feature 1, scatter plots are created to visualize the results for climbing up, climbing down, walking, and running activities for both Head and Chest in all directions.

## Libraries
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)


