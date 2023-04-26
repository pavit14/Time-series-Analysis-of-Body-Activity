# Time Series Features for Human Activity Monitoring
This repository contains the implementation of a system for extracting time series features for human activity monitoring, along with visualizations for different activities and body parts for 15 individuals. 
<a href='https://www.uni-mannheim.de/dws/research/projects/activity-recognition/#dataset_realworld'> Dataset</a>
## Feature 1
The first task involves applying the HVG (Horizontal Visibility Graph) and NVG (Natural Visibility Graph) methods to compute the average degree, network diameter, and average path length. The data is tabulated for different subjects (1-15) and axes for Head and Chest. Scatter plots are created for climbing up, climbing down, walking, and running for head and chest in all directions (x, y, z).
## Feature 2
The second task involves computing complexity and permutation entropy for the data in all three directions (x, y, z). The data is tabulated for different subjects (1-15), axes, Embedded Dimensions (3, 4, 5, 6), Embedded Delay (1, 2, 3), and Signal Length (1024, 2048, 4096). Scatter plots are created for climbing up, climbing down, walking, and running for head and chest in all directions (x, y, z).
## Libraries
* numpy
* pandas
* matplotlib
* os
* re
* seaborn

